<script>
    import '../styles.css'
    import Sidebar from '../components/Sidebar.svelte'
</script>

<svelte:head>
    <title>Media Hack Lab</title>
</svelte:head>
<main>
   <Sidebar />
<div class="content">
   <div class="logo"><img src="/lablogo.png"></div>
    <slot />
</div>
</main>

<style>
    .logo img  { 
        max-width: 400px;
        margin-top: 30px;
    }
    .content { 
        padding-bottom: 300px;
    }
</style>
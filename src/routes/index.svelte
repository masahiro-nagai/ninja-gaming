<script>
    let title = "Ninja Gaming Guides";

    const updateTitle = () =>{
        title = "something completely title";
    }
</script>

<div class="index">
    <h2>{title}</h2>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Amet odit cupiditate tenetur optio. Ullam, culpa? Perspiciatis, soluta molestias! Doloremque aliquid ratione beatae hic quasi, similique maxime asperiores fugiat pariatur totam voluptas deserunt repellendus, explicabo officia rem enim fugit incidunt perspiciatis. Omnis nulla nostrum ullam libero nemo? Odio eveniet alias nulla nemo dignissimos quia, pariatur voluptates, asperiores molestias minima porro perspiciatis.</p>
    <button on:click={updateTitle}>change title</button>
    <input type="text" bind:value={title}>
</div>
<style>
    .index{
        text-align: center;
        display: block;
        margin: 20px auto;
    }
</style>

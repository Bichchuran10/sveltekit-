<script>
        export let productId=100;
</script>

<a href="/">Home</a>

<h1>Product List</h1>
<h2> <a href="/products/1"> Product 1 </h2>
<h2> <a href="/products/2"> Product 2 </h2>
<h2> <a href="{`/products/${productId}`}> Product 3 </h2>
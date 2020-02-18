<template>
    <main class="content">
        <div class="container flex space-between">
            <ProductList />
            <Aside />
        </div>
    </main>
</template>

<script>
import ProductList from './ProductList'
import Aside from './Aside'
export default {
    components: {
        ProductList,
        Aside
    }
}
</script>
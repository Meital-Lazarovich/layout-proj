<template>
    <main class="content flex space-between">
        <ProductList />
        <Aside />
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
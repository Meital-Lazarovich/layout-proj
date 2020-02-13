<template>
    <section class="Home">
        <AppHeader />
        <Hero />
        <PageFilter />
        <Content />
    </section>
</template>

<script>
import AppHeader from '../components/AppHeader';
import Hero from '../components/Hero';
import PageFilter from '../components/PageFilter';
import Content from '../components/Content';

export default {
    components: {
        AppHeader,
        Hero,
        PageFilter,
        Content
    }
}
</script>
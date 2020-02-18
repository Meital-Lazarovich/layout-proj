<template>
    <section class="article-list">
        <h1 class="list-header"></h1>
        <hr />
        <article class="flex space-between" v-for="idx in 3" :key="idx">
            <div class="article-img"></div>
            <div class="main flex space-between column">
                <p class="article-header"></p>
                <a href class="article-link"></a>
            </div>
        </article>
    </section>
</template>
<template>
    <aside>
        <ArticleList></ArticleList>
        <Promoted></Promoted>
    </aside>
</template>

<script>
import ArticleList from './ArticleList'
import Promoted from './Promoted'

export default {
    components: {
        ArticleList,
        Promoted
    }
}
</script>
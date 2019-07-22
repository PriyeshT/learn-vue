<template>
    <blockquote>{{ quote }}</blockquote>
</template>

<script>
export default {
    name: 'BlockQuote',
    props: {
        quote: String
    }
}
</script>

<style>
blockquote {
    padding: 1em;
    font-family: 'Muli', sans-serif;
    font-size: 1.6em;
    margin: 0;
    text-align: left;
    border-left: .4em solid sandybrown;
}

blockquote::before, blockquote::after {
    font-size: 1.8em;
}

blockquote::before {
    content: '\201C';
}

blockquote::after {
    content: '\201D';
}


</style>



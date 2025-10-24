<template>
    <footer>
        <p>For more info about the API consult <a src="https://osv.dev/" target="_blank">OSV API</a></p>
        <p>©2025 <a href="https://kerumosolutions.com" target="_blank">Kevin Ruiz Molina</a>. All rights reserved.</p>
    </footer>
</template>

<script lang="ts">
</script>

<style scoped>
    footer {
        position: fixed;
        bottom: 0;
        padding: 16px;
        display: flex;
        justify-content: center;
        width: 100vw;
        flex-wrap: wrap;
        background-color: var(--gray);
    }
    a {
        font-weight: 700;
        color: #FFF;
    }
    @media screen and (min-width: 768px) {
        footer { 
            justify-content: space-between;
        }
    }
</style>
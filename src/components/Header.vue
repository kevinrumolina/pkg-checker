<template>
    <header>
        <img src="https://google.github.io/osv.dev/assets/logo-dark.png" alt="OSV Logo">
        <h1>Vulnerabilities Scanner</h1>
    </header>
</template>

<style scoped>
    header {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-top: 50px;
    }
    h1 {
        font-size: 36px;
        margin-top: 25px;
        text-align: center;
    }
    img {
        padding: 0 20%;
        width: 100%;
    }
    @media screen and (min-width: 768px) {
        h1 { 
            font-size: 64px;
        }
    }
</style>
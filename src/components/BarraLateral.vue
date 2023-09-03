<template>
    <header>
        <h1>
            <img alt="Tracker logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />
        </h1>
    </header>
</template>

<style scoped>
header {
    background: #0d3b66;
    width: 100%;
    height: 100vh;
    padding: 1rem;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media only screen and (max-width: 768px){
    header {
        padding: 2.5rem;
        height: auto;
    }

    .logo {
        margin: 0 2rem 0 0;
    }
}
</style>
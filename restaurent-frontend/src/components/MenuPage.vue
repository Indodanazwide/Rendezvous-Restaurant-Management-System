<template>
    <div class="menu">
        <!-- Banner -->
        <header>
            <h1>Menu</h1>
        </header>

        <main class="menu">
            <div class="container">
                <div class="logo"></div>
                <div class="text">
                    <p>

                    </p>
                </div>
            </div>
        </main>
    </div>
</template>

<style>
.menu {
    padding: 12vh 0;
}

header {
  height: 20vh;
  width: 100%;
  background-color: #0F152C;
  color: #b2a43b;
  text-align: center;
  padding-block: 1.5rem;
}

.container {
    display: flex;
    justify-content: center;
}

.logo {
    width: 10rem;
    height: 10em;
    background-image: url('@/assets/images/png/brand-logo.png');
    background-size: contain;
    background-repeat: no-repeat;
}



</style>
<template>
    <div class="container-fluid">
        
        <Navbar />

        <slot />

        <Footer />
    </div>
</template>

<style>
.container-fluid {
    margin: 0;
    padding: 0;
}

.primary {
    color: #0099ff;
}
</style>
<template>
    <div>
        <div class="navItem">
        <nav class="navbar navbar-expand-lg navbar-light">
            <div class="container-fluid">
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item" v-for="navItem in navItems" :key="navItem">
                    <a class="nav-link" aria-current="page" href="#">
                        {{navItem}}
                    </a>
                    </li>
                </ul>
                </div>
            </div>
        </nav>
    </div>
    </div>
</template>
<script>
export default {
    name: 'Header',
    data() {
        return {
        navItems: [
            'Home',
            'Products & Services',
            'Become a client',
            'About us'
      ]
        }
    }
}
</script>
<style scoped>

</style>

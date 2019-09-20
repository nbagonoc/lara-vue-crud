<template>
<nav class="navbar navbar-expand-md navbar-light">
    <div class="container">
        <router-link class="navbar-brand" to="/">My Vue App</router-link>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarCollapse">
            <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
                <router-link class="nav-link" to="/">Home</router-link>
            </li>
            </ul>
        </div>
    </div>
</nav>
</template>

<script>
    export default {
        name: 'app-header'
    }
</script>

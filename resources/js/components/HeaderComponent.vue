<template>
    <div class="container^fruid bg-dark mb-3">
        <div class="container">
            <nav class="navbar navbar-dark">
                <span class="navbar-brand mb-0 h1">Vue Laravel SPA</span>
                <div>
                <router-link :to="{name: 'task.list'}">
                    <button class="btn btn-success">List</button>
                </router-link>
                <router-link :to="{name: task.create}">
                    <button class="btn btn-success">Add</button>
                </router-link>
                </div>
            </nav>
        </div>
    </div>
</template>

<script>
    export default {}
</script>
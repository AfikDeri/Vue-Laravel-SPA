<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card card-default">
                    <div class="card-header">Vue.JS SPA example</div>

                    <div class="card-body">
                        <h2>{{ welcome }}</h2>
                        <img src="https://camo.githubusercontent.com/f2f5547663dd4286b279d319270607316d5af2cc/68747470733a2f2f63646e2e706272642e636f2f696d616765732f486477437574382e706e67" alt="WeCode">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'home',
        computed: {
            welcome() {
                return this.$store.getters.welcome
            }
        }
    }
</script>

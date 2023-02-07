<template>
    <div class="container">
        <div class="row">
            <div class="col">
                <div class="bg-secondary text-white my-3 py-3 card">
                    <div class="card-body">
                        This is call to action component.
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'CallToAction',
    props: {
        msg: String
    }
}
</script>

<style scoped>
</style>
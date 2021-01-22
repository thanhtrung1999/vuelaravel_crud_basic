<template>
    <div class="home__component">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card card-default">
                    <div class="card-header">Home Component</div>

                    <div class="card-body">
                        I'm the Home Component component.
                    </div>
                </div>
            </div>
        </div>
        <hr>
        <div class="row justify-content-center">
            <example-component />
        </div>
    </div>
</template>

<script>
export default {
    name: "HomeComponent",
    mounted() {
        console.log('Component mounted.')
    }
}
</script>

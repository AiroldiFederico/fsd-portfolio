<script>
    import {store} from '../store'
    export default {

        name: "NavBarComp",
        components: {
            
        },

        data() {
            return {
                store,
            }
        },

        methods: {

        }
    };

</script>


<!-- NAVBAR -->
<template>
    <div>
        <nav class="navbar">
            <button class="btn ms-2" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasWithBothOptions" aria-controls="offcanvasWithBothOptions">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="offcanvas offcanvas-start" data-bs-scroll="true" tabindex="-1" id="offcanvasWithBothOptions" aria-labelledby="offcanvasWithBothOptionsLabel">
            <div class="offcanvas-header">
                <h5 class="offcanvas-title" id="offcanvasWithBothOptionsLabel">Backdrop with scrolling</h5>
                <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
            </div>
            <div class="offcanvas-body">
                <p>Try scrolling the rest of the page to see this option in action.</p>
            </div>
            </div>
        </nav>
    </div>
</template>


<style lang="scss" scoped>

.navbar-toggler-icon {
    color: #1F2440 !important;
    
    font-size: 1.5rem;
    
}

.offcanvas {
    background-color: antiquewhite !important;
}


</style>
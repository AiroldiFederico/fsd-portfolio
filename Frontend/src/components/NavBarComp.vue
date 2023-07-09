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
        <nav class="navbar fixed-top bg-body-tertiary">
            <div class="container-fluid">
              <!-- Leftside -->
              <div>
      
              </div>
      
              <!-- Center Logo -->
              <div>
                  <h2 id="logo">AIRO</h2>
              </div>
      
              <!-- Rightside -->
              <div>
      
              </div>     
            </div>
        </nav>
    </div>
</template>


<style lang="scss" scoped>

    #logo {
        font-weight: bolder;
    }

</style>
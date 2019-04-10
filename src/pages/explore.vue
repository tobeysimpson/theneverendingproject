<template>
    <b-container fluid align-v="center">
        <!-- Content here -->
        <b-row align-h="center" align-v="center">
            <h4 class="text-center">Find your aesthetic treatment provider</h4>
        </b-row>
        <b-row align-v="center">
            <b-container class="bv-example-row" fluid>
                <b-row>
                    <b-col>
                        <vue-bootstrap-typeahead 
                            v-model="query"
                            :data="['Miami', 'Oklahoma']"
                            placeholder="Enter Your City"
                        />
                    </b-col>
                    <b-col>
                        <b-button variant="outline-primary">Search</b-button>
                    </b-col>
                </b-row>
            </b-container> 
        </b-row>
    </b-container>
</template>

<script>
    import VueBootstrapTypeahead from 'vue-bootstrap-typeahead'
    export default {
        components: {
            VueBootstrapTypeahead
        }
    }
</script>
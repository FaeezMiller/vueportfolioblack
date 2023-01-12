<template>
    <div class="content-container">
        <h3>Education</h3>
    </div>
    <div>
    <dt v-for="educate in education" :key="educate" class="text-center d-flex flex-column">
    <dr class="fw-bold">{{ educate.educationLevel }}</dr>|{{ educate.year }}</dt>
    <dd class="lead">{{ educate.description }}</dd>
    </div>
</template>

<script>

import { mapActions,mapGetters} from 'vuex';
export default{
    name: "educationComponent",
    computed: {
        ...mapGetters(["education"])
    },
    methods: {
        ...mapActions(["fetchEducation"])
    },
    created(){
        this.fetchEducation();
    }
}
</script>
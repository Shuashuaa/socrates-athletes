<template>
	<HomeComp/>
	<DetailsComp/>
</template>

<script>
import { defineComponent } from 'vue';

import HomeComp from '../components/HomeComp.vue';
import DetailsComp from '../components/DetailsComp.vue';

export default defineComponent({
    components: {
        HomeComp,
        DetailsComp,
    },
});

</script>
<template>
    <div class="calc pa-6 ma-6">
        <v-text-field >
        </v-text-field>
        <p>{{ $store.state.count }}</p>
        <v-btn @click="$store.commit('incrementBy')">

        </v-btn>
    </div>
</template>

<script>
export default {
    name: 'CalcView',
    components: {

    },
    data() {
        return {

        }
    }
}
</script>
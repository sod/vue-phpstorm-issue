<template>
    <div>
        {{ bar }}
        {{ getBar() }}
        {{ computedBar }}
    </div>
</template>

<script lang="ts">
    import {Component, Prop, Vue} from 'vue-property-decorator';

    @Component()
    export default class extends Vue {
        @Prop() bar: number;

        getBar(): number {
            return 0;
        }

        get computedBar(): number {
            return 0;
        }
    }
</script>

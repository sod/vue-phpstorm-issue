<template>
    <div>
        {{ foo }}
        {{ getFoo() }}
        {{ computedFoo }}
    </div>
</template>

<script>
    export default {
        props: [
            'foo'
        ],
        methods: {
            getFoo() {
            }
        },
        computed: {
            computedFoo() {
            }
        },
    }
</script>

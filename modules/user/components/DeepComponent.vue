<script setup lang="ts">
defineProps({
    msg: {
        type: String as PropType<string>,
    }
})

const count = ref(1)

const state = useState('test', () => {})

const api = useApi()

</script>

<template>
    <div>
        DeepComponent
    </div>
</template>
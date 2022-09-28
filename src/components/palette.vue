<template>
<input @click="function(){alert(colorbg)}" v-model="colorbg" type="color" id="color-picker" />
</template>
<style></style>
<script>

</script>
//@click="$emit(`colorpick`, colorbg)"//
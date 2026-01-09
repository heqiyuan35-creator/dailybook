<template>
    <div>
       <p>忘记了导出组件？？？{{ n.myProps }}</p>
    </div>
</template>
<script setup>
    let n=defineProps(["myProps"])

</script>
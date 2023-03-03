<template>
<div>
    <h3>Mixin  A</h3>
    <button @click="increament">Click Here {{ count }}</button>
</div>
</template>

<script>
import count from '../mixins/count'
export default {
    name:"MixinA",
    mixins:[count]
}
</script>

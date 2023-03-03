<template>
    <div>
        <h3>Mixin  B</h3>
        <button @click="increament">Click Here {{ count }}</button>
    </div>
    </template>
    
    <script>
    import count from '../mixins/count'
    export default {
        name:"MixinB",
        mixins:[count]
    }
    </script>
    
<template>
    <p ref="paragraph"></p>
</template>

<script>
    import Lorem from './lorem';

    export default {
        name: "lorem",
        methods: {
            putLoremText : function(){
                var lorem = new Lorem;
                lorem.type = Lorem.TEXT;
                lorem.query = this.add;
                lorem.createLorem(this.$refs.paragraph);
            }
        },
        props:  {
            add: {
                type: String,
                default: ''
            }
        },
        mounted : function () {
            if(this.add) this.putLoremText();
        }
    };
</script>

<style lang="sass">

</style>
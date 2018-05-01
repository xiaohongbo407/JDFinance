<template lang="html">
    <div :class="{btnClass,cname}">
        <p/>
    </div>
</template>

<script>
export default {
    props: {
        cname: {
            type: String,
            default: "",
        },
    },
    data() {
        return {
            btnClass: "btn",
        }
    },
}
</script>

<style lang="scss">
@import "../../css/element.scss"
.btn{

}
</style>

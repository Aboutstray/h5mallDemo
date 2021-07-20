<template>
    <div class="tab-bar-item">
        <div v-if="!isActive"><slot name="tabber-icon"></slot></div>
        <div v-else><slot name="tabber-icon-active"></slot></div>
        <slot name="tabber-text"></slot>
    </div>
</template>

<script>
export default {
    data(){
        return{
            isActive:true
        }
    },
    methods:{

    }
}
</script>

<style scoped>
.tab-bar-item{
    flex: 1;
    text-align: center;
    height: 59px;
    color: #adadad;
}
.tab-bar-item img{
    width: 24px;
    height: 24px;
    margin-top: 10px;
    vertical-align: middle;
}
</style>
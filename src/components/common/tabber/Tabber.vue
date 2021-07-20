<template>
<div>
    <div id="tab-bar">
        <slot></slot>
    </div>
</div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
#tab-bar{
    display: flex;
    border-top: 1px solid #ccc;

    position: fixed;
    left: 0;
    right: 0;
    bottom: 0;
}
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
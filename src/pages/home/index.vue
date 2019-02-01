<template>
<div id="home" class="page">

    <header class="header">
        
    </header>

    <homeNav/>
    
    <scroller :top="74" :bottom="49">s
        
    </scroller>

</div>
</template>

<script>
import homeNav from '../../components/homeCom/homeNav'
export default {
    components: {
        homeNav
    }
}
</script>

<style lang="scss" scoped>
#home{
    background: palegoldenrod;
    .header{
        width: 100%;
        height: 44px;
        position: absolute;
        top: 0;
        left: 0;
        display: flex;
        padding: 12px 8px;
        box-sizing: border-box;
        // background: #eee;
        img{
            height: 100%;
        }
        p{
            line-height: 20px;
            font-size: 12px;
            padding: 0 10px;
            background: #ededed;
            color: #666;
            border-radius: 4px;
            margin: 0 8px;
            flex: 1;
        }
        span{
            color: #b4282d;
            border: 1px solid #b4282d;
            border-radius: 2px;
            font-size: 12px;
            padding: 6px;
            line-height: 8px;
        }
    }
}
</style>

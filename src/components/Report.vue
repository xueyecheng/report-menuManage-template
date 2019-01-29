<template>
    <div class="Report">
         <h2>Hello Xue nan shen！</h2>
         <el-button type="primary" plain>{{buttonFont}}</el-button>
    </div>
</template>

<script>
import {getUniqueId} from '../utils/utils'
export default {
    name:'Report',
    data(){
        return {
            buttonFont:''
        }
    },
    mounted(){
        this.buttonFont=getUniqueId();
    }
}
</script>

<style lang="scss" scoped>

</style>

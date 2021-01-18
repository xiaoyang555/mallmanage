<template>
<div id="vue"> 
<el-form label-position="top" label-width="80px" :model="formdata">
  <el-form-item label="用户名">
    <el-input v-model="formdata.username"></el-input>
  </el-form-item>
  <el-form-item label="密码">
    <el-input v-model="formdata.password"></el-input>
  </el-form-item>
</el-form>

</div>

</template>

<script>
export default {
    data(){
        return{
        value1: 0,
        value2: 50,
        value3: 36,
        value4: 48,
        value5: 42
            }
        },
    methods: {
      formatTooltip(val) {
        return val / 100;
      }
    }

    }
</script>


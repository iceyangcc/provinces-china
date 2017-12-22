# ProvincesOfChina
中国省市区最新数据2份, chinese provinces; 

你可以根据您的需要改造一下js代码中 的 key(你可以使用nodejs/python等脚本语言处理这个文件)
其中一个是 针对 vue element ui 级联选择器设计的省市区数据,
该数据来自国家统计局,

### element ui 使用数据示例
```
导入 
import cityOptions from '@/js/city_data2017_element.js'
 <el-cascader
    :options="cityOptions"
    :value="city"
    @change="changeProvince"
    change-on-select
  >
  </el-cascader>
  
  data中绑定数据
  cityOptions: cityOptions,
```

# LegalHolidayJson
法定节假日json文件，作为个人/工作需求使用

### 数据来源：
> http://search.www.gov.cn/search/fw/index.do?q=%E8%8A%82%E5%81%87%E6%97%A5
 

### 使用方式：
1. get请求：https://raw.githubusercontent.com/yuxpro/LegalHolidayJson/main/yyyy.json 其中yyyy指年份，如：2021
> 返回数据格式为：

{
  "data":{
  "holiday":[
    "0101",
    "0102",
    "0103",
    "0211",
    "0212",
    "0213",
    "0214",
    "0215",
    "0216",
    "0217",
    "0403",
    "0404",
    "0405",
    "0501",
    "0502",
    "0503",
    "0504",
    "0505",
    "0612",
    "0613",
    "0614",
    "0919",
    "0920",
    "0921",
    "1001",
    "1002",
    "1003",
    "1004",
    "1005",
    "1006",
    "1007"],
    "workingday":[
    "0207",
    "0220",
    "0425",
    "0508",
    "0918",
    "0926",
    "1009"] 
  },
  "code":0,
  "msg":"查询成功"
}

2. data内：
"holiday"表示法定节假日，后面接的是日期格式为MMDD的法定节假日列表。
"workingday"表示法定补休日，后面接的是日期格式为MMDD的法定补休日列表。

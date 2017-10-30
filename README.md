##基本信息

接口名称: 药品目录化学药中成药列表    

接口地址: http://192.168.20.225:8080/hpms/api/mcdProduct30/listHisProduct

请求方法: POST                      

数据类型: X-WWW-FORM-URLENCODED

响应类型: JSON

接口状态: 有效

##接口描述
 
 药品目录化学药中成药列表查询 $path$/mcdProduct30/hisProductInfo ——> $path$/mcdProduct30/listHisProduct
 
##请求参数
 
 | 参数名称 | 是否必须 | 类型 | 默认值 | 描述 |
 | ------ | ------ | ------- |  ------- |  ------- |
 | drugId |  false |  string | 0000027103 | 药品ID |

##响应
 
 | 参数名称 | 是否必须 | 数据类型 | 描述 | 
 | ------ | ------ | ------- |  ------- | 
 | message | true | string | | 
 | content | true | array[object] | |
 | id | true | string | ID主键 |
 
##例子
 
```javascript
  var ihubo = {
    nickName  : "草依山",
    site : "http://jser.me"
  }
```

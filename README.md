## Ecosystem
接口名称: 药品目录化学药中成药列表    接口地址: http://192.168.20.225:8080/hpms/api/mcdProduct30/listHisProduct
请求方法: POST                      数据类型: X-WWW-FORM-URLENCODED响应类型: JSON接口状态: 有效

####请求参数
==
| 参数名称 | 是否必须 | 类型 | 默认值 | 描述 |
| ------ | ------ | ------- |  ------- |  ------- | 
| drugId |  false |  string | 0000027103 | 药品ID |

 响应数据
 ==
 | 参数名称 | 是否必须 | 数据类型 | 描述 | 
 | ------ | ------ | ------- |  ------- | 
 | message | true | string | | 
 | content | true | array[object] | |
 | id | true | string | ID主键 |
 
 例子
 ==

```javascript
   "message": "操作成功", 
    "content": [
        {
            "id": "RPMCD000000000000MED0000128249", 
            "code": "Z138002-110101-A1H5-01-13-0002978-01", 
            "status": 1, 
            "version": null, 
            "commonName": "熊胆降热", 
            "flmc": "", 
            "ddd": null, 
            "kjyw": 0, 
            "specF": "0.36g", 
            "smlNameF": "胶囊剂", 
            "nameCnF": "比拜克胶囊", 
            "saltName": null, 
            "dddUnit": null, 
            "facNameF": "四川金辉药业有限公司", 
            "attrNameF": "无", 
            "specUnit1Val": null, 
            "specUnit1": null, 
            "code197": "Z138002-110101-A1H5-01-0002978", 
            "specUnit2Val": 0.36, 
            "specUnit2": "G", 
            "jbyw": 0, 
            "minUseUnit": "粒", 
            "packUnit": "盒", 
            "convert": 14, 
            "ybProvince": "", 
            "yblb": "", 
            "ybbh": "", 
            "jkyw": 0, 
            "yyyy": 0, 
            "pregnancyLevel": "", 
            "jmdf": "", 
            "py": "XDJR", 
            "pack": 1, 
            "adminRoute": "口服", 
            "adminFrequency": 3, 
            "createDate": 1496841547000, 
            "updateDate": 1497001519000, 
            "activePrin": null, 
            "activeUnit": null, 
            "brandName": null, 
            "convertF": "14粒/盒", 
            "delFlag": 0, 
            "drugType": "中成药", 
            "facAbbrF": "四川金辉", 
            "fivePen": "CEBR", 
            "nameEnF": null, 
            "ownerCodeF": "86902168000048", 
            "ppi": 0, 
            "prodPzwhF": "国药准字Z20026560", 
            "prodTradeF": null, 
            "prodZczhF": null, 
            "quantyUnit": "盒", 
            "rbflName": "", 
            "smsId": "146156607159499", 
            "warpNameF": "空", 
            "yjId": null, 
            "ylflName": "", 
            "ypid": "304030170102"
        }
    ], 
    "total": 195174, 
    "flag": "S"
```

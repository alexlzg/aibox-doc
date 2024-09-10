## Pilot登录
`POST /map/api/v1/login`

<h3 id="创建元素-parameters">Parameters</h3>

|Name|Type|Required|Description|
|---|---|---|---|
|username|string|true|用户名|
|password|string|true|密码|
|flag|number|true|标识,flag=2 代表飞机|



<h3 id="创建元素-responses">Responses</h3>
 
|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|OK|[map.SwagUUIDResp](#schemamap.swaguuidresp)|

> Example responses
```json
{
	"code":0
   	"data":{
    	"id":"94c51c50-f111-45e8-ac8c-4f96c93ced44"
    },
    "message": "success"
}

```

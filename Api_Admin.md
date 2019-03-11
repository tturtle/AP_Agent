# 支付中心 Admin API

## 规范说明：

- 编码：`UTF-8`
- Content-Type： `application/json`
  
- 回传格式：

```
|参数|参数名称|说明|举例|
|:-------------:|:------:|:--------:|:-------:|
| `isSuccess` | 是否成功 | 请求是否成功 | true; false |
| `message` | 讯息 | 通常是回覆错误讯息 | 帐号或密码错误 |
| `code` | 代码 | 响应代码, AP-0000 表示成功 | AP-0000 |
| `result` | 响应资讯 | 如果有回传资料, 皆放于此内 | { "count":"1" } |

范例：
{
 "isSuccess": true,
 "message": "成功",
 "code": "AP-0000",
 "result": { "count":"1" },
}

```

---
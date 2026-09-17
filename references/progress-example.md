# 进度记录示例（全部虚构）

notes数组中的一条示例：

```json
{"note_id":"demo-001","title":"海湾城建筑散步","source_locator":"用户本地收藏夹中的标题与ID","status":"read","reason":"","body_read":true,"media":"unread","summary":"作者建议参观老街与市立展馆；价格尚待官方核验"}
```

status取pending/read/blocked/excluded；media取unread/partial/read/not_applicable。read仅代表正文读取成功，body_read须为true；其他状态不可冒称已读。source_locator不保存临时签名参数；同一note_id只保留一条当前状态。

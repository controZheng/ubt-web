
事件格式
----

### 合并事件格式

所有事件统一到这个格式. 合并后, 部分字段共用. 事件自身的数据以数组形式存放:

```bash
data: [
  EVENT_FORMAT
]
```

例子:

```json
{
  "data": [
    {
      "resolution": "1096x761",
      "location": "https://h5.ele.me/sales/",
      "pvhash": "xxxx1x466jfk59x3htv1kqjzhlmgxxxx",
      "referrer": "https://h5.ele.me/discovery/",
      "ssid": "xxxxy7bnvq80e3pnot31vg4gr60txxxx_2016-12-26",
      "type": "PV",
      "timestamp": "ix6asfi4"
    },
    {
      "fetchStart": 45,
      "connectEnd": 382,
      "connectStart": 114,
      "domComplete": 1543,
      "domContentLoadedEventEnd": 1041,
      "domContentLoadedEventStart": 953,
      "domInteractive": 953,
      "domLoading": 479,
      "domainLookupEnd": 114,
      "domainLookupStart": 76,
      "loadEventEnd": 1574,
      "loadEventStart": 1543,
      "requestStart": 382,
      "responseEnd": 478,
      "responseStart": 477,
      "ssid": "xxxxy7bnvq80e3pnot31vg4gr60txxxx_2016-12-26",
      "type": "TIMING",
      "timestamp": "ix6xi6az"
    },
    {
      "type": "PARAMS",
      "user_id": 885996,
      "geohash": "",
      "ssid": "xxxxy7bnvq80e3pnot31vg4gr60txxxx_2016-12-26",
      "timestamp": "ix6xi58y"
    },
    {
      "id": 1644,
      "type": "EVENT",
      "params": {
        "from": 3,
        "title": "天天特价",
        "restaurant_id": "328591",
        "dish_id": "12222",
        "index": 0
      },
      "ssid": "xxxxy7bnvq80e3pnot31vg4gr60txxxx_2016-12-26",
      "timestamp": "igw6zpqh"
    }
  ]
}
```
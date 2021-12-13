### 바로 쏘기
```bash
echo $(($(date +%s%N))) 
curl -v -H "Content-Type: application/json" -XPOST -s "http://localhost:3100/loki/api/v1/push" --data-raw  '{"streams": [{ "stream": { "foo": "bar2" }, "values": [ [ "1639226953837326439", "fizzbuzz!!!" ] ] }]}'
```

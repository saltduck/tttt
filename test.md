### Penta 协议

#### penta_gasPrice
获取当前gasPrice
* Parameters    
没有
* Returns    
`QUANTITY` - 当前Gas价格的整数。
* Example

```json
//Request
'{"jsonrpc":"2.0","method":"penta_gasPrice","params":[],"id":73}'

//Result
{
  "id":73,
  "jsonrpc": "2.0",
  "result": "0x430e23400" // 18000000000
}
```

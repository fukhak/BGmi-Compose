#bgmi-compose

使用docker compose的BGmi一鍵包

使用鏡像:

bgmi-dockerlized, nginx, transmission

## 特色

 - 開箱即用
 - 前端，後端和BT端獨立分開，有需要可以自行更換

## 安裝

```
docker compose up -d
```

you need exec to cli use docker exec -it to config more setting and get bangumi list

all env name can found on bgmi source code

相關資料可以參考[BGmi主git](https://github.com/BGmi/BGmi/blob/master/README.cn.md#使用)

## 注意事項

 - BT端會在下載完成後繼續做種，需要自行暫停或刪除
 - 訂閲後默認只會下載之後的集數，假如整套下載請在filter上調整episode參數

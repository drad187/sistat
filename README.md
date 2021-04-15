### cURL commands

Following commands are used to fetch data from [SiStat](https://pxweb.stat.si/SiStat/)

curl -X POST -H "Content-Type: application/json" -d @obcine_data.json "https://pxweb.stat.si:443/SiStatData/api/v1/sl/Data/05C4004S.px" -o prebivalstvo_obcine.json

curl -X POST -H "Content-Type: application/json" -d @regije_data.json "https://pxweb.stat.si:443/SiStatData/api/v1/sl/Data/05C2002S.px" -o prebivalstvo_regije.json
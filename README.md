curl "http://10.10.5.37:8083/api/promocode/validate" ^
  -H "Accept-Language: en-US,en;q=0.9" ^
  -H "Connection: keep-alive" ^
  -H "Cookie: XSRF-TOKEN=ef11d2fb-0f62-4991-b8d4-e4ba2cc3ecc9" ^
  -H "Origin: http://10.10.5.37:8083" ^
  -H "Referer: http://10.10.5.37:8083/financing-details" ^
  -H "User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/112.0.0.0 Safari/537.36" ^
  -H "accept: application/json" ^
  -H "content-type: application/json" ^
  -H "x-xsrf-token: ef11d2fb-0f62-4991-b8d4-e4ba2cc3ecc9" ^
  --data-raw "^{^\^"promo_code^\^":^\^"GreatFino^\^",^\^"agent_code^\^":^\^"^\^",^\^"tenure^\^":^\^"36^\^",^\^"loan_amount^\^":10000,^\^"min_gross_income^\^":^\^"1500^\^"^}" ^
  --compressed ^
  --insecure
  
  02PFON20000000000341

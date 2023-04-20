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
  
  
  curl "http://10.10.5.37:8083/api/case/02PFON20000000000342/pf/personal_details" ^
  -X "PUT" ^
  -H "Accept-Language: en-US,en;q=0.9" ^
  -H "Connection: keep-alive" ^
  -H "Cookie: XSRF-TOKEN=7c567447-6364-4ab9-96c8-35fed9008478" ^
  -H "Origin: http://10.10.5.37:8083" ^
  -H "Referer: http://10.10.5.37:8083/personal-detail" ^
  -H "User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/112.0.0.0 Safari/537.36" ^
  -H "accept: application/json" ^
  -H "content-type: application/json" ^
  -H "dropoff_steps: Step 7" ^
  -H "x-auth-token: Bearer eyJhbGciOiJSUzI1NiJ9.eyJjYXNlaWQiOlsyMDAwMDAwMDAwMDM0Ml0sImFwcGxpY2FudGlkIjpbOTQxLDk0Ml0sInN1YiI6IkF1dGhvcml6YXRpb24iLCJpc3MiOiJDcmVkaXRTdGFjayIsImV4cCI6MTY4MjA0MDcyNCwiaWF0IjoxNjgxOTU0MzI0LCJqdGkiOiJhOTJhMTliNC1lZjI2LTQ1NjgtYWY1ZS02NGRkYmFkOTI4YTAifQ.UhbAKJn5goQAgQ6FbCxQmLPaIw1KVChlXSkzuvf93r8Z-FlVZyNYSprSlFqGPIpi9OHce6H9m9zJBfnyOQ3P6uhSnBqxQkPQvOJcgHQmwFOqJl-HM9gGue555JRj9KAFkJLbFAB5WpywtdrfStqWsBfiCfiBs9RGiMofCdREARmSO8ij_5tlhkwRBgCGUL8lwZvvVVNY-SM7zUHpohVNWQgW97gnLhE1JQSGU89kLGWsZj1tMKkdVu2KattcqnU9zkr1QikH00vEDihKq_G3X0BteGSay4hZKhX-8kmFbZSH5AwkItBXLtujbBrzeo4W6DSxXjQiYU3K-4ICOnbtKQ" ^
  -H "x-xsrf-token: 7c567447-6364-4ab9-96c8-35fed9008478" ^
  --data-raw "^{^\^"applicant^\^":^{^\^"personal_details^\^":^{^\^"title^\^":^\^"2^\^",^\^"full_name^\^":^\^"NUR AFINI BINTI SHAMSHUDDIN^\^",^\^"date_of_birth^\^":^\^"1996-03-20^\^",^\^"email^\^":^\^"afini.work.test^@gmail.com^\^",^\^"existing_aeon_product^\^":^\^"0^\^",^\^"residency_status^\^":^\^"B^\^",^\^"gender^\^":^\^"F^\^",^\^"race^\^":^\^"001^\^",^\^"other_race^\^":^\^"^\^",^\^"marital_status^\^":^\^"1^\^",^\^"no_of_dependants^\^":^\^"1^\^",^\^"mobile_phone_number^\^":^\^"(+60)1110029792^\^",^\^"id_type^\^":^\^"1^\^",^\^"id_number^\^":^\^"960320086594^\^",^\^"other_ic_type^\^":^\^"^\^",^\^"other_ic_field^\^":^\^"^\^",^\^"nationality^\^":^\^"MY^\^",^\^"address_line_1^\^":^\^"damnsara^\^",^\^"address_line_2^\^":^\^"^\^",^\^"address_line_3^\^":^\^"^\^",^\^"postcode^\^":^\^"50100^\^",^\^"city^\^":^\^"Kuala Lumpur^\^",^\^"state^\^":^\^"01^\^",^\^"residential_ownership^\^":^\^"R^\^",^\^"years_of_stay^\^":^\^"01.02^\^",^\^"permanent_resident^\^":^\^"1^\^",^\^"permanent_address_1^\^":^\^"damnsara^\^",^\^"permanent_address_3^\^":^\^"^\^",^\^"permanent_postal_code^\^":^\^"50100^\^",^\^"permanent_state^\^":^\^"01^\^",^\^"permanent_city^\^":^\^"Kuala Lumpur^\^",^\^"relationship^\^":^\^"5^\^",^\^"ocr_verified^\^":^[^{^\^"front_id^\^":0,^\^"back_id^\^":0,^\^"passport_id^\^":0^}^]^}^}^}" ^
  --compressed ^
  --insecure
  
  NEW
  
  curl "http://10.10.5.37:8083/api/param/data-list?lang_code=EN" ^
  -H "Accept-Language: en-US,en;q=0.9" ^
  -H "Connection: keep-alive" ^
  -H "Cookie: XSRF-TOKEN=7c567447-6364-4ab9-96c8-35fed9008478" ^
  -H "Referer: http://10.10.5.37:8083/loan-detail" ^
  -H "User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/112.0.0.0 Safari/537.36" ^
  -H "accept: application/json" ^
  -H "content-type: application/json" ^
  -H "x-xsrf-token: 7c567447-6364-4ab9-96c8-35fed9008478" ^
  --compressed ^
  --insecure
  
  NEW
  
  curl "http://10.10.5.37:8083/api/screening/02PFON20000000000369/external" ^
  -X "POST" ^
  -H "Accept-Language: en-US,en;q=0.9" ^
  -H "Connection: keep-alive" ^
  -H "Content-Length: 0" ^
  -H "Cookie: XSRF-TOKEN=7c567447-6364-4ab9-96c8-35fed9008478" ^
  -H "Origin: http://10.10.5.37:8083" ^
  -H "Referer: http://10.10.5.37:8083/otp" ^
  -H "User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/112.0.0.0 Safari/537.36" ^
  -H "accept: application/json" ^
  -H "content-type: application/json" ^
  -H "x-xsrf-token: 7c567447-6364-4ab9-96c8-35fed9008478" ^
  --compressed

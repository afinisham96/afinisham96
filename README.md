
02PFON470DE4DFDDBD15-doc error

02PFON470EB66BB0578E

http://10.10.5.37:8083/additional-document-upload?dff8f768e6509e03d7d21327cd42d755&02PFON470EB66BB0578E

http://10.10.5.37:8083/additional-document-upload?be642ddd3215a17539b57f4c43de1780&02PFON470DE4DFDDBD15

http://10.10.5.37:8083/additional-document-upload?e070427d525ad73adc3fc42e9463b1a7&02PFON470DFC283620AF

![image](https://github.com/afinisham96/afinisham96/assets/131110842/750b36eb-8f23-480e-9d13-28452ccf1894)

![image](https://github.com/afinisham96/afinisham96/assets/131110842/8c75e624-f4cc-4e59-95ad-04341c0cc54b)

http://10.10.5.37:8083/additional-document-upload?e070427d525ad73adc3fc42e9463b1a7&02PFON470DFC283620AF

{errorCode: "400", errorMessage: "{"code":"URL_TKN_400","status":"Invalid Token"}"}
errorCode
: 
"400"
errorMessage
: 
"{\"code\":\"URL_TKN_400\",\"status\":\"Invalid Token\"}"


curl "http://10.10.5.37:8083/api/utils/validate-url" ^
  -H "Accept-Language: en-US,en;q=0.9" ^
  -H "Connection: keep-alive" ^
  -H "Cookie: XSRF-TOKEN=eaaa852b-3ece-46e8-afe7-633a43b17b64" ^
  -H "Origin: http://10.10.5.37:8083" ^
  -H "Referer: http://10.10.5.37:8083/additional-document-upload?e070427d525ad73adc3fc42e9463b1a7&02PFON470DFC283620AF" ^
  -H "User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/113.0.0.0 Safari/537.36" ^
  -H "accept: application/json" ^
  -H "content-type: application/json" ^
  -H "x-xsrf-token: eaaa852b-3ece-46e8-afe7-633a43b17b64" ^
  --data-raw "^{^\^"caseid^\^":^\^"02PFON470DFC283620AF^\^",^\^"token^\^":^\^"e070427d525ad73adc3fc42e9463b1a7^\^"^}" ^
  --compressed ^
  --insecure


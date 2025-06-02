Test Case: GTL_TC_01 – Valid Request for GetTeacherList

Endpoint:  
POST `/GetTeacherList`

Request Body:
```json
{
  "key": "JULKtdueaWAXsvkq1Ep2",
  "topCount": 2,
  "needImage": false
}

Expected Result:
Status code: 200 OK
IsSuccess: true
Teachers: array with up to 2 teacher objects

Actual Result:
Status: 200 OK
IsSuccess: true
Teachers received

Screenshot: screenshots/GTL_TC_01_response.png

Test Status: Pass

```javascript
exports.handler = async (event, context, callback) => {
  /* ********************************************
   * event === contains the incoming data
   * context === details about the function
   * (time it started, timeout etc)
   * callback(arg1, arg2)
   * arg1 : error
   * arg2 : data we rwant to send back
   **********************************************/
  const response = {
    statusCode: 200,
    body: JSON.stringify("Hello from Lambda!"),
  };
  return response;
};
```

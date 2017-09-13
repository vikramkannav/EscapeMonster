# Student

## Student

This API is used for student to enter his/her name & game code those he/she
like to play the game

```shell
curl "http://baseurl/student"
```


> The above command returns JSON structured like this:

```json
```


### HTTP Request

 `POST http://baseurl/student`

### Parameters

Parameter |Type | Required | Description
---------|------| ------- | -----------
name   | string  | true   | Name of the contact person
code   |  integer | true  | Game code student like to play

<aside class="success">status:200 OK </aside>
<aside class="warning">status:422 Unprocessable entry.</aside>
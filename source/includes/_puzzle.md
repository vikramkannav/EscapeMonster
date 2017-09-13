# Puzzle

This API is used for create the puzzle for the game. 

```shell
curl "http://baseurl/game/:id/puzzle"
```


> The above command returns JSON structured like this:

```json
```


### HTTP Request

 `GET http://baseurl/game/:id/puzzle`

### Parameters

Parameter |Type | Required | Description
---------|------| ------- | -----------
 name   | string | true   | Name of the puzzle 
 description|string | true | Description of the puzzle
 hint    |string  | true   | hint of the puzzle
 

<aside class="success">status:200 OK </aside>
<aside class="warning">status:422 Unprocessable entry.</aside>
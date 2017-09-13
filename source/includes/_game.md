# Game

## Create Game

This API is used for create the Game with some information. 

```shell
curl "http://baseurl/game"
```


> The above command returns JSON structured like this:

```json
```


### HTTP Request

 `POST http://baseurl/game`

### Parameters

Parameter |Type | Required | Description
---------|------| ------- | -----------
name   | string  | true   | Name of the game
code   | integer | true    | Code of the game
description | string | true | Description of the game
time   | time | true    | Time of the game
subject | string | true   | Subject of the game
level   | integer | true  | Level of the game

<aside class="success">status:200 OK </aside>
<aside class="warning">status:422 Unprocessable entry.</aside>

## Game List

This API is used for list of the game. 

```shell
curl "http://baseurl/game"
```


> The above command returns JSON structured like this:

```json
```


### HTTP Request

 `GET http://baseurl/games`

### Parameters

Parameter |Type | Required | Description
---------|------| ------- | -----------


<aside class="success">status:200 OK </aside>






## Game details

This API is used for game detail page. 

```shell
curl "http://baseurl/games/:id"
```


> The above command returns JSON structured like this:

```json
```


### HTTP Request

 `GET http://baseurl/games/:id`

### Parameters

Parameter |Type | Required | Description
---------|------| ------- | -----------
        |       |          |
        |       |           |       
     
<aside class="success">status:200 OK </aside>



## Game Members

This API is used for game detail page. 

```shell
curl "http://baseurl/games/:id/members"
```


> The above command returns JSON structured like this:

```json
```


### HTTP Request

 `GET http://baseurl/games/:id/members`

### Parameters

Parameter |Type | Required | Description
---------|------| ------- | -----------
        |       |          |
        |       |           |       


<aside class="success">status:200 OK </aside>
<aside class="warning">status:422 Unprocessable entry.</aside>


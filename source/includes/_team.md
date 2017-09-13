# Team

## Assign team

This API is used for the create the team by he/she.With some information

```shell
curl "http://baseurl/team"
```


> The above command returns JSON structured like this:

```json
```


### HTTP Request

 `POST http://baseurl/team`

### Parameters

Parameter |Type | Required | Description
---------|------| ------- | -----------
name   | string  | true   | Name of the team
student_name   | string | true  | Team members student names

<aside class="success">status:200 OK </aside>
<aside class="warning">status:422 Unprocessable entry.</aside>
# Contact us

This API is used for the contact us form. With this API user (like school person)can contact with 
Monster escape team with some information (name,school name, email,comments).  


```shell
curl "http://baseurl/contact"
```


> The above command returns JSON structured like this:

```json
```


### HTTP Request

 `GET http://baseurl/contact`

### Parameters

Parameter |Type | Required | Description
---------|------| ------- | -----------
name   | string  | true   | Name of the contact person
school | string | true    | School name of the contact person
email  | string | true    | Email of the contact person
comment | string | true   | Comment by the contact person

<aside class="success">status:200 OK </aside>
<aside class="warning">status:422 Unprocessable entry.</aside>
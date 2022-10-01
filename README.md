# REST-API-basics
Working With API's


## HTTP Verb	Typical Action (CRUD)
* POST	Create
* GET	Read
* PUT	Update
* PATCH	Update
* DELETE	Delete


![image](https://user-images.githubusercontent.com/96833570/193411299-adc015e3-5ba8-400b-a57e-6e458f472893.png)


## Displaying the response headers

``curl --include https://api.github.com/``

## REST API headers

![image](https://user-images.githubusercontent.com/96833570/193411776-8ec8c0bb-4ce4-4bf7-b95f-368c2a4dc3f1.png)

![image](https://user-images.githubusercontent.com/96833570/193411807-c3ca9594-7919-43a7-8a25-4183541ad45f.png)

Here is an example below:

![image](https://user-images.githubusercontent.com/96833570/193412007-8019b650-2e10-4119-bc9b-9b9f95bc3c9c.png)



## What are JSON objects?

In JSON, the object is an unordered set of name-value pairs. An object begins with { (left brace) and ends with } (right brace). Wrap the strings in JSON with " (double quotes).

```
{
  "current_user_url": "https://api.github.com/user",
  "current_user_authorizations_html_url": "https://github.com/settings/connections/applications{/client_id}"
}
```

## Working with Github API requests in POSTMAN

![image](https://user-images.githubusercontent.com/96833570/193412550-9e2b7454-9952-4081-ac22-ff0180364c29.png)
Below is the code snippet generated in python:

![image](https://user-images.githubusercontent.com/96833570/193412884-d1a0826f-4d97-428b-b69a-dd178f694544.png)


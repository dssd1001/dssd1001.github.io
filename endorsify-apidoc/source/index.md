---
title: Endorsify API Reference

language_tabs:
- bash
- javascript

includes:

search: true

toc_footers:
- Questions? contact david@endorsify.co
---
<!-- START_INFO -->
# Info

Welcome to the API reference for Endorsify Web App.

[Last updated: 5/17/2018]

Developers, use this as a look-up tool to make/write tests, search a specific HTTP request to refresh your memory, or however you want to use this for. This will probably come in handy.

Designers, you may find this useful as you design new pages.

FYI, organization and descriptions for a lot of methods are nonexistent—this is a work in progress as I sift through the codebase and slowly organize things. And to help stop further disorder moving forward, I will soon be applying a strict code-style-guideline for everyone to follow.

-David
<!-- END_INFO -->

#Campaign
<!-- START_39852ea172f6971c906de94aebf15bdd -->
## test

> Example request:

```bash
curl "https://endorsify.co/test" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/test",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET test`

`HEAD test`


<!-- END_39852ea172f6971c906de94aebf15bdd -->
<!-- START_b818908aeddc90383c46a6ef131cec05 -->
## brand/campaign

> Example request:

```bash
curl "https://endorsify.co/brand/campaign" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET brand/campaign`

`HEAD brand/campaign`


<!-- END_b818908aeddc90383c46a6ef131cec05 -->
<!-- START_4b9bf05f735581110cab00de2aed531f -->
## brand/campaign/create

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/create" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/create",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET brand/campaign/create`

`HEAD brand/campaign/create`


<!-- END_4b9bf05f735581110cab00de2aed531f -->
<!-- START_eec468eba6de85e55ad8462245b7446a -->
## brand/campaign/edit/{user_id}

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/edit/{user_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/edit/{user_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET brand/campaign/edit/{user_id}`

`HEAD brand/campaign/edit/{user_id}`


<!-- END_eec468eba6de85e55ad8462245b7446a -->
<!-- START_a0c343a1a056d5902adb7a444f001839 -->
## brand/campaign/view/{id}

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/view/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/view/{id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET brand/campaign/view/{id}`

`HEAD brand/campaign/view/{id}`


<!-- END_a0c343a1a056d5902adb7a444f001839 -->
<!-- START_40f6120665f34442dbc805098db64863 -->
## saveStrategy

> Example request:

```bash
curl "https://endorsify.co/saveStrategy" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/saveStrategy",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST saveStrategy`


<!-- END_40f6120665f34442dbc805098db64863 -->
<!-- START_09b2bb4b1b2453945030801ff4b564af -->
## saveStrategy/{id}

> Example request:

```bash
curl "https://endorsify.co/saveStrategy/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/saveStrategy/{id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET saveStrategy/{id}`

`HEAD saveStrategy/{id}`


<!-- END_09b2bb4b1b2453945030801ff4b564af -->
<!-- START_b5dde93fa26f4ac56a6074a1aeb31c00 -->
## brand/campaign/suggested/{id}

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/suggested/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/suggested/{id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET brand/campaign/suggested/{id}`

`HEAD brand/campaign/suggested/{id}`


<!-- END_b5dde93fa26f4ac56a6074a1aeb31c00 -->
<!-- START_9d59a6f1a6fba23bfeb939bfd147d1c2 -->
## brand/campaign/negotiate/{id}

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/negotiate/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/negotiate/{id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET brand/campaign/negotiate/{id}`

`HEAD brand/campaign/negotiate/{id}`


<!-- END_9d59a6f1a6fba23bfeb939bfd147d1c2 -->
<!-- START_9057573f5a0beabf593704c02d6632f9 -->
## brand/campaign/in-progress/{id}

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/in-progress/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/in-progress/{id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET brand/campaign/in-progress/{id}`

`HEAD brand/campaign/in-progress/{id}`


<!-- END_9057573f5a0beabf593704c02d6632f9 -->
<!-- START_a935a65835bf404b3da9ab33c25607ec -->
## brand/campaign/complete/{id}

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/complete/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/complete/{id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET brand/campaign/complete/{id}`

`HEAD brand/campaign/complete/{id}`


<!-- END_a935a65835bf404b3da9ab33c25607ec -->
<!-- START_8c1b78f2b73a1b4882578e0f4de5eb03 -->
## brand/campaign/store

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/store" \
-H "Accept: application/json" \
    -d "name"="eos" \
    -d "promote"="eos" \
    -d "audience"="eos" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/store",
    "method": "POST",
    "data": {
        "name": "eos",
        "promote": "eos",
        "audience": "eos"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST brand/campaign/store`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    name | string |  required  | Maximum: `40`
    promote | string |  required  | 
    audience | string |  required  | 

<!-- END_8c1b78f2b73a1b4882578e0f4de5eb03 -->
<!-- START_d25ceecd8d8490ef1b64b5c7eb273348 -->
## brand/campaign/update/{id}

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/update/{id}" \
-H "Accept: application/json" \
    -d "name"="dignissimos" \
    -d "promote"="dignissimos" \
    -d "audience"="dignissimos" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/update/{id}",
    "method": "POST",
    "data": {
        "name": "dignissimos",
        "promote": "dignissimos",
        "audience": "dignissimos"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST brand/campaign/update/{id}`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    name | string |  required  | Maximum: `40`
    promote | string |  required  | 
    audience | string |  required  | 

<!-- END_d25ceecd8d8490ef1b64b5c7eb273348 -->
<!-- START_9b4b9a0f86e8470bfddc0e709c2b8553 -->
## brand/campaign/archive/{id}

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/archive/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/archive/{id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET brand/campaign/archive/{id}`

`HEAD brand/campaign/archive/{id}`


<!-- END_9b4b9a0f86e8470bfddc0e709c2b8553 -->
<!-- START_998c57710f8794eb8c89c51af83a0729 -->
## upload-document/{path}

> Example request:

```bash
curl "https://endorsify.co/upload-document/{path}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/upload-document/{path}",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST upload-document/{path}`


<!-- END_998c57710f8794eb8c89c51af83a0729 -->
<!-- START_69e1fce10654027add4401ccf94baea4 -->
## brand/campaign/archive/{id}

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/archive/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/archive/{id}",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST brand/campaign/archive/{id}`


<!-- END_69e1fce10654027add4401ccf94baea4 -->
<!-- START_9d6d31e45c9cb2217c6f80a445d42410 -->
## brand/campaign/search

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/search" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/search",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET brand/campaign/search`

`HEAD brand/campaign/search`


<!-- END_9d6d31e45c9cb2217c6f80a445d42410 -->
<!-- START_972584acc7107278556a7ca4f7ed4cf5 -->
## brand/campaign/delete/{id}

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/delete/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/delete/{id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET brand/campaign/delete/{id}`

`HEAD brand/campaign/delete/{id}`


<!-- END_972584acc7107278556a7ca4f7ed4cf5 -->
<!-- START_6e8735dda4e8e8be4cb846a74f465716 -->
## brand/campaign/delete-get/{id}

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/delete-get/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/delete-get/{id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET brand/campaign/delete-get/{id}`

`HEAD brand/campaign/delete-get/{id}`


<!-- END_6e8735dda4e8e8be4cb846a74f465716 -->
<!-- START_f8ba231e9fac79efe43d10c8c44b31d4 -->
## brand/campaign/bookmark/{id}/{cam_id}

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/bookmark/{id}/{cam_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/bookmark/{id}/{cam_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET brand/campaign/bookmark/{id}/{cam_id}`

`HEAD brand/campaign/bookmark/{id}/{cam_id}`


<!-- END_f8ba231e9fac79efe43d10c8c44b31d4 -->
<!-- START_d23ef0dd86919bb98c18d4892357439e -->
## brand/campaign/remove-bookmark/{user_id}/{campaign_id}

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/remove-bookmark/{user_id}/{campaign_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/remove-bookmark/{user_id}/{campaign_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET brand/campaign/remove-bookmark/{user_id}/{campaign_id}`

`HEAD brand/campaign/remove-bookmark/{user_id}/{campaign_id}`


<!-- END_d23ef0dd86919bb98c18d4892357439e -->
<!-- START_cefb0b8be89c30bf217668168349d78b -->
## brand/campaign/changes/negotiate/{user_id}/{campaign_id}

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/changes/negotiate/{user_id}/{campaign_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/changes/negotiate/{user_id}/{campaign_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET brand/campaign/changes/negotiate/{user_id}/{campaign_id}`

`HEAD brand/campaign/changes/negotiate/{user_id}/{campaign_id}`


<!-- END_cefb0b8be89c30bf217668168349d78b -->
<!-- START_181c42caa7c1f9e13a7a7698889ce0b9 -->
## brand/campaign/changes/inprogress

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/changes/inprogress" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/changes/inprogress",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST brand/campaign/changes/inprogress`


<!-- END_181c42caa7c1f9e13a7a7698889ce0b9 -->
<!-- START_478bb9c701d4f00b18cb8d7582b41690 -->
## brand/campaign/changes/complete

> Example request:

```bash
curl "https://endorsify.co/brand/campaign/changes/complete" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brand/campaign/changes/complete",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST brand/campaign/changes/complete`


<!-- END_478bb9c701d4f00b18cb8d7582b41690 -->
#Profile
<!-- START_0f15af4a72ec033d66ef9a320727b267 -->
## /

> Example request:

```bash
curl "https://endorsify.co//" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co//",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET /`

`HEAD /`


<!-- END_0f15af4a72ec033d66ef9a320727b267 -->
<!-- START_7ff67badb50ddc1bdc2258d1889676c3 -->
## profile/info/{user_id}

> Example request:

```bash
curl "https://endorsify.co/profile/info/{user_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/profile/info/{user_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET profile/info/{user_id}`

`HEAD profile/info/{user_id}`


<!-- END_7ff67badb50ddc1bdc2258d1889676c3 -->
<!-- START_ca2681a8822a37f77a296cf70400994d -->
## profile/stats/{user_id}

> Example request:

```bash
curl "https://endorsify.co/profile/stats/{user_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/profile/stats/{user_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET profile/stats/{user_id}`

`HEAD profile/stats/{user_id}`


<!-- END_ca2681a8822a37f77a296cf70400994d -->
<!-- START_b092a45c571ab02256f3e132c159198b -->
## brands/{user_id}

> Example request:

```bash
curl "https://endorsify.co/brands/{user_id}" \
-H "Accept: application/json" \
    -d "bio"="soluta" \
    -d "first_name"="soluta" \
    -d "last_name"="soluta" \
    -d "month"="soluta" \
    -d "day"="soluta" \
    -d "year"="soluta" \
    -d "gender"="soluta" \
    -d "location"="soluta" \
    -d "city"="soluta" \
    -d "phone_number"="soluta" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/brands/{user_id}",
    "method": "POST",
    "data": {
        "bio": "soluta",
        "first_name": "soluta",
        "last_name": "soluta",
        "month": "soluta",
        "day": "soluta",
        "year": "soluta",
        "gender": "soluta",
        "location": "soluta",
        "city": "soluta",
        "phone_number": "soluta"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST brands/{user_id}`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    bio | string |  required  | Minimum: `5`
    first_name | string |  required  | 
    last_name | string |  required  | 
    month | string |  required  | 
    day | string |  required  | 
    year | string |  required  | 
    gender | string |  required  | 
    location | string |  required  | 
    city | string |  required  | 
    phone_number | string |  required  | 

<!-- END_b092a45c571ab02256f3e132c159198b -->
<!-- START_dc3604ad8120d36284fbc748d9a6686d -->
## influencer/change-password

> Example request:

```bash
curl "https://endorsify.co/influencer/change-password" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/influencer/change-password",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET influencer/change-password`

`HEAD influencer/change-password`


<!-- END_dc3604ad8120d36284fbc748d9a6686d -->
<!-- START_5b587f558add951f0a808a0023e97511 -->
## change-password-influencer

> Example request:

```bash
curl "https://endorsify.co/change-password-influencer" \
-H "Accept: application/json" \
    -d "password"="voluptatem" \
    -d "new_password"="voluptatem" \
    -d "confirm_new_password"="voluptatem" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/change-password-influencer",
    "method": "POST",
    "data": {
        "password": "voluptatem",
        "new_password": "voluptatem",
        "confirm_new_password": "voluptatem"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST change-password-influencer`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    password | string |  required  | 
    new_password | string |  required  | Minimum: `6` Maximum: `50` Must match this regular expression: `/^(?=.*[a-z|A-Z])(?=.*[A-Z])(?=.*\d).+$/`
    confirm_new_password | string |  required  | Must be the same as `new_password`

<!-- END_5b587f558add951f0a808a0023e97511 -->
<!-- START_180a2d4c2f3791cf025314756b42bb8c -->
## dash

> Example request:

```bash
curl "https://endorsify.co/dash" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/dash",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET dash`

`HEAD dash`


<!-- END_180a2d4c2f3791cf025314756b42bb8c -->
<!-- START_5aed5e562c38813f6ab2e07152bf4178 -->
## user/profile

> Example request:

```bash
curl "https://endorsify.co/user/profile" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/user/profile",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET user/profile`

`HEAD user/profile`


<!-- END_5aed5e562c38813f6ab2e07152bf4178 -->
<!-- START_8735e430f5d857e3213fb3cc291a3519 -->
## user/change-password

> Example request:

```bash
curl "https://endorsify.co/user/change-password" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/user/change-password",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET user/change-password`

`HEAD user/change-password`


<!-- END_8735e430f5d857e3213fb3cc291a3519 -->
<!-- START_48e619be6bd46a1727bd55f4e738d547 -->
## change-password

> Example request:

```bash
curl "https://endorsify.co/change-password" \
-H "Accept: application/json" \
    -d "password"="voluptas" \
    -d "new_password"="voluptas" \
    -d "confirm_new_password"="voluptas" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/change-password",
    "method": "POST",
    "data": {
        "password": "voluptas",
        "new_password": "voluptas",
        "confirm_new_password": "voluptas"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST change-password`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    password | string |  required  | 
    new_password | string |  required  | Minimum: `6` Maximum: `50` Must match this regular expression: `/^(?=.*[a-z|A-Z])(?=.*[A-Z])(?=.*\d).+$/`
    confirm_new_password | string |  required  | Must be the same as `new_password`

<!-- END_48e619be6bd46a1727bd55f4e738d547 -->
<!-- START_b5c8b25ab517a102db85941ee215bc80 -->
## user/delete-image/{id}

> Example request:

```bash
curl "https://endorsify.co/user/delete-image/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/user/delete-image/{id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET user/delete-image/{id}`

`HEAD user/delete-image/{id}`


<!-- END_b5c8b25ab517a102db85941ee215bc80 -->
<!-- START_920995126b81c90ffae4af2eb5d04f93 -->
## message

> Example request:

```bash
curl "https://endorsify.co/message" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/message",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET message`

`HEAD message`


<!-- END_920995126b81c90ffae4af2eb5d04f93 -->
<!-- START_968e21ae439589a9b87502d9a6f41abe -->
## upload-image/{path}

> Example request:

```bash
curl "https://endorsify.co/upload-image/{path}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/upload-image/{path}",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST upload-image/{path}`


<!-- END_968e21ae439589a9b87502d9a6f41abe -->
<!-- START_1e67857a5e65bfcf733ab0c7ae54ff95 -->
## store/brand/profile

> Example request:

```bash
curl "https://endorsify.co/store/brand/profile" \
-H "Accept: application/json" \
    -d "website"="autem" \
    -d "description"="autem" \
    -d "industry"="autem" \
    -d "facebook"="autem" \
    -d "twitter"="autem" \
    -d "instagram"="autem" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/store/brand/profile",
    "method": "POST",
    "data": {
        "website": "autem",
        "description": "autem",
        "industry": "autem",
        "facebook": "autem",
        "twitter": "autem",
        "instagram": "autem"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST store/brand/profile`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    website | string |  required  | Must match this regular expression: `/\./`
    description | string |  required  | 
    industry | string |  required  | 
    facebook | string |  optional  | Must match this regular expression: `/^(?:(?:http|https):\/\/)?(?:www.)?facebook.com\/?/`
    twitter | string |  optional  | Must match this regular expression: `/^(?:(?:http|https):\/\/)?(?:www.)?twitter.com\/?/`
    instagram | string |  optional  | Must match this regular expression: `/^(?:(?:http|https):\/\/)?(?:www.)?instagram.com\/?/`

<!-- END_1e67857a5e65bfcf733ab0c7ae54ff95 -->
<!-- START_6ed2fbe900aeeedb2c956af652fcadb3 -->
## stats/followers/{user_id}

> Example request:

```bash
curl "https://endorsify.co/stats/followers/{user_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/stats/followers/{user_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET stats/followers/{user_id}`

`HEAD stats/followers/{user_id}`


<!-- END_6ed2fbe900aeeedb2c956af652fcadb3 -->
<!-- START_fe57da5855ac1613b9ad618372d724de -->
## stats/avg-likes/{user_id}

> Example request:

```bash
curl "https://endorsify.co/stats/avg-likes/{user_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/stats/avg-likes/{user_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET stats/avg-likes/{user_id}`

`HEAD stats/avg-likes/{user_id}`


<!-- END_fe57da5855ac1613b9ad618372d724de -->
<!-- START_a89bc6c8f1a46734d40560c77910aaf6 -->
## stats/eng-rate/{user_id}

> Example request:

```bash
curl "https://endorsify.co/stats/eng-rate/{user_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/stats/eng-rate/{user_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET stats/eng-rate/{user_id}`

`HEAD stats/eng-rate/{user_id}`


<!-- END_a89bc6c8f1a46734d40560c77910aaf6 -->
<!-- START_8a88b9e931c5052da2fa63aec466460d -->
## stats/cpm/{user_id}

> Example request:

```bash
curl "https://endorsify.co/stats/cpm/{user_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/stats/cpm/{user_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET stats/cpm/{user_id}`

`HEAD stats/cpm/{user_id}`


<!-- END_8a88b9e931c5052da2fa63aec466460d -->
#Subscription
<!-- START_f3ca1965d2e1a7ec30d305ab94d9996c -->
## paypal/brand/signup

> Example request:

```bash
curl "https://endorsify.co/paypal/brand/signup" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/paypal/brand/signup",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET paypal/brand/signup`

`HEAD paypal/brand/signup`


<!-- END_f3ca1965d2e1a7ec30d305ab94d9996c -->
<!-- START_d56dab7125a1fb84845b31970199eba6 -->
## plan/{plan}

> Example request:

```bash
curl "https://endorsify.co/plan/{plan}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/plan/{plan}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET plan/{plan}`

`HEAD plan/{plan}`


<!-- END_d56dab7125a1fb84845b31970199eba6 -->
<!-- START_074d3825d6750b75d0ec196764336674 -->
## paypal/brand/signup

> Example request:

```bash
curl "https://endorsify.co/paypal/brand/signup" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/paypal/brand/signup",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST paypal/brand/signup`


<!-- END_074d3825d6750b75d0ec196764336674 -->
<!-- START_162f96c3b8411925bf66549134daa532 -->
## paypal/brand/update

> Example request:

```bash
curl "https://endorsify.co/paypal/brand/update" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/paypal/brand/update",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET paypal/brand/update`

`HEAD paypal/brand/update`


<!-- END_162f96c3b8411925bf66549134daa532 -->
<!-- START_041f086d1e1982796ec6ecee6581673e -->
## paypal/brand/update

> Example request:

```bash
curl "https://endorsify.co/paypal/brand/update" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/paypal/brand/update",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST paypal/brand/update`


<!-- END_041f086d1e1982796ec6ecee6581673e -->
#User
<!-- START_9566a8caf83dacf40a3ebd7e35855d2d -->
## admin/dashboard

> Example request:

```bash
curl "https://endorsify.co/admin/dashboard" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/dashboard",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/dashboard`

`HEAD admin/dashboard`


<!-- END_9566a8caf83dacf40a3ebd7e35855d2d -->
<!-- START_f34eefe575f71c30d6fb822063ee3f47 -->
## admin/influencers

> Example request:

```bash
curl "https://endorsify.co/admin/influencers" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/influencers",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/influencers`

`HEAD admin/influencers`


<!-- END_f34eefe575f71c30d6fb822063ee3f47 -->
<!-- START_a95ccadd82bb4b024cf8c7f033aa5bc3 -->
## admin/influencer/edit/{user_id}

> Example request:

```bash
curl "https://endorsify.co/admin/influencer/edit/{user_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/influencer/edit/{user_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/influencer/edit/{user_id}`

`HEAD admin/influencer/edit/{user_id}`


<!-- END_a95ccadd82bb4b024cf8c7f033aa5bc3 -->
<!-- START_49bde1eaf1d0526feb539e5d1434209b -->
## admin/influencer/delete/{user_id}

> Example request:

```bash
curl "https://endorsify.co/admin/influencer/delete/{user_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/influencer/delete/{user_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/influencer/delete/{user_id}`

`HEAD admin/influencer/delete/{user_id}`


<!-- END_49bde1eaf1d0526feb539e5d1434209b -->
<!-- START_52e9c4890ef10207fe9942ffb3bb659d -->
## admin/influencers/revoke/lists

> Example request:

```bash
curl "https://endorsify.co/admin/influencers/revoke/lists" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/influencers/revoke/lists",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/influencers/revoke/lists`

`HEAD admin/influencers/revoke/lists`


<!-- END_52e9c4890ef10207fe9942ffb3bb659d -->
<!-- START_6f64203ba4fd4fa555dcb5d5172ca92b -->
## admin/influencer/revoke/{user_id}

> Example request:

```bash
curl "https://endorsify.co/admin/influencer/revoke/{user_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/influencer/revoke/{user_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/influencer/revoke/{user_id}`

`HEAD admin/influencer/revoke/{user_id}`


<!-- END_6f64203ba4fd4fa555dcb5d5172ca92b -->
<!-- START_20061691a1e10b4bca272be5dbfbef95 -->
## admin/influencer/revoke/{user_id}

> Example request:

```bash
curl "https://endorsify.co/admin/influencer/revoke/{user_id}" \
-H "Accept: application/json" \
    -d "subject"="alias" \
    -d "message"="alias" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/influencer/revoke/{user_id}",
    "method": "POST",
    "data": {
        "subject": "alias",
        "message": "alias"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST admin/influencer/revoke/{user_id}`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    subject | string |  required  | 
    message | string |  required  | 

<!-- END_20061691a1e10b4bca272be5dbfbef95 -->
<!-- START_c16e34dd7a9572e22f6d89577920a3dc -->
## admin/ifluencer/save/{user_id}

> Example request:

```bash
curl "https://endorsify.co/admin/ifluencer/save/{user_id}" \
-H "Accept: application/json" \
    -d "first_name"="saepe" \
    -d "last_name"="saepe" \
    -d "gender"="saepe" \
    -d "location"="saepe" \
    -d "city"="saepe" \
    -d "phone_number"="617530051" \
    -d "base_pay"="617530051" \
    -d "cpm"="617530051" \
    -d "cpe"="617530051" \
    -d "bio"="saepe" \
    -d "industries"="saepe" \
    -d "month"="saepe" \
    -d "day"="saepe" \
    -d "year"="saepe" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/ifluencer/save/{user_id}",
    "method": "POST",
    "data": {
        "first_name": "saepe",
        "last_name": "saepe",
        "gender": "saepe",
        "location": "saepe",
        "city": "saepe",
        "phone_number": 617530051,
        "base_pay": 617530051,
        "cpm": 617530051,
        "cpe": 617530051,
        "bio": "saepe",
        "industries": "saepe",
        "month": "saepe",
        "day": "saepe",
        "year": "saepe"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST admin/ifluencer/save/{user_id}`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    first_name | string |  required  | Minimum: `3`
    last_name | string |  required  | 
    gender | string |  required  | 
    location | string |  required  | 
    city | string |  required  | 
    phone_number | numeric |  required  | 
    base_pay | numeric |  required  | 
    cpm | numeric |  required  | 
    cpe | numeric |  required  | 
    bio | string |  required  | Minimum: `5`
    industries | string |  required  | 
    month | string |  required  | 
    day | string |  required  | 
    year | string |  required  | 

<!-- END_c16e34dd7a9572e22f6d89577920a3dc -->
<!-- START_024613f73a871d3bdcbbffe918694ac7 -->
## admin/without-social/lists

> Example request:

```bash
curl "https://endorsify.co/admin/without-social/lists" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/without-social/lists",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/without-social/lists`

`HEAD admin/without-social/lists`


<!-- END_024613f73a871d3bdcbbffe918694ac7 -->
<!-- START_f2491c9109dc79f969cf64f9b937f538 -->
## admin/brands

> Example request:

```bash
curl "https://endorsify.co/admin/brands" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/brands",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/brands`

`HEAD admin/brands`


<!-- END_f2491c9109dc79f969cf64f9b937f538 -->
<!-- START_fdad7d36dab8234a53a79b8d8a75b6d1 -->
## admin/brand/edit/{user_id}

> Example request:

```bash
curl "https://endorsify.co/admin/brand/edit/{user_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/brand/edit/{user_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/brand/edit/{user_id}`

`HEAD admin/brand/edit/{user_id}`


<!-- END_fdad7d36dab8234a53a79b8d8a75b6d1 -->
<!-- START_4467c6d0bd4bd3c2caf0479651b97e5e -->
## admin/brand/view/{user_id}

> Example request:

```bash
curl "https://endorsify.co/admin/brand/view/{user_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/brand/view/{user_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/brand/view/{user_id}`

`HEAD admin/brand/view/{user_id}`


<!-- END_4467c6d0bd4bd3c2caf0479651b97e5e -->
<!-- START_6e157a10189861efbda5f3ba9e8abc78 -->
## admin/brand/campaign-edit/{campaign_id}

> Example request:

```bash
curl "https://endorsify.co/admin/brand/campaign-edit/{campaign_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/brand/campaign-edit/{campaign_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/brand/campaign-edit/{campaign_id}`

`HEAD admin/brand/campaign-edit/{campaign_id}`


<!-- END_6e157a10189861efbda5f3ba9e8abc78 -->
<!-- START_03fa9b26fbebcdaaca0d39714f784537 -->
## admin/brand/campaign-edit/{campaign_id}

> Example request:

```bash
curl "https://endorsify.co/admin/brand/campaign-edit/{campaign_id}" \
-H "Accept: application/json" \
    -d "content_posted"="aut" \
    -d "cost"="aut" \
    -d "reach"="aut" \
    -d "likes"="aut" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/brand/campaign-edit/{campaign_id}",
    "method": "POST",
    "data": {
        "content_posted": "aut",
        "cost": "aut",
        "reach": "aut",
        "likes": "aut"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST admin/brand/campaign-edit/{campaign_id}`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    content_posted | string |  required  | 
    cost | string |  required  | 
    reach | string |  required  | 
    likes | string |  required  | 

<!-- END_03fa9b26fbebcdaaca0d39714f784537 -->
<!-- START_6467d7904f3a3348e65b3272bc09dee3 -->
## admin/brand/delete/{user_id}

> Example request:

```bash
curl "https://endorsify.co/admin/brand/delete/{user_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/brand/delete/{user_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/brand/delete/{user_id}`

`HEAD admin/brand/delete/{user_id}`


<!-- END_6467d7904f3a3348e65b3272bc09dee3 -->
<!-- START_b0042d3f955914e7d892121c45c6efb8 -->
## admin/brand/save/{user_id}

> Example request:

```bash
curl "https://endorsify.co/admin/brand/save/{user_id}" \
-H "Accept: application/json" \
    -d "brand_name"="quidem" \
    -d "website"="quidem" \
    -d "description"="quidem" \
    -d "industry"="quidem" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/brand/save/{user_id}",
    "method": "POST",
    "data": {
        "brand_name": "quidem",
        "website": "quidem",
        "description": "quidem",
        "industry": "quidem"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST admin/brand/save/{user_id}`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    brand_name | string |  required  | 
    website | string |  required  | Must match this regular expression: `/\./`
    description | string |  required  | 
    industry | string |  required  | 

<!-- END_b0042d3f955914e7d892121c45c6efb8 -->
<!-- START_e0556186c963e10f46c88be4a5af937b -->
## admin/change/status/{user_id}

> Example request:

```bash
curl "https://endorsify.co/admin/change/status/{user_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/change/status/{user_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/change/status/{user_id}`

`HEAD admin/change/status/{user_id}`


<!-- END_e0556186c963e10f46c88be4a5af937b -->
<!-- START_d27a8ba890c05f6374e365054cd8544b -->
## admin/dashcamp

> Example request:

```bash
curl "https://endorsify.co/admin/dashcamp" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/dashcamp",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/dashcamp`

`HEAD admin/dashcamp`


<!-- END_d27a8ba890c05f6374e365054cd8544b -->
<!-- START_2030c349abfa988c2172693d51cab67f -->
## admin/change/statuscamp/{id}

> Example request:

```bash
curl "https://endorsify.co/admin/change/statuscamp/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/change/statuscamp/{id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/change/statuscamp/{id}`

`HEAD admin/change/statuscamp/{id}`


<!-- END_2030c349abfa988c2172693d51cab67f -->
<!-- START_fd4b8d68bedcc9489dd35420d836cf06 -->
## admin/dashcamp/edit/{id}

> Example request:

```bash
curl "https://endorsify.co/admin/dashcamp/edit/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/dashcamp/edit/{id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/dashcamp/edit/{id}`

`HEAD admin/dashcamp/edit/{id}`


<!-- END_fd4b8d68bedcc9489dd35420d836cf06 -->
<!-- START_ba587819adf2d37413a2323f20ba02f9 -->
## admin/dashcamp/delete/{id}

> Example request:

```bash
curl "https://endorsify.co/admin/dashcamp/delete/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/dashcamp/delete/{id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/dashcamp/delete/{id}`

`HEAD admin/dashcamp/delete/{id}`


<!-- END_ba587819adf2d37413a2323f20ba02f9 -->
<!-- START_5acb285ab3b221ea3fd950e37399b478 -->
## admin/dashcamp/save/{id}

> Example request:

```bash
curl "https://endorsify.co/admin/dashcamp/save/{id}" \
-H "Accept: application/json" \
    -d "name"="quasi" \
    -d "logo"="quasi" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/dashcamp/save/{id}",
    "method": "POST",
    "data": {
        "name": "quasi",
        "logo": "quasi"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST admin/dashcamp/save/{id}`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    name | string |  required  | 
    logo | string |  required  | Must match this regular expression: `/\b(?:(?:https?|ftp):\/\/|www\.)[-a-z0-9+&@#\/%?=~_|!:,.;]*[-a-z0-9+&@#\/%=~_|]/i`

<!-- END_5acb285ab3b221ea3fd950e37399b478 -->
<!-- START_29b60fe1b88c64e4fbe8c50617d81609 -->
## admin/dashcamp/add

> Example request:

```bash
curl "https://endorsify.co/admin/dashcamp/add" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/dashcamp/add",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/dashcamp/add`

`HEAD admin/dashcamp/add`


<!-- END_29b60fe1b88c64e4fbe8c50617d81609 -->
<!-- START_d0a94c40ad9dd4f381f1929268acef9e -->
## admin/feedback

> Example request:

```bash
curl "https://endorsify.co/admin/feedback" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/feedback",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/feedback`

`HEAD admin/feedback`


<!-- END_d0a94c40ad9dd4f381f1929268acef9e -->
<!-- START_4a1ea97cac43b23dbe9af3641841f952 -->
## admin/view/influencers/{user_id}

> Example request:

```bash
curl "https://endorsify.co/admin/view/influencers/{user_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/view/influencers/{user_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/view/influencers/{user_id}`

`HEAD admin/view/influencers/{user_id}`


<!-- END_4a1ea97cac43b23dbe9af3641841f952 -->
<!-- START_14713a7ae7f78e053fceaa3a7a6a2876 -->
## admin/send/email/{user_id}

> Example request:

```bash
curl "https://endorsify.co/admin/send/email/{user_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/send/email/{user_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/send/email/{user_id}`

`HEAD admin/send/email/{user_id}`


<!-- END_14713a7ae7f78e053fceaa3a7a6a2876 -->
<!-- START_a2fb05787960ce36554ed93c03102049 -->
## admin/send/email/{user_id}

> Example request:

```bash
curl "https://endorsify.co/admin/send/email/{user_id}" \
-H "Accept: application/json" \
    -d "subject"="incidunt" \
    -d "message"="incidunt" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/send/email/{user_id}",
    "method": "POST",
    "data": {
        "subject": "incidunt",
        "message": "incidunt"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST admin/send/email/{user_id}`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    subject | string |  required  | 
    message | string |  required  | 

<!-- END_a2fb05787960ce36554ed93c03102049 -->
<!-- START_0aad4dadf5653e9c4e2128b10f81f8c4 -->
## admin/contact-us

> Example request:

```bash
curl "https://endorsify.co/admin/contact-us" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/contact-us",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/contact-us`

`HEAD admin/contact-us`


<!-- END_0aad4dadf5653e9c4e2128b10f81f8c4 -->
<!-- START_5ae2699eda884a91494da79ef8631c30 -->
## admin/contact-us/status/{id}

> Example request:

```bash
curl "https://endorsify.co/admin/contact-us/status/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/contact-us/status/{id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/contact-us/status/{id}`

`HEAD admin/contact-us/status/{id}`


<!-- END_5ae2699eda884a91494da79ef8631c30 -->
<!-- START_a17f6c70fbc61ca8c347de3978cbf7ac -->
## admin/industry

> Example request:

```bash
curl "https://endorsify.co/admin/industry" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/industry",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/industry`

`HEAD admin/industry`


<!-- END_a17f6c70fbc61ca8c347de3978cbf7ac -->
<!-- START_ce0703d3359824b0fc4d57bbed0e18f1 -->
## admin/industry/add

> Example request:

```bash
curl "https://endorsify.co/admin/industry/add" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/industry/add",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/industry/add`

`HEAD admin/industry/add`


<!-- END_ce0703d3359824b0fc4d57bbed0e18f1 -->
<!-- START_464f8ffadcb7fd4fac91c56e2177c50b -->
## admin/industry/edit/{id}

> Example request:

```bash
curl "https://endorsify.co/admin/industry/edit/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/industry/edit/{id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/industry/edit/{id}`

`HEAD admin/industry/edit/{id}`


<!-- END_464f8ffadcb7fd4fac91c56e2177c50b -->
<!-- START_8b43dbae8ca8524136050eb731a69647 -->
## admin/industry/delete/{id}

> Example request:

```bash
curl "https://endorsify.co/admin/industry/delete/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/industry/delete/{id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/industry/delete/{id}`

`HEAD admin/industry/delete/{id}`


<!-- END_8b43dbae8ca8524136050eb731a69647 -->
<!-- START_8c4847f39ef088ab321e245468edb7b8 -->
## admin/industry/save

> Example request:

```bash
curl "https://endorsify.co/admin/industry/save" \
-H "Accept: application/json" \
    -d "name"="aut" \
    -d "status"="aut" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/industry/save",
    "method": "POST",
    "data": {
        "name": "aut",
        "status": "aut"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST admin/industry/save`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    name | string |  required  | 
    status | string |  required  | 

<!-- END_8c4847f39ef088ab321e245468edb7b8 -->
<!-- START_7ba3d84dfd1e95957610fc20c5d95d4e -->
## admin/industry/update/{id}

> Example request:

```bash
curl "https://endorsify.co/admin/industry/update/{id}" \
-H "Accept: application/json" \
    -d "name"="accusantium" \
    -d "status"="accusantium" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/industry/update/{id}",
    "method": "POST",
    "data": {
        "name": "accusantium",
        "status": "accusantium"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST admin/industry/update/{id}`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    name | string |  required  | 
    status | string |  required  | 

<!-- END_7ba3d84dfd1e95957610fc20c5d95d4e -->
<!-- START_368012cfbdcbe592e777dd308d2d0db2 -->
## admin/industry/change/status/{id}

> Example request:

```bash
curl "https://endorsify.co/admin/industry/change/status/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/industry/change/status/{id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/industry/change/status/{id}`

`HEAD admin/industry/change/status/{id}`


<!-- END_368012cfbdcbe592e777dd308d2d0db2 -->
<!-- START_9b236ea310f927973ee914fbf526efca -->
## admin/hired

> Example request:

```bash
curl "https://endorsify.co/admin/hired" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/hired",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/hired`

`HEAD admin/hired`


<!-- END_9b236ea310f927973ee914fbf526efca -->
<!-- START_e02baf717a1a5f3e22d0240c88dd9182 -->
## admin/hired/change/status/{params}

> Example request:

```bash
curl "https://endorsify.co/admin/hired/change/status/{params}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/hired/change/status/{params}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/hired/change/status/{params}`

`HEAD admin/hired/change/status/{params}`


<!-- END_e02baf717a1a5f3e22d0240c88dd9182 -->
<!-- START_8f36370a08231a4e9ea2d3ca3f334a98 -->
## admin/change/password

> Example request:

```bash
curl "https://endorsify.co/admin/change/password" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/change/password",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET admin/change/password`

`HEAD admin/change/password`


<!-- END_8f36370a08231a4e9ea2d3ca3f334a98 -->
<!-- START_4d359e48a9af16de601d1a02aa3eb64e -->
## admin/change/password

> Example request:

```bash
curl "https://endorsify.co/admin/change/password" \
-H "Accept: application/json" \
    -d "current_password"="rerum" \
    -d "new_password"="rerum" \
    -d "confirm_password"="rerum" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/change/password",
    "method": "POST",
    "data": {
        "current_password": "rerum",
        "new_password": "rerum",
        "confirm_password": "rerum"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST admin/change/password`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    current_password | string |  required  | 
    new_password | string |  required  | Minimum: `6` Maximum: `50` Must match this regular expression: `/^(?=.*[a-z|A-Z])(?=.*[A-Z])(?=.*\d).+$/`
    confirm_password | string |  required  | Must be the same as `new_password`

<!-- END_4d359e48a9af16de601d1a02aa3eb64e -->
<!-- START_2b3a958f446cb9d3b82f4fc94fdac645 -->
## admin/export/{type}

> Example request:

```bash
curl "https://endorsify.co/admin/export/{type}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/admin/export/{type}",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST admin/export/{type}`


<!-- END_2b3a958f446cb9d3b82f4fc94fdac645 -->
#general
<!-- START_b8a26549776bc13ed0fd6a49df203ae6 -->
## Authenticate the request for channel access.

> Example request:

```bash
curl "https://endorsify.co/broadcasting/auth" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/broadcasting/auth",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST broadcasting/auth`


<!-- END_b8a26549776bc13ed0fd6a49df203ae6 -->
<!-- START_aa4b683fffc265536f9e1043e8cfc24d -->
## pages/{name}

> Example request:

```bash
curl "https://endorsify.co/pages/{name}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/pages/{name}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET pages/{name}`

`HEAD pages/{name}`


<!-- END_aa4b683fffc265536f9e1043e8cfc24d -->
<!-- START_c01d4b17c88274fc6c8396c463b3d0b5 -->
## pages/post/contact_us

> Example request:

```bash
curl "https://endorsify.co/pages/post/contact_us" \
-H "Accept: application/json" \
    -d "name"="blanditiis" \
    -d "location"="blanditiis" \
    -d "email"="chandler.cassin@example.org" \
    -d "phone_number"="blanditiis" \
    -d "message"="blanditiis" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/pages/post/contact_us",
    "method": "POST",
    "data": {
        "name": "blanditiis",
        "location": "blanditiis",
        "email": "chandler.cassin@example.org",
        "phone_number": "blanditiis",
        "message": "blanditiis"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST pages/post/contact_us`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    name | string |  required  | 
    location | string |  required  | Maximum: `255`
    email | email |  required  | 
    phone_number | string |  required  | Must match this regular expression: `/^\(?([0-9]{3})\)?[-.●]?([0-9]{3})[-.●]?([0-9]{4})$/`
    message | string |  optional  | Maximum: `400`

<!-- END_c01d4b17c88274fc6c8396c463b3d0b5 -->
<!-- START_778e5f83dc5cb9c5851cf0ad985b4534 -->
## signup

> Example request:

```bash
curl "https://endorsify.co/signup" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/signup",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET signup`

`HEAD signup`


<!-- END_778e5f83dc5cb9c5851cf0ad985b4534 -->
<!-- START_9085287582de0f0288ad1ec3f30fbbbc -->
## signup/{name}

> Example request:

```bash
curl "https://endorsify.co/signup/{name}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/signup/{name}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET signup/{name}`

`HEAD signup/{name}`


<!-- END_9085287582de0f0288ad1ec3f30fbbbc -->
<!-- START_02f750c97b19b7e6377d0a2e59a16f8d -->
## managed-service

> Example request:

```bash
curl "https://endorsify.co/managed-service" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/managed-service",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET managed-service`

`HEAD managed-service`


<!-- END_02f750c97b19b7e6377d0a2e59a16f8d -->
<!-- START_45def4da6d09e649f3b2c95189bbb020 -->
## login

> Example request:

```bash
curl "https://endorsify.co/login" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/login",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET login`

`HEAD login`


<!-- END_45def4da6d09e649f3b2c95189bbb020 -->
<!-- START_26553179412c74a7b45c1867abcab1ba -->
## forgot-password

> Example request:

```bash
curl "https://endorsify.co/forgot-password" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/forgot-password",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET forgot-password`

`HEAD forgot-password`


<!-- END_26553179412c74a7b45c1867abcab1ba -->
<!-- START_d5020378cd80c7734cbcbc4581b4305d -->
## forgot-password

> Example request:

```bash
curl "https://endorsify.co/forgot-password" \
-H "Accept: application/json" \
    -d "email"="wisozk.hassan@example.net" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/forgot-password",
    "method": "POST",
    "data": {
        "email": "wisozk.hassan@example.net"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST forgot-password`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    email | email |  required  | 

<!-- END_d5020378cd80c7734cbcbc4581b4305d -->
<!-- START_0947747dbbfc9a25cf91b57418b58484 -->
## signup-influencer

> Example request:

```bash
curl "https://endorsify.co/signup-influencer" \
-H "Accept: application/json" \
    -d "email"="vkoepp@example.org" \
    -d "password"="saepe" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/signup-influencer",
    "method": "POST",
    "data": {
        "email": "vkoepp@example.org",
        "password": "saepe"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST signup-influencer`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    email | email |  required  | 
    password | string |  required  | Minimum: `6` Maximum: `50` Must match this regular expression: `/^(?=.*[a-z|A-Z])(?=.*[A-Z])(?=.*\d).+$/`

<!-- END_0947747dbbfc9a25cf91b57418b58484 -->
<!-- START_06c4420c2c12d10decaeea7d71b52ce4 -->
## signup-brand

> Example request:

```bash
curl "https://endorsify.co/signup-brand" \
-H "Accept: application/json" \
    -d "first_name"="cumque" \
    -d "last_name"="cumque" \
    -d "brand_name"="cumque" \
    -d "email"="zola97@example.net" \
    -d "password"="cumque" \
    -d "phone"="cumque" \
    -d "wheredid"="cumque" \
    -d "help"="cumque" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/signup-brand",
    "method": "POST",
    "data": {
        "first_name": "cumque",
        "last_name": "cumque",
        "brand_name": "cumque",
        "email": "zola97@example.net",
        "password": "cumque",
        "phone": "cumque",
        "wheredid": "cumque",
        "help": "cumque"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST signup-brand`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    first_name | string |  required  | Maximum: `255`
    last_name | string |  required  | Maximum: `255`
    brand_name | string |  required  | 
    email | email |  required  | 
    password | string |  required  | Minimum: `6` Maximum: `50` Must match this regular expression: `/^(?=.*[a-z|A-Z])(?=.*[A-Z])(?=.*\d).+$/`
    phone | string |  required  | Must match this regular expression: `/^\(?([0-9]{3})\)?[-.●]?([0-9]{3})[-.●]?([0-9]{4})$/`
    wheredid | string |  required  | Maximum: `255`
    help | string |  optional  | Maximum: `400`

<!-- END_06c4420c2c12d10decaeea7d71b52ce4 -->
<!-- START_d181e5d4fdd51a6a08ed0b736b68c405 -->
## login/instagram

> Example request:

```bash
curl "https://endorsify.co/login/instagram" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/login/instagram",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET login/instagram`

`HEAD login/instagram`


<!-- END_d181e5d4fdd51a6a08ed0b736b68c405 -->
<!-- START_8c0d0f3474708d520f7fa37ef6e3c84c -->
## auth/response

> Example request:

```bash
curl "https://endorsify.co/auth/response" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/auth/response",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET auth/response`

`HEAD auth/response`


<!-- END_8c0d0f3474708d520f7fa37ef6e3c84c -->
<!-- START_63aca094ed4a38127b6c7b53f0a45380 -->
## influencer/{user_id}

> Example request:

```bash
curl "https://endorsify.co/influencer/{user_id}" \
-H "Accept: application/json" \
    -d "bio"="architecto" \
    -d "indicative_fee"="4" \
    -d "first_name"="architecto" \
    -d "last_name"="architecto" \
    -d "month"="architecto" \
    -d "day"="architecto" \
    -d "year"="architecto" \
    -d "gender"="architecto" \
    -d "location"="architecto" \
    -d "city"="architecto" \
    -d "phone_number"="architecto" \
    -d "paypal_email"="kozey.mandy@example.com" \
    -d "industries"="architecto" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/influencer/{user_id}",
    "method": "POST",
    "data": {
        "bio": "architecto",
        "indicative_fee": 4,
        "first_name": "architecto",
        "last_name": "architecto",
        "month": "architecto",
        "day": "architecto",
        "year": "architecto",
        "gender": "architecto",
        "location": "architecto",
        "city": "architecto",
        "phone_number": "architecto",
        "paypal_email": "kozey.mandy@example.com",
        "industries": "architecto"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST influencer/{user_id}`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    bio | string |  required  | Minimum: `5`
    indicative_fee | numeric |  required  | 
    first_name | string |  required  | 
    last_name | string |  required  | 
    month | string |  required  | 
    day | string |  required  | 
    year | string |  required  | 
    gender | string |  required  | 
    location | string |  required  | 
    city | string |  required  | 
    phone_number | string |  required  | 
    paypal_email | email |  optional  | 
    industries | string |  required  | 

<!-- END_63aca094ed4a38127b6c7b53f0a45380 -->
<!-- START_caa58dbcc73794e55bcb5d52b6809c35 -->
## instagram

> Example request:

```bash
curl "https://endorsify.co/instagram" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/instagram",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET instagram`

`HEAD instagram`


<!-- END_caa58dbcc73794e55bcb5d52b6809c35 -->
<!-- START_06586d4005ac1b409c5e977b67b9f3ab -->
## user-login

> Example request:

```bash
curl "https://endorsify.co/user-login" \
-H "Accept: application/json" \
    -d "email"="aric.mayert@example.com" \
    -d "password"="atque" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/user-login",
    "method": "POST",
    "data": {
        "email": "aric.mayert@example.com",
        "password": "atque"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST user-login`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    email | email |  required  | 
    password | string |  required  | 

<!-- END_06586d4005ac1b409c5e977b67b9f3ab -->
<!-- START_9afa4e404f32e488d703a8d08f5e7785 -->
## user-login-home

> Example request:

```bash
curl "https://endorsify.co/user-login-home" \
-H "Accept: application/json" \
    -d "email"="manley.satterfield@example.net" \
    -d "password"="quaerat" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/user-login-home",
    "method": "POST",
    "data": {
        "email": "manley.satterfield@example.net",
        "password": "quaerat"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST user-login-home`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    email | email |  required  | 
    password | string |  required  | 

<!-- END_9afa4e404f32e488d703a8d08f5e7785 -->
<!-- START_082193b2c4e68f0e7b316efaf9520eba -->
## Display options to select payment method

> Example request:

```bash
curl "https://endorsify.co/signup-home" \
-H "Accept: application/json" \
    -d "email"="aurelie.bashirian@example.org" \
    -d "password"="ullam" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/signup-home",
    "method": "POST",
    "data": {
        "email": "aurelie.bashirian@example.org",
        "password": "ullam"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST signup-home`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    email | email |  required  | 
    password | string |  required  | Minimum: `6` Maximum: `50` Must match this regular expression: `/^(?=.*[a-z|A-Z])(?=.*[A-Z])(?=.*\d).+$/`

<!-- END_082193b2c4e68f0e7b316efaf9520eba -->
<!-- START_662786edd6508906cb5d5b25dc8102a3 -->
## search/ajax/botInfluencer/{industry}

> Example request:

```bash
curl "https://endorsify.co/search/ajax/botInfluencer/{industry}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/search/ajax/botInfluencer/{industry}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET search/ajax/botInfluencer/{industry}`

`HEAD search/ajax/botInfluencer/{industry}`

`POST search/ajax/botInfluencer/{industry}`

`PUT search/ajax/botInfluencer/{industry}`

`PATCH search/ajax/botInfluencer/{industry}`

`DELETE search/ajax/botInfluencer/{industry}`


<!-- END_662786edd6508906cb5d5b25dc8102a3 -->
<!-- START_87f91668b39e86bf308dc4a1ad023b87 -->
## sitemap

> Example request:

```bash
curl "https://endorsify.co/sitemap" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/sitemap",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET sitemap`

`HEAD sitemap`


<!-- END_87f91668b39e86bf308dc4a1ad023b87 -->
<!-- START_78c84aedea5cf9f44215a083c149daee -->
## logout

> Example request:

```bash
curl "https://endorsify.co/logout" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/logout",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET logout`

`HEAD logout`


<!-- END_78c84aedea5cf9f44215a083c149daee -->
<!-- START_ec47820aa773aa75b2caedcca275003e -->
## response/thanks

> Example request:

```bash
curl "https://endorsify.co/response/thanks" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/response/thanks",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET response/thanks`

`HEAD response/thanks`


<!-- END_ec47820aa773aa75b2caedcca275003e -->
<!-- START_366d4fb0e6c4c9eb79686a1f4b493988 -->
## influencer/apply/{social_id}

> Example request:

```bash
curl "https://endorsify.co/influencer/apply/{social_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/influencer/apply/{social_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET influencer/apply/{social_id}`

`HEAD influencer/apply/{social_id}`


<!-- END_366d4fb0e6c4c9eb79686a1f4b493988 -->
<!-- START_7f1bce507cda7d40c1610eb164fe7468 -->
## demo/influencers

> Example request:

```bash
curl "https://endorsify.co/demo/influencers" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/demo/influencers",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET demo/influencers`

`HEAD demo/influencers`


<!-- END_7f1bce507cda7d40c1610eb164fe7468 -->
<!-- START_e2ea200ee9790570d3d09c92803f1ae1 -->
## demo/content-search

> Example request:

```bash
curl "https://endorsify.co/demo/content-search" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/demo/content-search",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET demo/content-search`

`HEAD demo/content-search`


<!-- END_e2ea200ee9790570d3d09c92803f1ae1 -->
<!-- START_4cdf47cbcf17f66e3add082141eed89d -->
## demo/campaign

> Example request:

```bash
curl "https://endorsify.co/demo/campaign" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/demo/campaign",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET demo/campaign`

`HEAD demo/campaign`


<!-- END_4cdf47cbcf17f66e3add082141eed89d -->
<!-- START_9a1ba66b41afadf5bac1604adb9c5085 -->
## demo/campaign/view

> Example request:

```bash
curl "https://endorsify.co/demo/campaign/view" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/demo/campaign/view",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET demo/campaign/view`

`HEAD demo/campaign/view`


<!-- END_9a1ba66b41afadf5bac1604adb9c5085 -->
<!-- START_1b62872f7e85d797804cb8f8a29f9180 -->
## demo/messages

> Example request:

```bash
curl "https://endorsify.co/demo/messages" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/demo/messages",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET demo/messages`

`HEAD demo/messages`


<!-- END_1b62872f7e85d797804cb8f8a29f9180 -->
<!-- START_f26b6a6eca58d4718f0befd79e781bf8 -->
## demo/demotime

> Example request:

```bash
curl "https://endorsify.co/demo/demotime" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/demo/demotime",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET demo/demotime`

`HEAD demo/demotime`


<!-- END_f26b6a6eca58d4718f0befd79e781bf8 -->
<!-- START_1d7af42cf289ff9ae1fb258141982a20 -->
## stripe/influencer/signup

> Example request:

```bash
curl "https://endorsify.co/stripe/influencer/signup" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/stripe/influencer/signup",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET stripe/influencer/signup`

`HEAD stripe/influencer/signup`


<!-- END_1d7af42cf289ff9ae1fb258141982a20 -->
<!-- START_808985ef5e570a2770cd64567ecf1ced -->
## stripe/influencer/signup

> Example request:

```bash
curl "https://endorsify.co/stripe/influencer/signup" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/stripe/influencer/signup",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST stripe/influencer/signup`


<!-- END_808985ef5e570a2770cd64567ecf1ced -->
<!-- START_ec7f5b5bcbb7a3ec8003fb6aa2338c9c -->
## stripe/influencer/update

> Example request:

```bash
curl "https://endorsify.co/stripe/influencer/update" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/stripe/influencer/update",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET stripe/influencer/update`

`HEAD stripe/influencer/update`


<!-- END_ec7f5b5bcbb7a3ec8003fb6aa2338c9c -->
<!-- START_48a7259beb5b9f9fcf1ce324b96db537 -->
## stripe/influencer/update

> Example request:

```bash
curl "https://endorsify.co/stripe/influencer/update" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/stripe/influencer/update",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST stripe/influencer/update`


<!-- END_48a7259beb5b9f9fcf1ce324b96db537 -->
<!-- START_252bb81e739ad2d9df0fff898abac2f7 -->
## stripe/brand/signup

> Example request:

```bash
curl "https://endorsify.co/stripe/brand/signup" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/stripe/brand/signup",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET stripe/brand/signup`

`HEAD stripe/brand/signup`


<!-- END_252bb81e739ad2d9df0fff898abac2f7 -->
<!-- START_36582454211b7d40ac548c9fd44fdc55 -->
## stripe/brand/signup

> Example request:

```bash
curl "https://endorsify.co/stripe/brand/signup" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/stripe/brand/signup",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST stripe/brand/signup`


<!-- END_36582454211b7d40ac548c9fd44fdc55 -->
<!-- START_200344699914057f8a7893377b404f29 -->
## stripe/brand/update

> Example request:

```bash
curl "https://endorsify.co/stripe/brand/update" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/stripe/brand/update",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET stripe/brand/update`

`HEAD stripe/brand/update`


<!-- END_200344699914057f8a7893377b404f29 -->
<!-- START_97bad058de0e9988d56683b328f2bb4b -->
## stripe/brand/update

> Example request:

```bash
curl "https://endorsify.co/stripe/brand/update" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/stripe/brand/update",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST stripe/brand/update`


<!-- END_97bad058de0e9988d56683b328f2bb4b -->
<!-- START_208aca5160c99be7dd2246a5d15311fe -->
## braintree/token

> Example request:

```bash
curl "https://endorsify.co/braintree/token" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/braintree/token",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET braintree/token`

`HEAD braintree/token`


<!-- END_208aca5160c99be7dd2246a5d15311fe -->
<!-- START_f612e9532d9e8ad7dc52c51f2fb770de -->
## search/influencers

> Example request:

```bash
curl "https://endorsify.co/search/influencers" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/search/influencers",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET search/influencers`

`HEAD search/influencers`


<!-- END_f612e9532d9e8ad7dc52c51f2fb770de -->
<!-- START_9d3bd66aecefc53be0167bba047242ba -->
## search/ajax/influencers

> Example request:

```bash
curl "https://endorsify.co/search/ajax/influencers" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/search/ajax/influencers",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST search/ajax/influencers`


<!-- END_9d3bd66aecefc53be0167bba047242ba -->
<!-- START_45f8f859983f070672922acc12916256 -->
## search/ajax/feedback

> Example request:

```bash
curl "https://endorsify.co/search/ajax/feedback" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/search/ajax/feedback",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST search/ajax/feedback`


<!-- END_45f8f859983f070672922acc12916256 -->
<!-- START_6884d4f33487247a3541cfaa582a3f8b -->
## search/ajax/content-search

> Example request:

```bash
curl "https://endorsify.co/search/ajax/content-search" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/search/ajax/content-search",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST search/ajax/content-search`


<!-- END_6884d4f33487247a3541cfaa582a3f8b -->
<!-- START_41cc78e55819ae615ed6541611b35226 -->
## search/content-search

> Example request:

```bash
curl "https://endorsify.co/search/content-search" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/search/content-search",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET search/content-search`

`HEAD search/content-search`


<!-- END_41cc78e55819ae615ed6541611b35226 -->
<!-- START_a450f72d0b9b15334b56ba0ba0eefe33 -->
## influencer/viewprofile/{social_id}

> Example request:

```bash
curl "https://endorsify.co/influencer/viewprofile/{social_id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/influencer/viewprofile/{social_id}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET influencer/viewprofile/{social_id}`

`HEAD influencer/viewprofile/{social_id}`


<!-- END_a450f72d0b9b15334b56ba0ba0eefe33 -->
<!-- START_a1c9263ff0c1ec29cd835f949ca55497 -->
## stripe/charge

> Example request:

```bash
curl "https://endorsify.co/stripe/charge" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/stripe/charge",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST stripe/charge`


<!-- END_a1c9263ff0c1ec29cd835f949ca55497 -->
<!-- START_662d345ef1e6639c5738f5781a8faf15 -->
## stripe/transfer

> Example request:

```bash
curl "https://endorsify.co/stripe/transfer" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/stripe/transfer",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST stripe/transfer`


<!-- END_662d345ef1e6639c5738f5781a8faf15 -->
<!-- START_b9f621571262dcf2d34f259d13dc4013 -->
## messages

> Example request:

```bash
curl "https://endorsify.co/messages" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/messages",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "error": "Unauthenticated."
}
```

### HTTP Request
`GET messages`

`HEAD messages`


<!-- END_b9f621571262dcf2d34f259d13dc4013 -->
<!-- START_4ef2095ce9b788538960708c0aec76eb -->
## messages

> Example request:

```bash
curl "https://endorsify.co/messages" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/messages",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST messages`


<!-- END_4ef2095ce9b788538960708c0aec76eb -->
<!-- START_7bf3b05711919ce132e458c2c00e2bcd -->
## messages/archive

> Example request:

```bash
curl "https://endorsify.co/messages/archive" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/messages/archive",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST messages/archive`


<!-- END_7bf3b05711919ce132e458c2c00e2bcd -->
<!-- START_1b5b6a70195f5113a3acc22feaf0162a -->
## messages/unarchive

> Example request:

```bash
curl "https://endorsify.co/messages/unarchive" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/messages/unarchive",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST messages/unarchive`


<!-- END_1b5b6a70195f5113a3acc22feaf0162a -->
<!-- START_4d003b450bcf8c24c61ee3489936723f -->
## messages/delete

> Example request:

```bash
curl "https://endorsify.co/messages/delete" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/messages/delete",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST messages/delete`


<!-- END_4d003b450bcf8c24c61ee3489936723f -->
<!-- START_bdf40d524589561f19f86e27622bd7d8 -->
## messages/upload

> Example request:

```bash
curl "https://endorsify.co/messages/upload" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/messages/upload",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST messages/upload`


<!-- END_bdf40d524589561f19f86e27622bd7d8 -->
<!-- START_53ced99fef1b333aeba8b35e3a3f7e4b -->
## messages/online

> Example request:

```bash
curl "https://endorsify.co/messages/online" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/messages/online",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST messages/online`


<!-- END_53ced99fef1b333aeba8b35e3a3f7e4b -->
<!-- START_fee310a89f24e8e412fc5929d2b37a4b -->
## pusher/auth

> Example request:

```bash
curl "https://endorsify.co/pusher/auth" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://endorsify.co/pusher/auth",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST pusher/auth`


<!-- END_fee310a89f24e8e412fc5929d2b37a4b -->

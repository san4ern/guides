# Random Image

{% hint style="warning" %}
You can use package for it

[https://www.npmjs.com/package/random-img-lib](https://www.npmjs.com/package/random-img-lib)  
{% endhint %}

{% api-method method="get" host="https://san4ouZ.ml" path="/random?q=:type" %}
{% api-method-summary %}
Get random image
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to get random image
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-query-parameters %}
{% api-method-parameter name="q" type="string" %}
Allowed types are foxes, memes, fennec, dogs, cats
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Image successfully retrived
{% endapi-method-response-example-description %}

```
{ type: true, message: 'url' }
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=302 %}
{% api-method-response-example-description %}
There are not images to get randomized
{% endapi-method-response-example-description %}

```
{ type: false, message: 'There are not images to get randomized' }
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=404 %}
{% api-method-response-example-description %}
Could not a type matching this query
{% endapi-method-response-example-description %}

```
{ type: false, message: 'No such method were found' }
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% hint style="success" %}
If this guide helps you, you can like it
{% endhint %}


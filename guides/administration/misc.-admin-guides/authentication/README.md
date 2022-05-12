# Authentication

{% content-ref url="open-id-connect/" %}
[open-id-connect](open-id-connect/)
{% endcontent-ref %}

{% content-ref url="single-sign-on-iframe.md" %}
[single-sign-on-iframe.md](single-sign-on-iframe.md)
{% endcontent-ref %}

## External Authentication

If you need to automatically login users from your own website you can look at [Iframe integration page](https://github.com/jpreynat/docs-3/blob/master/guides/administration/misc.-admin-guides/authentication/broken-reference/README.md) or you can use the REST API [Login](https://github.com/jpreynat/docs-3/blob/master/guides/administration/misc.-admin-guides/authentication/broken-reference/README.md) in combination with [deeplinking](https://github.com/jpreynat/docs-3/blob/master/guides/administration/misc.-admin-guides/authentication/broken-reference/README.md) and the resumeToken.

```
# get the resumeToken from your REST API login - it's the authToken field
https://yourown.rocket.chat/home?resumeToken=abcd123456789
```

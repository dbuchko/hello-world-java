# hello-world-java
Repo with a basic sample Mulesoft app for testing.

Console deployed to `https://<app-url>/console/java/``

Java API – PUT

Body [JSON] example:

```
{

  "firstName": "Bobby",

  "lastName": "Fisher"

}
```
Eg:
```
curl -X PUT -H 'Content-Type: application/json' -d '{"firstName": "Bobby", "lastName": "Fisher"}' https://<app-url>/java/helloworld
```

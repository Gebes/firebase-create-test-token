# Firebase Create Test Token

Create a custom token for a specific UID and simply verify it using the Firebase API.

```go
func CreateTestToken(client *auth.Client, firebaseKey, uid string) (string, error)
```
---
title: "parseJWT()"
---

# parseJWT()

Parses a JSON web token. Throws an `Error` if the token is not well-formed. This method does not verify the payload claims, such as expiration, or the signature.

## Definition

```ts
function parseJWT(jwt: string): [header: object, payload: header, signature: Uint8Array];
```

### Parameters

- `jwt`

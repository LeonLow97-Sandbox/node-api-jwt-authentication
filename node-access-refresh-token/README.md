# Content

[Web Dev Simplified](https://www.youtube.com/watch?v=-RCnNyD0L-s&ab_channel=WebDevSimplified)

## Run on NodeJS

- To generate a Secret:
    - `require('crypto').randomBytes(64).toString('hex')`

## RefreshToken

- To handle expiration date on accesstoken.

## Logout

- Remove the refreshToken so no more accessToken can be created.
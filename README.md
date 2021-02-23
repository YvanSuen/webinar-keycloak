# Demo for Keycloak Integration in ASP.NET Core and Angular.

## Start

Use 

```
docker-compose up
```

to start Keycloak, the API and Angular Frontend.

## Urls

| System   | Url                   |
| -------- | --------------------- |
| Keycloak | http://localhost:8080 |
| API      | http://localhost:5000 |
| Frontend | http://localhost:4200 |

## Logins

| Username  | Password  | Description                                     |
| --------- | --------- | ----------------------------------------------- |
| editor    | editor    | Can create posts and delete not published posts |
| publisher | publisher | Can publish and unpublish posts                 |
| legal     | lega      | Can unpublish posts                             |


## Point of interest

[src\api\startup.cs](src/api/startup.cs#L67)
Configure Jwt Bearer authentication to use Keycloak


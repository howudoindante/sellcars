# SELLCARS 
### Graduation project for the sale cars

## FAQ

#### Why?

In my opinion, this project fully reveals my abilities. And this is a great opportunity to consolidate your skills.

## API Reference

#### Login

```http
  POST /auth/login
```
***Request body parameters***
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `username` | `string` | **Required**. Your username. |
| `password` | `string` | **Required**. Your password. |

***Response parameters***

Status: 200
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `token` | `string` | Authorization token. |

Status: 400
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `message` | `string` | Error message. |

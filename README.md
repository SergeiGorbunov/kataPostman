1) POST (https://blog.kata.academy/api/users):
  {
  "user": {
    "username": "SergeiGorbunov",
    "email": "gorbunov-city@mail.ru",
    "password": "aezakmi"
  }
}
Response:
{
    "user": {
        "username": "sergeigorbunov",
        "email": "gorbunov-city@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0NjM3MjI5NjBjNjc1MWIwMGI3NzQyMiIsInVzZXJuYW1lIjoic2VyZ2VpZ29yYnVub3YiLCJleHAiOjE2ODk0MjMxNzcsImlhdCI6MTY4NDIzOTE3N30.U_Ok2fmOFEQGhc_xY-rulOs7bPHlpNgzsaS2TDb5mTY"
    }
}

<=============================>

2) POST (https://blog.kata.academy/api/users/login/):
{
  "user": {
    "email": "gorbunov-city@mail.ru",
    "password": "aezakmi"
  }
}
Response: 
{
    "user": {
        "username": "sergeigorbunov",
        "email": "gorbunov-city@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0NjM3MjI5NjBjNjc1MWIwMGI3NzQyMiIsInVzZXJuYW1lIjoic2VyZ2VpZ29yYnVub3YiLCJleHAiOjE2ODk0MjMxNzcsImlhdCI6MTY4NDIzOTE3N30.U_Ok2fmOFEQGhc_xY-rulOs7bPHlpNgzsaS2TDb5mTY"
    }
}

<=============================>

3) GET (https://blog.kata.academy/api/user):
Bearer Token: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0NjM3MjI5NjBjNjc1MWIwMGI3NzQyMiIsInVzZXJuYW1lIjoic2VyZ2VpZ29yYnVub3YiLCJleHAiOjE2ODk0MjMxNzcsImlhdCI6MTY4NDIzOTE3N30.U_Ok2fmOFEQGhc_xY-rulOs7bPHlpNgzsaS2TDb5mTY
Response:
{
    "user": {
        "username": "sergeigorbunov",
        "email": "gorbunov-city@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0NjM3MjI5NjBjNjc1MWIwMGI3NzQyMiIsInVzZXJuYW1lIjoic2VyZ2VpZ29yYnVub3YiLCJleHAiOjE2ODk0MjM0NDMsImlhdCI6MTY4NDIzOTQ0M30.LkKS7OAChS8FWVFXstNzIaYskoTeszQ55gToeNdw200"
    }
}

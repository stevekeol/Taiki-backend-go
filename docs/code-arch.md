# Code Arch

## The Complete Project Folder Structure

```yaml title=""
.
├── Dockerfile: Docker配置文件
├── api: 
│   ├── controller: 
│   │   ├── login_controller.go: 
│   │   ├── profile_controller.go: 
│   │   ├── profile_controller_test.go: 
│   │   ├── refresh_token_controller.go: 
│   │   ├── signup_controller.go: 
│   │   └── task_controller.go: 
│   ├── middleware: 
│   │   └── jwt_auth_middleware.go: jwt授权中间件
│   └── route: 
│       ├── login_route.go: 
│       ├── profile_route.go: 
│       ├── refresh_token_route.go: 
│       ├── route.go: 
│       ├── signup_route.go: 
│       └── task_route.go: 
├── bootstrap: 
│   ├── app.go: 
│   ├── database.go: 
│   └── env.go: 
├── cmd: 
│   └── main.go: 
├── docker-compose.yaml: 
├── domain: 
│   ├── error_response.go: 
│   ├── jwt_custom.go: 
│   ├── login.go: 
│   ├── profile.go: 
│   ├── refresh_token.go: 
│   ├── signup.go: 
│   ├── success_response.go: 
│   ├── task.go: 
│   └── user.go: 
├── go.mod: 
├── go.sum: 
├── internal: 
│   └── tokenutil: 
│       └── tokenutil.go: 
├── mongo: 
│   └── mongo.go: 
├── repository: 
│   ├── task_repository.go: 
│   ├── user_repository.go: 
│   └── user_repository_test.go: 
└── usecase: 
    ├── login_usecase.go: 
    ├── profile_usecase.go: 
    ├── refresh_token_usecase.go: 
    ├── signup_usecase.go: 
    ├── task_usecase.go: 
    └── task_usecase_test.go: 
```
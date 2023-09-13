# The purpose of the repository
I'll store the output and memo through the journey of [the course](https://www.udemy.com/course/nestjs-zero-to-hero/).
I'll review them in the future when I face some challenges while developing products with NestJS.

In the repository, I'll use v10.1.11 of NestJS while v7 in the Udemy course. I'll change some codes for v10 when I need it.

# Task Management
## Section1
```
yarn global add @nestjs/cli
nest -v
```

## Section2
```
nest new nestjs-task-management
nest g module tasks
nest g controller tasks --no-spec
nest g service tasks --no-spec
yarn add uuid
```

## Section3
```
yarn add class-validator class-transformer
```

## Section4
```
docker run --name postgres-nest -p 5432:5432 -e POSTGRES_PASSWORD=postgres -d postgres
yarn add typeorm @nestjs/typeorm pg
yarn remove uuid
```
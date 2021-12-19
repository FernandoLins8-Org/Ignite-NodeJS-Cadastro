# Tests

## User model

[x] - should be able to create an user with all props

## UsersRepository

[x] - should be able to create new users

[x] - should be able to list all users

[x] - should be able to find user by ID

[x] - should be able to find user by e-mail address

[x] - should be able to turn an user as admin

## CreateUserUseCase

[x] - should be able to create new users

[x] - should not be able to create new users when email is already taken

## TurnUserAdminUseCase

[x] - it should be able to turn an user as admin

[x] - it should not be able to turn a non existing user as admin

## ShowUserProfileUseCase

[x] - it should be able to get user profile by ID

[x] - should not be able to show profile of a non existing user

## ListAllUsersUseCase

[x] - it should be able to list all users

[x] - should not be able to a non admin user get list of all users

[x] - should not be able to a non existing user get list of all users

## routes.spec.ts
[x] - should be able to create new users

[x] - should not be able to create new users when email is already taken

[x] - should be able to turn an user as admin

[x] - should not be able to turn a non existing user as admin

[x] - should not be able to show profile of a non existing user

[x] - should be able to list all users

[x] - should not be able to a non admin user get list of all users

[x] - should not be able to a non existing user get list of all users

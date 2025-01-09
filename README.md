### Used Packages:
1. Gin Framework
2. Postgres
3. GORM
4. Golang JWT (https://github.com/golang-jwt/jwt)
5. Godotenv (https://github.com/joho/godotenv)
6. Validation (https://github.com/go-playground/validator)
7. Slug (https://github.com/gosimple/slug)

### Steps to follow
1. Clone the repo
2. Run the command `go mod download`
3. Rename the .env.example file to .env 
4. Create a database in postgres 
5. Change the DNS value in .env file 
6. Run the command `go run db/migrate/migrate.go` (Drop existing tables and recreate those)
7. Check your database, tables should be available
8. Run the project using the command `go run main.go`
9. Test the application in Postman

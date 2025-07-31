# shopping-cart
Shopping Cart is a fullstack e-commerce web application built to simulate a basic online shopping experience for users. It provides a complete flow: from user registration/login, to browsing products, to adding items to a cart, and finally placing orders.
 1.Backend Setup (Golang)
cd backend
go mod tidy
go run main.go

2.Frontend Setup (React)
cd frontend
npm install
npm start

3.Auth Token Handling
After login, the JWT token is stored in localStorage.
Token is sent in the Authorization header as:
Authorization: Bearer <token>

4.If you're using Ginkgo for tests:
go install github.com/onsi/ginkgo/v2/ginkgo@latest
ginkgo ./...

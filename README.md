# Tattoo Tattle

## Welcome to Tattoo Tattle!

### There are two modes in the site:

### In the artist mode you can:

1. Add Tattoos
2. Display your tattoos
3. Approve or deny requests

### In the client mode you can:

1. View tattoos
2. Filter based on location, price, and style
3. Add and view requests on tattoos that you liked

### Instructions:

1. Git clone the repo
2. Run "npm i" to download all node modules and dependencies
3. Run "npx prisma migrate reset" to seed the database for the first viewing 
4. On a terminal session run the command "npx nodemon" to start up the prisma servers
5. On a separate terminal run "npm run dev" to start up the app
6. Create an account/log in and explore the tattoo tattle site!

### Technologies used:

1. React
2. React Router
3. Material UI
4. Firebase (image storage)
5. Prisma ORM 
6. Express JS
7. Bcrypt (password safety)
8. JWT authentication 

### Future updates:

1. Loading cards when waiting for fetch; empty card display

### Changes from previous versions:

1. Tattoo Tattle now implements a real backend, which uses Prisma 
2. Tattoo Tattle now implements authentication and authorization through the use of JWT tokens 

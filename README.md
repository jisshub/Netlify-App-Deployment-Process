# Steps to Deploy App to Netlify

## 1. Stop the server, then run below command 

```bash
npm run build
```

- Creates a **build/dist** folder in our project directory.

## 2. Serve the production build, Install serve package globally

```bash
npm i -g serve
```

## 3. Serve the build/dist folder

```bash
serve -s build
```

        Or

```bash
serve -s dist
```

- It serves our app on our **localhost:3000** or **localhost:5000**.

- We can see the production build of our app in localhost.

## 4. Finally we deploy the app to netlify

- First create a github remote repo and push all the changes to the same.
- Login to netlify, click the ne**w site from the git** button.
- Choose **Github**
- Select our repository from the list.
- Click the **Deploy Site** button.











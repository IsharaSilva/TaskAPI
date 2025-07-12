get - http://localhost:8080/api/tasks
post - http://localhost:8080/api/tasks
 {
    "title": "Task 3",
    "description": "Do something 3",
    "completed": true
  }

get by Id - http://localhost:8080/api/tasks/4
put - http://localhost:8080/api/tasks/4
delete- http://localhost:8080/api/tasks/4

run git commands
after create repo, then first take git pull then,
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main

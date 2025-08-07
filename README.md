Step-by-Step Workflow
1️⃣ Clone the Project
git clone https://github.com/Kishorecloud7/jenkins-repo.git

2️⃣ Review the Application Code
app.js
const http = require("http");
const port = 3000;

const server = http.createServer((req, res) => {
  res.statusCode = 200;
  res.end("Hello from Jenkins CI/CD Pipeline!");
});

server.listen(port, () => {
  console.log(`Server running at http://localhost:${port}/`);
});

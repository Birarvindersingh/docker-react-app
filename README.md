<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
</head>
<body>

  <h1>🐳 Dockerize and Run a React Web App</h1>

  <p>This project demonstrates how to create a simple React application using Vite, containerize it with Docker, run it locally, and push the image to DockerHub for portability and reuse.</p>

  <h2>🚀 Project Overview</h2>
  <ul>
    <li>Create a simple React app using Vite</li>
    <li>Write a Dockerfile to containerize the application</li>
    <li>Build and run the app locally using Docker</li>
    <li>Define a multi-container setup using Docker Compose</li>
    <li>Push the Docker image to DockerHub</li>
  </ul>

  <h2>🛠️ Technologies Used</h2>
  <ul>
    <li>React (with Vite)</li>
    <li>Docker</li>
    <li>Docker Compose</li>
    <li>Nginx (for production build)</li>
    <li>DockerHub</li>
  </ul>

  <h2>📦 Docker Commands Summary</h2>
  <ul>
    <li><code>docker build -t docker-react-app .</code> – Build Docker image</li>
    <li><code>docker run -d -p 8080:80 docker-react-app</code> – Run container</li>
    <li><code>docker tag docker-react-app bir23/docker-react-app</code> – Tag image for DockerHub</li>
    <li><code>docker push bir23/docker-react-app</code> – Push to DockerHub</li>
  </ul>

  <h2>📸 Project Screenshots</h2>
  <img src="https://github.com/Birarvindersingh/docker-react-app/blob/main/1.PNG" alt="Screenshot 1" width="500" />
  <img src="https://github.com/Birarvindersingh/docker-react-app/blob/main/2.PNG" alt="Screenshot 2" width="500" />
  <img src="https://github.com/Birarvindersingh/docker-react-app/blob/main/3.PNG" alt="Screenshot 3" width="500" />
  <img src="https://github.com/Birarvindersingh/docker-react-app/blob/main/4.PNG" alt="Screenshot 4" width="500" />
  <img src="https://github.com/Birarvindersingh/docker-react-app/blob/main/5.PNG" alt="Screenshot 5" width="500" />
  <img src="https://github.com/Birarvindersingh/docker-react-app/blob/main/6.PNG" alt="Screenshot 6" width="500" />
  <img src="https://github.com/Birarvindersingh/docker-react-app/blob/main/7.PNG" alt="Screenshot 7" width="500" />
  <img src="https://github.com/Birarvindersingh/docker-react-app/blob/main/8.PNG" alt="Screenshot 8" width="500" />
  <img src="https://github.com/Birarvindersingh/docker-react-app/blob/main/9.PNG" alt="Screenshot 9" width="500" />
  <img src="https://github.com/Birarvindersingh/docker-react-app/blob/main/10.PNG" alt="Screenshot 10" width="500" />

  <h2>🐳 DockerHub Link</h2>
  <p>View the pushed Docker image here:</p>
  <p>🔗 <a href="https://hub.docker.com/r/bir23/docker-react-app" target="_blank">DockerHub Repository: bir23/docker-react-app</a></p>

</body>
</html>

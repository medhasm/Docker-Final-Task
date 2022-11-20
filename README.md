
# Final Task In Docker

Create a Python Web APP using FLASK that:  
● Presents the Current BitCoin Price (LIVE)  
● Stores the price in a Redis Database  
● Presents the Average Price for the last 10 minutes (LIVE) 

## Run Locally

Clone the project

```bash
  git clone https://github.com/mohamadassi173/Docker-Final-Task.git
```

Go to the project directory

```bash
  cd Docker-Final-Task
```

Build

```bash
  docker compose up
```

Run

```bash
  http://127.0.0.1:8000/
```





## DockerHub

Run the image from DockerHub

```bash
  docker pull medhasm/bitcoin-flask
  docker run -d -p 8000:5000 medhasm/bitcoin-flask:latest
```
<img width="932" alt="img" src="https://user-images.githubusercontent.com/57920502/202924413-8942aae2-45cb-4555-803c-e1ddbb127f2a.png">


## Jenkins 
CI/CD that creates and pushes the generated Web application Docker image to Docker Hub  
<img width="662" alt="image" src="https://user-images.githubusercontent.com/57872327/177614069-498a87bc-2dd5-4874-a033-b08495668615.png">




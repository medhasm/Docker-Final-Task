
# Final Task In Docker

Create a Python Web APP using FLASK that:  
● Presents the Current BitCoin Price (LIVE)  
● Stores the price in a Redis Database  
● Presents the Average Price for the last 10 minutes (LIVE) 

## Run Locally

Clone the project

```bash
  git clone https://github.com/medhasm/Docker-Final-Task.git
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
<img width="541" alt="img" src="https://user-images.githubusercontent.com/57920502/202924851-becdcf64-489b-476e-b4e6-ed7d5ea33d08.png">







# Go URL shortner from youtube tutorial [here](https://www.youtube.com/watch?v=bTLQT7W12dQ)

## Running

`docker-compose up --build`

#### Note: You'll need to insert something into the database before the "New" modal will work. I dont know why... 

POST to `http://localhost:3000/goly` with
```json
{
    "redirect": "https://go.dev/",
    "goly": "go-is-cool",
    "random": true
}
```
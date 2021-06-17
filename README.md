# SummerScoolK8s
Repo made for Syntio summer school. It contains simple nginx hello world web app with a dockerfile.

Docker needs to be installed on host machine to use this repo.

### Tutorial:
1. Clone the repo
2. Build the image (cd into repo and run `docker build . -t nginx)
3. Run the image (docker run -p 8000:80 -t nginx)
4. Connect to server (type in browser localhost:8000)

Congratulations!
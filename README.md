# ReadmeTest

# TV series Recommendation System

A fully containerized application that runs on docker containers and returns TV Series recommendations based on overview, genre, and cast. Additional filters such as certificate and series status can also be used.

## Requirements

1. Latest Stable version of Docker Engine

    Find full documentation of requirements and supported OS [here.](https://docs.docker.com/engine/install/)

2. Latest Stable version of Docker-compose

## Installing Requirements
If you already have Docker and Docker-compose installed you can skip directly to running the application.

### For Ubuntu (Linux based systems)
Open a Terminal and type the following commands:-

1. Update 
```bash
sudo apt-get update
```
2. Install Docker 
```bash
sudo apt-get install docker.io
```
3. Start Docker
```bash
sudo systemctl restart docker
```
4. Check if Docker is running
```bash
sudo systemctl status docker
```
5. Enable Docker
```bash
sudo systemctl enable docker
```
6. Install Docker-Compose
```bash
sudo apt install docker-compose
```
7. If any of the commands failed, try running the update command and then running the failed command
```bash
sudo apt-get update
```

### For Windows

1. Visit the [Docker](https://www.docker.com/) Website

2. On the Top right of the screen click on Get Started.

3. Download the Docker Desktop version for Windows.

4. Once downloaded execute the file and follow the prompt, Restart when required (Note: make sure to enable/select [WSL2](https://docs.microsoft.com/en-us/windows/wsl/about) option, it is selected by default)

5. No need to install Docker-compose as it comes bundled with Docker Desktop

## Running the application
### Before running the application run the following command to install Git

1. For windows you can download from [here.](https://git-scm.com/download/win)

2. For Ubuntu you can run the following command in terminal
```bash
sudo apt-get install git
```
### Make a directory where you want the application to download and open the terminal/cmd from inside the directory

1. Once we have git installed we can run the following command on the terminal(ubuntu) or cmd(windows) from inside that directory. (Note : Might need to add 'sudo' in front of the command for ubuntu)
```bash
git clone https://github.com/Jaishankar619/TV_Series_recommendation.git
```

2. Once the repository is downloaded type the following command
```bash
cd TV_Series_recommendation/
```

3. For Ubuntu type the following to launch the app 
```bash
sudo docker-compose up --build
```
4. For windows type the following to launch the app 

```bash
docker-compose up --build
```

5. Once the build is complete and the containers are running you can visit the following [link](https://127.0.0.1:5000) to view the application or open a browser and type 127.0.0.1:5000 in address bar.



## Usage

Coming soon ...
```python

Coming soon...
```

## License
[MIT](https://choosealicense.com/licenses/mit/)

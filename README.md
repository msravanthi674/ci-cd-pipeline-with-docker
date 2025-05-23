#  Local CI/CD Pipeline with Docker and GitHub Actions

This project demonstrates a complete local CI/CD pipeline using:

- Docker
- GitHub Actions
- [`act`](https://github.com/nektos/act) to simulate GitHub workflows locally

## Features

- Builds a Docker image for Nginx
- Serves a custom HTML page
- Uses GitHub Actions to automate build, run, and test
- Can be run locally using `act` to simulate cloud CI/CD

## Run It Locally

```bash
git clone https://github.com/your-username/docker-nginx-ci.git
cd docker-nginx-ci
act push

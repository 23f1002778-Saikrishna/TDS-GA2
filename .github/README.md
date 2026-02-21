# Q9 Solution: Docker Hub Image (via GitHub Actions)

## Objective
Create and push a Docker image to Docker Hub with a specific tag.

## Important Note
**Local Docker execution is not possible in this environment.**
Therefore, this repository includes a GitHub Action to perform the build and push automatically.

## How to Deploy

1.  **Push this code** to your GitHub repository: `(https://github.com/23f1002778-Saikrishna/TDS-GA2/edit/main/.github)`.
2.  **Go to Settings -> Secrets and variables -> Actions** in your GitHub repository.
3.  Add the following **Repository secrets**:
    -   `DOCKER_USERNAME`: Your Docker Hub username (`soiboie`).
    -   `DOCKER_PASSWORD`: Your Docker Hub access token (or password).
4.  **Trigger the Workflow**:
    -   Go to the **Actions** tab.
    -   Select **Docker Image CI**.
    -   Click **Run workflow**.

## Result
Once the workflow completes, the image will be available at:
`(https://hub.docker.com/repository/docker/soiboie/tds/general?secret=<your_token_here>&identifier=soiboie)`

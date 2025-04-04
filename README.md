# sit737-2025-prac5p

Part I

Step 1: Installed Docker Desktop
Step 2: Clone previous task (4.2c) files into new repo
Step 3: Create the dockerfile in vsc
Step 4: Copy the dockerfile in workshop recording
Step 5: Build the docker image "docker build -t calculator"
Step 6: Fill out docker-compose.yml using recording as example
Step 7: Modify the content to fit (port number & removal of command)
Step 8: Test it by running "docker compose up"
Step 9: Test localhost:3000 and the different endpoints
Step 10: After working, push Docker image to registry
Step 11: Put a tag on the image "docker tag"
Step 12: Push the image to registry "docker push"

Part II

Step 1: Search on how to add health checks
Step 2: I used "https://www.warp.dev/terminus/docker-compose-health-check" this as my base
Step 3: Create the healthcheck for the container
Step 4: Placed option to have automatic check every 30 seconds
Step 5: Placed option to maximize each checks up to 10 seconds (more than that will be considered a failure)
Step 6: Placed option an amount of retries "3" before declaring the container as 'unhealthy'
how to build CI/CD pipline in simple way:

we need three components:
GitHub ->jenkins->Dockerhub

![img.png](img.png)

To summarize, we have three main steps:
1. Upload the code to GitHub.
2. Create a project in Jenkins and enter the GitHub and Docker Hub credentials.
Jenkins will automatically build the image and push it for you to the Docker Hub
account. When you push the code to GitHub, Jenkins automatically detects, tests,
and builds the image. If no errors are generated, Jenkins pushes the image to
the registry.
3. Verify that the image is on your Docker Hub account.



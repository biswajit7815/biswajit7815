<h1 align="center">Hi 👋, I'm Biswajit Behera</h1>
<h3 align="center"><h3 align="center"> 🚀 DevOps & Cloud Engineer | AWS | Docker | Kubernetes | CI/CD | Terraform </h3></h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=biswajit7815&label=Profile%20views&color=0e75b6&style=flat" alt="biswajit7815" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=biswajit7815" alt="biswajit7815" /></a> </p>

<p align="left"> <a href="https://twitter.com/" target="blank"><img src="https://img.shields.io/twitter/follow/?logo=twitter&style=for-the-badge" alt="" /></a> </p>

- -->This project demonstrates a fully automated DevOps workflow — from development to deployment using Jenkins Declarative Pipeline integrated with Docker and AWS EC2. Development Phase (Code Creation & Version Control) -->Actors: Developer, GitHub -->The developer writes and tests the Django application code locally. -->Once ready, the code is pushed to a GitHub repository. -->GitHub acts as the central version control system, maintaining all commits and branches. CI/CD Automation (Jenkins): -->Tool: Jenkins -->Jenkins is configured with a webhook linked to GitHub. -->Whenever new code is pushed, GitHub triggers Jenkins automatically. -->Jenkins runs a Declarative Pipeline (Jenkinsfile) which defines the entire build → test → deploy flow. Jenkins Pipeline performs:  Continuous Integration (CI)  Pulls the latest code from GitHub.  Builds and tags a Docker image of the Django application.  Runs tests and linting (if configured).  Continuous Deployment (CD)  Pushes the built image to Docker Hub.  Connects to the AWS EC2 instance via SSH and pulls the latest Docker image.  Stops any running container and deploys the updated container automatically. Containerization Phase Tools: Docker, Docker Hub • Jenkins uses Docker to build a lightweight image of the Django app. • The image contains all dependencies (python, Django, requirements.txt, etc.). • The image is tagged (for example my-notes-app:v1.0) and pushed to Docker Hub, serving as a central image registry. Deployment Phase Tool: AWS EC2 • The EC2 instance acts as the deployment server. • Jenkins or a manual process pulls the Docker image from Docker Hub onto the EC2 instance. • A container is created and run using: docker run -d -p 8000:8000 biswajit7815/my-notes-app:latest The application is now live and accessible via \http://<your-ec2-public-ip>:8000 Pipeline Type It defines stages such as: -->Checkout Code -->Build Docker Image -->Push Image to Docker Hub -->Deploy to EC2 [https://app.eraser.io/workspace/hW3KemzTybaVmPMvQzBs](https://github.com/biswajit7815/django-notes-app)

- 🌱 I’m currently learning **Advanced Terraform, AWS services, and Infrastructure as Code (IaC)** to enhance automation and scalability.**

- 🔭 I’m completed the project { Tech Stack } --> {its very important for flow the deployment } [[[ pull the github repo --> created the docker file --> build the docker --> push to my dockerhub (biswajit7815) --> created the yml file like (pv ,pvc ,frontend , backend , service , deployment ,namwspace ,ect) --> then kubectl apply -f <yml file name > ---> after i will port-forwarding all the deployment.yml (like backend , frontend , database ) ---> then access the ip address then it will work properly ]]]]] Successfully Deployed a 3-Tier Full-Stack Chat Application on Kubernetes! I’m excited to share that I’ve completed the deployment of a full-stack Chat Application using Kubernetes. 🔹 Architecture Overview: Frontend: React.js (containerized and deployed as a Kubernetes Deployment) Backend: Node.js with Express (handles real-time messaging and APIs) Database: MongoDB (stateful component managed within the cluster) 🔹{ What I Did: } Created Docker images for each tier (frontend, backend, database). Wrote Kubernetes yml files like -->Deployments, Services, and Namespace. like K8s . Configured Minikube to run the cluster locally. Verified communication between pods using internal cluster networking. Tested full functionality — then put my credentials and created a user account, logged in successfully, and verified data stored in MongoDB. [full-stack-chat](https://github.com/biswajit7815/full-stack_chatApp)

- 👨‍💻 All of my projects are available at [https://github.com/biswajit7815](https://github.com/biswajit7815)

- 📝 I regularly write articles on [DevOps best practices, Cloud Automation, and CI/CD implementation](DevOps best practices, Cloud Automation, and CI/CD implementation)

- 💬 Ask me about **Docker, Kubernetes, Jenkins, AWS, CI/CD Pipelines, and Cloud Automation**

- 📫 How to reach me **biswajitbehera1868@gmail.com**

- 📄 Know about my experiences [https://github.com/biswajit7815/biswajit7815/blob/main/Biswajit_behera_cv.pdf](https://github.com/biswajit7815/biswajit7815/blob/main/Biswajit_behera_cv.pdf)

- ⚡ Fun fact **I believe in “Automate Everything” — if it can be scripted, it should be.**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/www.linkedin.com/in/biswajit-behera-1b564031a" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="www.linkedin.com/in/biswajit-behera-1b564031a" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://grafana.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/grafana/grafana-icon.svg" alt="grafana" width="40" height="40"/> </a> <a href="https://www.jenkins.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/> </a> <a href="https://kubernetes.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

<h3 align="left">Support:</h3>
<p><a href="https://www.buymeacoffee.com/biswajit behera"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="biswajit behera" /></a><a href="https://ko-fi.com/biswajit behera"> <img align="left" src="https://cdn.ko-fi.com/cdn/kofi3.png?v=3" height="50" width="210" alt="biswajit behera" /></a></p><br><br>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=biswajit7815&show_icons=true&locale=en&layout=compact" alt="biswajit7815" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=biswajit7815&show_icons=true&locale=en" alt="biswajit7815" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=biswajit7815&" alt="biswajit7815" /></p>

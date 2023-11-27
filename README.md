#  Dockerized and Deployed 2048 Game project to AWS Elasticbeanstalk

here we have small clone of 2048 game . The official app can also be found on the [Play Store](https://play.google.com/store/apps/details?id=com.gabrielecirulli.app2048) and [App Store!](https://itunes.apple.com/us/app/2048-by-gabriele-cirulli/id868076805)

<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/1175750/8614312/280e5dc2-26f1-11e5-9f1f-5891c3ca8b26.png" alt="Screenshot"/>
</p>

### Project 

 This GitHub repository houses the complete code of the 2048 game and Dockerfile for deploying the game on AWS Elastic Beanstalk. the Dockerfile, utilizing Ubuntu 22.04 as the base image , includes installations of essential utilities such as ZIP and Nginx, enhancing the overall performance of the game. I have deployed the game to AWS Elasticbeanstalk. An IAM role, 'aws-elasticbeanstalk-ec2-role,' is created to grant necessary permissions to EC2 instances, facilitating a secure and controlled environment.

 Key Features:

    Docker Containerization: The game is containerized using a Docker file, making it portable and easy to deploy across different environments.
    AWS Elastic Beanstalk Deployment: Utilizing the Elastic Beanstalk service, the Docker container is seamlessly deployed on AWS, providing a scalable and managed environment.
    IAM Role Configuration: The project incorporates the creation and configuration of an IAM role, specifically 'aws-elasticbeanstalk-ec2-role,' ensuring secure and granular permissions for the EC2 instances running the game

How to Use:

    Clone the Repository: Get started by cloning this repository to your local machine. you can get the game code from this repo.

    Docker Build and Run: Try to Write and Execute the Docker file to build the image and run the Docker container locally.

    AWS Deployment: Learn to configure AWS Elastic Beanstalk Web application deployment. configure & specify the required IAM roles.

## Contributing
Changes and improvements are more than welcome! Feel free to fork and open a pull request.
for any queries related to project reach me on nusairtech@gmail.com


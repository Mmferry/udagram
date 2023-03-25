# Pipeline Process

The pipeline is setup and connected with this GitHub repository in CircleCI.

## Order of commands

1. The pipeline uses orbs to install Node, AWS cli and ElasticBeanstalk cli.
2. It checks out the code from the repo
3. FrontEnd & BackEnd install (Saves dependency cache for next time)
4. FrontEnd lint
5. FrontEnd & BackEnd build
6. FrontEnd & BackEnd deploy
7. Hold the process until take approval
8. Install EB CLI
9. Configure AWS credentials
10. Deploy to Elastic Beanstalk

![Infrastructure Schema](../screenshots/pipline_digram.drawio.png)

# DockerSeleniumStandalone

# Created a basic test file using Maven with selenium java

" What I have done in this project: "

*Step1: I have pulled the image from the Docker hub, using the following command*

  _docker pull selenium/standalone-chrome_
  
*Step2: I have run that image to create a container, using the following command*

  _docker run -d -p 4444:4444 -v /dev/shm:/dev/shm selenium/standalone-chrome:latest_

*Step3: I have created a new project in the intellij and run my sample test code in the docker by running the following command*

  _DesiredCapabilities cap = DesiredCapabilities.chrome();_

  _RemoteWebDriver driver = new RemoteWebDriver(url, cap);_

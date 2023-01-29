# TrackMyAppointment
An open source web application that tracks appointments

# Install Instructions
You need the following pre-requisites installed on your machine to install TrackMyAppointment:
1. [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) - Used to download the source code from this repository
2. [Java and Apache Maven](https://maven.apache.org/install.html) - Used to build the Java package file from the source code
3. [Docker](https://www.docker.com/) - Used to automatically configure the environment

Once you have the pre-requisites installed follow these instructions:
1. In the command line, navigate to the folder you wish to install TrackMyAppointment to
2. Clone this repository using git: `git clone https://github.com/JBetts97/TrackMyAppointment`
3. Move into the directory that is created: `cd /TrackMyAppointment`
4. Build the java package file from source code: `mvn clean package`
5. Build the docker image from the dockerfile: `docker build -t track-my-appointment .`
6. Run the docker image and bind port 8080: `docker run -p 8080:8080 -d track-my-appointment`
7. That's it! The application should now be accessible in a web browser at: `localhost:8080`

# Contribution and Development Configuration
Feel free to contribute to this software! I highly appreciate all contributions no matter how big or small. <br>
You can find details on how to setup a developer environment at `/Helpers/DeveloperGuide.md`
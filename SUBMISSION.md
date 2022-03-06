# HW8 - Docker
Tyler Reed - treed20

Added my screen captures to a directory called [images/hw8](images/hw8).

## Deliverables

###DOCKER
- Your dockerfile. Please provide a link to this file rather than a screen capture. <br>
[Dockerfile](images/hw8/)
- Your running docker instance as shown by a ps command. <br>
[docker-docker-ps.jpg](images/hw8/docker-docker-ps.jpg)
- Your browser accessing the main page of the website from your local container.<br>
[docker-browser.jpg](images/hw8/docker-browser.jpg)
###DOCKER COMPOSE - MYSQL ONLY
- The output from the docker-compose up command. <br>
[compose-sqlonly-compose-up.jpg](images/hw8/compose-sqlonly-compose-up.jpg)
- Your browser accessing the “Veterinarians” page of the website from your local container when you run the application from the host system. <br>
[compose-sqlonly-vets.jpg](images/hw8/compose-sqlonly-vets.jpg)
- A section of the stack trace generated when you attempt to run the application container that has been updated to use MySQL. <br>
[compose-sqlonly-err0.jpg](images/hw8/compose-sqlonly-err0.jpg) <br>
[compose-sqlonly-err0.jpg](images/hw8/compose-sqlonly-err6.jpg) <br>
[compose-sqlonly-err0.jpg](images/hw8/compose-sqlonly-err7.jpg) <br>
[compose-sqlonly-err0.jpg](images/hw8/compose-sqlonly-err8.jpg) <br>

###DOCKER COMPOSE - APP SERVER AND MYSQL
- Your updated docker-compose.yml file containing the application server, built from your local Dockerfile, and the existing MySQL configuration. Please provide a link to this file rather than a screen capture. <br>
[docker-compose.yml](docker-compose.yml)
- Your updated application-mysql.properties file containing the URL change for the database server. Please provide a link to this file rather than a screen capture. <br>
[application-mysql.properties](src/main/resources/application-mysql.properties)
- The output from the docker-compose up command. <br>
[compose-appsql-compose-up.jpg](images/hw8/compose-appsql-compose-up.jpg)<br>
[compose-appsql-compose-up2.jpg](images/hw8/compose-appsql-compose-up2.jpg)
- Your browser accessing the “Veterinarians” page of the website from your local container. <br>
[compose-appsql-browser-vet.jpg](images/hw8/compose-appsql-browser-vet.jpg)



# HW5 - Spring PetClinic CI
Tyler Reed - treed20

Added my screen captures to a new directory called [images](images).

## Deliverables
- Your GitHub account showing that is has been forked from the depaulcdm/springpetclinic repository. <br>
![GH-Forked](images/GH-Forked.jpg)
- Your GitHub Actions dashboard showing a successful first build. <br>
![Actions-Build-1-Arrow](images/Actions-Build-1-Arrow.jpg) <br>
![Actions-Build-1-Details](images/Actions-Build-1-Details.jpg)
- Your GitHub repository with the readme.md file selected showing the code that you changed to update the badge. <br>
![GH-Readme-Update](images/GH-Readme-Update.jpg) <br>
![GH-Readme-Update-raw](images/GH-Readme-Update-raw.jpg) 
- Your GitHub repository with the readme.md file selected showing the build success status after you’ve updated the badge markdown. <br>
![GH-Readme-Badge2](images/GH-Readme-Badge2.jpg)
- The section of the POM file showing the coordinates after you’ve commented them out. <br>
![GH-pom-diff.jpg](images/GH-pom-diff.jpg) <br>
![gh-pom-comments](images/gh-pom-comments.jpg)
- Your GitHub Actions dashboard showing the unsuccessful build after the breaking change. <br>
![gh-failed-build](images/gh-failed-build.jpg) <br>
![gh-failed-builled-details](images/gh-failed-builled-details.jpg)
- Your GitHub repository with the readme.md file selected showing the build failed status after the GitHub workflow fails. <br>
![gh-failed-badge](images/gh-failed-badge.jpg)
- The section of the POM file showing the coordinates after you’ve fixed them. <br>
![gh-corrected-pom](images/gh-corrected-pom.jpg) <br>
![gh-corrected-pom-diff](images/gh-corrected-pom-diff.jpg)
- Your GitHub Actions dashboard showing the successful build after the breaking change has been fixed. <br>
![gh-passed-build](images/gh-passed-build.jpg) <br>
![gh-passed-build-details](images/gh-passed-build-details.jpg)
- Your GitHub repository with the readme.md file selected showing the build success status after the GitHub workflow has recovered. <br>
![gh-passed-readme](images/gh-passed-readme.jpg)

# Practice task:

- Fork SimpleJ2EEProject
- Create git branch "newServlet"
- Create HttpServlet and map to "/" (use BaseHttpServlet which is in project) and commit changes
- Get instance of HelloWorldGenerator from context BaseHttpServlet.getBean() and print it in page (use htm page structure), commit
- Change HelloWorldGeneratorImpl hello text to "Hello world", commit
- Push changes to remote
- Checkout master
- Create new branch "newHelloText"
- Change HelloWorldGeneratorImpl hello text to "Hello visitor", commit
- Push changes to remote
- Checkout master
- Merge branch newHelloText to master, push
- Merge branch newServlet to master, push
- run "mvn package" and  Deploy web-app.war to tomcat
- Connect to tomcat debug port
- create breakpoint in servlet
- Change hello text from debug to "broken Hello"
- Show result to lecture


# Project manual
- copy setenv.bat to {tomcatDir}/bin to enable debug port 8000
- to create war artifact run "mvn package" (maven should be installed and configured)
 (https://www.mkyong.com/maven/how-to-install-maven-in-windows/)

# Lecture Materials
- Git lecture video https://www.youtube.com/watch?v=iJm0xflVz_8
- Lecture pptx files https://drive.google.com/drive/folders/0B4OuEuZP2SJYUTR4RjNNeXI3ZGM?usp=sharing
- Contact me andreydemosoft@gmail.com
- telegram chat https://t.me/joinchat/EY_wXQx2hyoLgYSerz8_qw

# SimpleJ2EEProject
Simple java 2 EE project fro TI karazin java course

- Set up GitHub account
- Import project
- Set up simple web project (1 servlet)
- Make commit/push
- Make branch/merge
- Debug Servlet"


https://start.spring.io/

# Practice task 2:

1. Dowload and Import new spring project
 1. Open https://start.spring.io/
 2. Select maven spring boot project with version 1.5.8
 3. Search for dependency named "Web" and add it
 4. Click Generate project
 5. Unzip
 6. Import as new maven project
7. 

# Devoir Servlet

## Prerequisites
- Java
- Apache Tomcat

## Usage
- git clone the project
- Copy `devoir-servlet.war` to `webapps` directory in Apache Tomcat
- In Apache Tomcat, navigate to the `bin` folder and run `startup.sh`
- Open `index.html` in your browser


- Click on the link
- 
![sevlet1](https://github.com/CarelleLoucas/devoir-servlet/assets/119422070/50fc7188-8b57-41d1-8988-c7c63bc1a3b2)


## Create WAR File
In the root of the project:
- Compile the `BonjourServlet.java` file with: `javac -d WEB-INF/classes -cp WEB-INF/lib/servlet-api.jar BonjourServlet.java`
- Generate the WAR file with: `jar -cvf devoir-servlet.war WEB-INF`

![servlet2](https://github.com/CarelleLoucas/devoir-servlet/assets/119422070/572059e7-fef0-46fe-836c-3c5743e131fc)

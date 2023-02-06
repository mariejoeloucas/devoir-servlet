# Devoir Servlet

## Prerequisites
- Java
- Apache Tomcat

## Usage
- git clone the project
- Copy `devoir-servlet.war` to `webapps` directory in Apache Tomcat
- In Apache Tomcat, navigate to the `bin` folder and run `startup.sh`
- Open `index.html` in your browser

![image](https://user-images.githubusercontent.com/101930339/217027803-8d097e32-dffa-4402-a0d7-9a2ee67853b1.png)

- Click on the link

![image](https://user-images.githubusercontent.com/101930339/217027841-5062965e-2bd2-4ce9-8117-46bc2aff23b4.png)


## Create WAR File
In the root of the project:
- Compile the `BonjourServlet.java` file with: `javac -d WEB-INF/classes -cp WEB-INF/lib/servlet-api.jar BonjourServlet.java`
- Generate the WAR file with: `jar -cvf devoir-servlet.war WEB-INF`

![image](https://user-images.githubusercontent.com/101930339/217028228-24947a43-4200-4739-8b5a-c6110ade8c9b.png)

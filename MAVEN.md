# MavenCentOS:

Maven is a build automantion tool. Used to Automate the build process. By using the Maven we can add the dependencies dynamically. 
We can make the Integration, Building, Testing and Documentation Contuniouslly.

Some of the Build automation tools like:

**1. Maven** used for Java, C#, Ruby, Scala Projects.

**2. Ant** used for Java Projects

**3. Gradle** used for Java, Android Projects

**4. NANT** used for the .Net Projects

**5. Pybuiler** used for the Python Projects

The Most important file in the Maven Projects is the **POM.XML** file. Maven is a Java based Application. Before installing the Maven into the CentOS platform. We need the Java that to be installed which is a pre-requisite.

1. To install the Java 1.8.0 using the command -------------------> **yum install java-1.8.0-openjdk**

![Java Installation in CentOS](https://user-images.githubusercontent.com/42949313/88607002-b964d200-d043-11ea-843f-180f3d874775.PNG)

2. To make the Java for all the projects using the command --------> **alternatives --config java**

![image](https://user-images.githubusercontent.com/42949313/88608081-86700d80-d046-11ea-8183-e9168c085df1.png)

3. To configure the Java using the command -----------------------> **vim .bashprofile**

Add the line **export JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk"**

![Java Environment Variables CentOS](https://user-images.githubusercontent.com/42949313/88609566-09df2e00-d04a-11ea-925c-0b7c99ffb9b5.PNG)

4. To verify the Java Environment Path setup ---------------------> **echo $JAVA_HOME**

![Java Configuration checking](https://user-images.githubusercontent.com/42949313/88609635-3d21bd00-d04a-11ea-908e-8fc9f7a97bb9.PNG)

5. To install Maven using the command ---------------------------> **yum install maven -y** or **yum install maven**

![Maven Installation in CentOS](https://user-images.githubusercontent.com/42949313/88609749-87a33980-d04a-11ea-9570-717b6c47cb35.PNG)

6. To find the maven installed version using the command --------> **mvn --version** or **mvn -version**

![Maven Vesion CentOS](https://user-images.githubusercontent.com/42949313/88609882-d0f38900-d04a-11ea-951a-30b94bb7c665.PNG)

7. To compile the Maven project using the command ----------------> **mvn compile**

8. To packge the Maven project using the command -----------------> **mvn package**

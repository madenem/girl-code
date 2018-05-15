# Girl Code - Build Your Own Bot

## Setup
Before you can start building your own bot, you will need to setup your environment.

### Java 8

1. Go to the Java download page - http://www.oracle.com/technetwork/pt/java/javase/downloads/jdk8-downloads-2133151.html
2. Accept the terms and conditions under **Java SE Development Kit 8u171**
3. Download the correct installation for you operating system.
4. Once the download has completed, double click the file and it will start the installation process.

### Maven
1. Create a folder in your C drive called `maven` (C:\maven)
2. Go to http://apache.is.co.za/maven/maven-3/3.5.3/binaries/apache-maven-3.5.3-bin.zip and select the `maven` folder you created
3. Right click the downloaded zip file and select Extract All.

### Visual Studio Code

1. Download VS Code at https://code.visualstudio.com/Download
2. You need to install the Java Extension Pack for Visual Studio Code as well. You can either download it from https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack, or you can follow the instructions at https://code.visualstudio.com/docs/editor/extension-gallery and search for "Java Extension Pack" in VS Code.

### Environment variables

**Please note:** The paths to the Java and Maven installations may differ depending on the version you downloaded. Make sure you use the correct paths for your machine.

1. In Windows, go to Control Panel and search for "enviroment".
2. Click on Edit the system environment variables
3. Click on the Environment Variables... button
4. You will see a `PATH` variable in the top block. Select the variable and click Edit.
5. Click the New button and paste the following path: `C:\maven\apache-maven-3.5.3-bin\apache-maven-3.5.3\bin`
6. Click OK.
7. Click the New button at the bottom of the window.
8. In the Variable Name input, type `JAVA_HOME`.
9. In the Variable Value, paste the following value: `C:\Program Files\Java\jdk1.8.0_171`
10. If your VS Code was open before you added the environment variables, you may have to close and open the application again.

### Bot Starter Pack
1. [Click here](https://github.com/madenem/girl-code/raw/master/starter-pack/starter-pack.zip) to download the bot starter pack.
2. Unzip the downloaded file.
3. Open VS Code, select File in the top left corner and then select Open Folder.
4. In the `starter-pack` folder, click on the `starter-bot` folder and then click Select Folder.
5. At the bottom left you should see a Maven Projects heading. Collapse this heading and then collapse starter-bot. Right click on java-sample-bot and select Package. If your environment has been setup correctly, you should see BUILD SUCCESS on the right in the Terminal window.

## Workshop slides
* [Java Basics](https://github.com/madenem/girl-code/raw/master/slides/Java%20Basics.pdf)
* [Introduction to Entelect Challenge](https://github.com/madenem/girl-code/raw/master/slides/Entelect%20Challenge%202018%20-%20Girl%20Code%20-%20Intro%20%2B%20Rules.pdf)
* [Build Your Own Bot - Setup](https://github.com/madenem/girl-code/raw/master/slides/Entelect%20Challenge%202018%20-%20Girl%20Code%20-%20Setup.pdf)
* [Build Your Own Bot - Activities](https://github.com/madenem/girl-code/raw/master/slides/Entelect%20Challenge%202018%20-%20Girl%20Code%20-%20Activities.pdf)

## Activity solutions
[Click here](https://github.com/madenem/girl-code/raw/master/starter-pack/starter-pack-solution.zip) to download the solutions to the activities.


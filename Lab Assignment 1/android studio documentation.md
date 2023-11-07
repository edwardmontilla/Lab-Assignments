#### Lab Assignment 1: Spinning Up React Native App


		 System Requirements: 

- Atleast 16GB of RAM
- 250GB of disk space
- Windows 10 or higher
- Visual Studio Code 2022 (optional)


		 Installing Dependencies

- You will need to install Node and the React Native command line interface

- Go to " https://nodejs.org/en " and install the latest version of LTS

- Follow the instructions to complete

- Now we'll install react in our system by typing " npm install -g create-react-app " in Windows PowerShell or a Command Line

		 Installation Instructions 

- Once everything has been set up, we'll need to install Android Studio

- Go to " https://developer.android.com/studio " and download Android Studio Giraffe

- Run the program and follow the instructions

		 Installing Tool Builds 

- After installing Android studio, open the the app and click "More actions" button then click on "SDK Manager".

- Tick on the box beside "Android 13.0 ("Tiramisu") and hit OK. This will install the Android 13.0 Tiramisu.

- After the installation, go back to SDK manager again and go to the "SDK Tools" tab. Tick the box next to "Show Package Details". Under Android SDK Build-Tool 34, make sure the box next to 33.0.0 is selected. 

- Hit Apply or OK to download.

		 Configuration Steps

- We'll configure the ANDROID_HOME environment table by accessing the Control Panel.

- Click on "User Accounts", then click "User Accounts" again.

- On the left hand side, click on "Change my environment variables".

- Click "New" and type "ANDROID_HOME" in the "Variable Name".

- Now go back to the Android Studio window and in the "Language & Frameworks" next to "Android SDK Location", copy the path and paste in the "Variable Value" just below Variable Name.

- Now we're going to open the Command Prompt window to verify the new environment variable is loaded.

- Open Windows Powershell.

- Copy and paste " Get-ChildItem -Path Env:\ " into powershell.

- Verify ANDROID_HOME has been added.

- Open the Control Panel once again and click User Accounts, then click User Accounts again.

- We'll on the left handside of the screen, click "Change my environment variables again.

- Select the "Path" variable and click "Edit".

- Click "New" and add the android sdk location but make sure to add " \platform-tools " at the end and hit OK.

		 Project Creation 

- Open a folder where you want to save the AwesomeProject file

- Click on the path of the folder and replace it with cmd and hit Enter

- Type " npm uninstall -g react-native-cli @react-native-community/cli "

- Then " npx react-native@latest init AwesomeProject "

- Wait for the download to finish then exit

		 Running the Project using File Explorer Path 

- Open the Project folder AwesomeProject

- Click on the file path and typ cmd again

- We will run this using " npm start "

- Just follow the steps and use the options given, for example when running the android mobile we choose " a "

- Wait for the application to turn on install its build

- A mobile emulator window should pop up with the welcome message " Welcome to React Native " 

		 Running the Project using Visual Studio Code 2022 

- Open Visual Studio Code

- Open the folder AwesomeProject

- At the top, click " Run -> New Terminal " if the terminal isn't aleady opened

- The terminal will open, run by typing " npm start "

- Just follow the steps and use the options given, for example when running the android mobile we choose " a "

- Wait for the application to turn on install its build

- A mobile emulator window should pop up with the welcome message " Welcome to React Native " 



		 Trouble Shooting / Resources 

- Now we'll delete any JDK or Java paths within the System Variables if there are any

- In the control panel, go to user accounts -> user accounts -> change my environment variables once again

- Go to System variables and click " Edit "

- Select " Path "

- Look for keywords containing "jdk" and/or "java", select and delete them

- Click ok

- Restart your computer and try running the project folder again




If you have trouble installing Node.js and npm follow this link:

	https://kinsta.com/knowledgebase/install-react/#windows-1

If you are denied access when editing Environment/System Variables, follow this link:

	https://superuser.com/questions/1467734/i-am-admin-but-i-cannot-edit-system-variables-windows-10

























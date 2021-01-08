# tasklist-app
A test repository while learning how to build an Android app using Expo


Credits:
https://code.tutsplus.com/tutorials/how-to-create-a-react-native-android-app--cms-35636

Installation of Needed Tools
1. Install Git
   * sudo apt-get install git-all
   * git version
2. Install Node.js
   * curl -sL https://deb.nodesource.com/setup_15.x | sudo -E bash -
   * sudo apt-get install -y nodejs
   * node -v
3. Install Expo Client to your computer
   * sudo  npm install expo-cli --global
   * expo --version
4. Install Expo App for Android to your phone

Building your first APK
1. Create a New Project With Expo
   * expo init nameOfYourApp
   >-The **expo init** command creates a project folder and installs all the dependencies required by the React Native app.  
   >-You will be prompted to choose a template for your project. For now, choose the **blank template**, which gives you minimal dependencies.  
   >-Afterwards, navigate to the project folder of your app, then start the Expo dev tools in that directory
   * cd nameOfYourApp
   * npm start
2. Open the Expo app on your phone and scan the QR Code shown on the terminal
3. Go to actual folder of your app `/home/PcUserName/nameOfYourApp` and look for **App.js**
4. Open **App.js** using your preferred code editor and modify the content of this file to suit your app design
   >-Each time you save the changes you made on this file, the outcome of your app will be shown real-time on the phone where Expo app was installed


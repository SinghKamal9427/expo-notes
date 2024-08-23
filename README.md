# expo-notes

GUIDE

Android 
Step1 - Clone the Repository:

git clone git@github.com:Maceforce/TheCraveCoach.git

After that, open the project in VSCode and change the branch to prebuilds.
git checkout prebuilds

Step2 - Remove the expo-updates Package:

Open package.json and remove "expo-updates" from the dependencies.
Run npm install 
Test the app by running npx expo start

Step3 - Open the Project in Android Studio:

Open the "android" folder in Android Studio.
Sync the project with Gradle files: Ctrl + Shift + O or through the menu File > Sync Project with Gradle Files.

Step4 - Change Build Variant:

Click on "Build Variants" from the sidebar.
Change "Active Build Variant" from debug (default) to release.

Step5 - Build the App:

Click on "Build" on the top navbar.
From the dropdown menu, click on "Build Bundle(s) / APK(s)" and choose either Build APK(s) or Build Bundle(s).

Alternative:
Open the project in VSCode, navigate to the android folder, and run the command: ./gradlew assembleRelease


IOS [Mac Required]
Step1 -Clone the Repository:

git clone git@github.com:Maceforce/TheCraveCoach.git

After that, open the project in VSCode and change the branch to prebuilds.

git checkout prebuilds

Step2 - Remove the expo-updates Package:

Open package.json and remove "expo-updates" from the dependencies.
Run npm install 
Test the app by running npx expo start

Step3 - Install CocoaPods:

    Navigate to the "ios"  cd ios   folder and run:
    pod install

Step4 -Open the Project in Xcode:

  Open the .xcworkspace file in Xcode:
  Configure and Build:
Ensure the correct signing and team are selected in Xcode settings.
Select a target device or simulator.
Click the "Run" button to build and deploy the app on the selected device or simulator

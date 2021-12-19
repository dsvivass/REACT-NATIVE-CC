# REACT-NATIVE-CC

To create a new project, we can use `react native CLI`, (read a comparison between **react native CLI** and **expo CLI** https://stackoverflow.com/questions/54862388/what-is-the-difference-between-expo-cli-and-react-native-cli), however, we'll use `expo CLI`.

If we were developing on Android, we would use something called *Android studio*. If we program on iOS we would use *XCode*. 

We are going to use **Expo**, so we don't have to worry about the whole installation process. We can see all documentation in https://docs.expo.dev/workflow/expo-cli/ .

+ To install expo-cli globally inside our project folder:

    ```
        npm install -g expo-cli
    ```

+ Once it is installed, we can create our project

    ```
        expo init <projectName>
    ```

    For this example we choose an empty template (We have the option when we run the above line of code)

    When everything id done, we could see some commands as follows:

    ```
        ✅ Your project is ready!

        To run your project, navigate to the directory and run one of the following npm commands.

        - cd react-native-cc
        - npm start # you can open iOS, Android, or web from here, or run them directly with the commands below.
        - npm run android
        - npm run ios # requires an iOS device or macOS for access to an iOS simulator
        - npm run web
    ```

    If we type `npm start` and we download the **Expo app** we will be able to see our app development live on our device, we could even share the app link to see it on other devices.
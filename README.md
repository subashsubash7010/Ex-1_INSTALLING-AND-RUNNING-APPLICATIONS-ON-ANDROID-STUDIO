# EX-1: INSTALLING AND RUNNING APPLICATIONS ON ANDROID STUDIO

**Name:** Subash M

**Register Number:** 212224220109

## Software Requirements
- Android Studio
- Android SDK
- Android Virtual Device (AVD)
- Java
- XML

---

## Step 1 – System Requirements

The required software tools are used to develop, design, and run Android applications. Android Studio provides the development environment, Java is used to implement application functionality, and XML is used to design the user interface.

### Required Software
- Android Studio
- Java Development Kit (JDK)
- Android SDK
- Android Emulator

---

## Step 2 – Setup Android Studio

Android Studio is the official Integrated Development Environment (IDE) used for Android application development.

### Installation Procedure
1. Download Android Studio from the official website.
2. Run the installer and follow the installation instructions.
3. Install the required Android SDK components.
4. Configure the Android SDK location.
5. Set up the Android Virtual Device if required.
6. Launch Android Studio.
7. Create a new Android project using the Empty Views Activity template.
8. Select Java as the programming language.

---

## Creating the Student Details Application

1. Open the project in Android Studio.
2. Design the user interface using the `activity_main.xml` file.
3. Add a heading named **STUDENT DETAILS**.
4. Add a button to reveal the student information.
5. Add a TextView to display the student name and register number.
6. Open the `MainActivity.java` file.
7. Initialize the Button and TextView using `findViewById()`.
8. Implement the button click event using `setOnClickListener()`.
9. Display the student information when the button is clicked.
10. Change the button text to **Details Revealed** after displaying the information.

---

## Step 3 – Create Android Virtual Device (AVD)

An Android Virtual Device is used to test and run the application without requiring a physical Android phone.

### Procedure
1. Open Device Manager in Android Studio.
2. Click **Create Virtual Device**.
3. Select a suitable device configuration.
4. Select and download an Android system image if required.
5. Finish the configuration and start the emulator.
6. Select the emulator from the device dropdown menu.

---

## Step 4 – Run the Application

1. Open the Student Details project.
2. Select the configured Android Emulator.
3. Click the **Run ▶** button in Android Studio.
4. Wait for the application to build and launch.
5. Verify that the Student Details screen appears.
6. Click the button to display the student information.

---

## Output

The application displays the heading **STUDENT DETAILS** and a button. When the button is clicked, the following details appear:

- **Name:** Subash M
- **Register Number:** 212224220109

The button text changes to **Details Revealed**.
<img width="1912" height="1131" alt="image" src="https://github.com/user-attachments/assets/4fc056c6-e3c3-4b34-b4b1-39f5ed784366" />




## Result

Thus, the Student Details application was successfully created and executed using Android Studio, and the student information was displayed by clicking the button.

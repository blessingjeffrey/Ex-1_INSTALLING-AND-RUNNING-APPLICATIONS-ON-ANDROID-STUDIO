# EX-1: INSTALLING AND RUNNING APPLICATIONS ON ANDROID STUDIO

**Name:** BLESSING JEFFREY YL

**Register Number:** 212223220014

## Software Requirements

- Android Studio
- Android SDK
- Android Virtual Device (AVD)
- Java
- XML

---

## Step 1 – System Requirements

The required software tools are used to develop, design, and run Android applications. Android Studio provides the development environment, Java is used to implement the calculator's functionality, and XML is used to design the user interface.

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

## Creating the To-Do List Application
1. Open the project in Android Studio.
2. Design the To-Do List interface using the activity_main.xml file.
3. Add an EditText to enter a new task.
4. Add a Button to insert the entered task into the To-Do List.
5. Add a TextView or RecyclerView to display the list of tasks.
6. Add buttons or checkboxes to mark tasks as completed.
7. Add a Delete button to remove tasks from the list.
8. Open the MainActivity.java file.
9. Initialize the required EditText, TextView, RecyclerView, and Buttons using findViewById().
10. Implement button click events using setOnClickListener().
11. Write the logic to add, display, update, and delete tasks.
12. Implement functionality to mark tasks as completed or pending.
13. Store the tasks using SQLite or SharedPreferences so that they remain available after closing the application.
14. Handle empty task inputs and invalid entries appropriately.

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
Open the TO-DO LIST project in Android Studio.
Select the configured Android Emulator.
Click the Run ▶ button in Android Studio.
Wait for the application to build and launch.
Verify that the To-Do List screen appears.
Enter a task in the input field.
Click the Add Task button to add the task to the list.
Verify that the newly added task is displayed correctly.
Test the checkbox to mark a task as completed.
Test the Delete button to remove a task from the list.
Verify that empty task inputs are handled appropriately.
Close and reopen the application to verify that saved tasks are retained.

---

## Output

<img width="1920" height="1080" alt="Screenshot 2026-11-02 082229" src="https://github.com/user-attachments/assets/b021446b-4697-4531-b2df-ae0bed4d1f0e" />



## Result

Thus, a To-Do List Android application was designed and implemented using Android Studio, Java, and XML. The application was successfully run on an Android Virtual Device, and its functionalities, including adding, displaying, updating, completing, and deleting tasks, were tested successfully.

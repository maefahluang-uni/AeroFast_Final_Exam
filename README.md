Name:  Thiha Lin
ID: 6631503092  
App Name: Aerofast  
FrameWork used: React Native  
GitHub Repository: [Click Here\!](https://github.com/6631503088/mobile_final_exam)  
APK/IPA: [Click Here\!](https://drive.google.com/file/d/1sUDa6YoZOlxB8GJ9G64CGcckDYOcBSmW/view?usp=sharing)  
—------------------------------------------------------------------------------------------------------------------  
**1.App Concept and Design**  
**1.1 User Personas**

Persona 1:

- Name: Mark

- Age: 25

- Occupation: Software Engineer

- Needs: Wants to track fitness progress and squeeze short workouts during breaks.

Persona 2:

- Name: Sarah

- Age: 20

- Occupation: University Student

- Needs: Needs guided daily routines to improve consistency and flexibility.

  **1.2 App Goals**

- Help users stay active and build a consistent fitness habit.

- Track user progress with steps, calories, workout time, and distance.

- Provide daily training programs including warm-up, cool-down, challenges, and stretching.

- Allow users to plan routines, monitor performance, and analyze history.


**1.3 Some main pages for mockup**  
Sign In / Sign Up Screen

- Supports email/password login and Google login.
- Simple and accessible UI for onboarding.

Home Screen

- Displays steps, calories burned, and today's training sessions.
- Suggests workout challenges like "Plank", "Chest", and "Burn 100 cal".

Plan Screen

- Workout programs with durations and reps (e.g., Bicep Curls, Triceps, Pull-ups).
- Displays assigned virtual coaches based on workout goals.

Profile Screen

- Personal info (Name, Gender, Height, Weight).
- Options to reset progress, manage coach, privacy policy, and logout.

Exercise Detail Screen

- Each program shows exercise name, duration, and instructions.
- Workout flow: Warm-up ➝ Core workout ➝ Cool-down.

**1.4 User Flow**

Open app ➔ Login or Register ➔ Browse pages and progress ➔ Select a workout ➔ Follow up Instructions ➔ Upgrade Progress with daily routines

—------------------------------------------------------------------------------------------------------------------  
**2.App Implementation**  
**2.1 Development Details**

- Tools used

  - react-native@0.79.1

  - Packages:

{
  "@react-navigation/native": "^6.1.17",
  "@react-navigation/stack": "^6.3.29",
  "@react-navigation/bottom-tabs": "^6.5.20",
  "@react-native-masked-view/masked-view": "^0.3.1",
  "@shopify/flash-list": "^1.6.4",
  "@shopify/restyle": "^2.4.4",
  "expo": "^52.0.46",
  "moment": "^2.30.1",
  "react": "18.2.0",
  "react-native": "0.74.1",
  "react-native-calendars": "^1.1305.0",
  "react-native-chart-kit": "^6.12.0",
  "react-native-circular-progress": "^1.4.0",
  "react-native-gesture-handler": "^2.16.1",
  "react-native-gifted-charts": "^1.4.10",
  "react-native-linear-gradient": "^2.8.3",
  "react-native-modal": "^13.0.1",
  "react-native-progress": "^5.0.1",
  "react-native-ruler-picker": "^0.2.2",
  "react-native-safe-area-context": "^4.10.1",
  "react-native-svg": "^15.2.0"
}


**2.2 Features Implemented**

- Checked list
  - User Authentication (Email, Password, Google Login) \=\> \[**YES**\]
  - Profile Management – Users can update gender, height, weight; reset or delete data \=\> \[**YES**\]
  - Detailed Exercise Plans – Each workout includes duration, reps/sets, and video guidance	 \=\> \[**YES**\]
  - Workout History & Calendar View – Users can review past workout activity	 \=\> \[**YES**\]
  - Bottom Tab Navigation – Seamless switching between Home, Plan, GPS, Analysis, and Profile \=\> \[**YES**\]

**2.3 App Screenshots**

**Sign In / Sign Up Screen:**
<img src="https://i.ibb.co/S7J6D30v/Screenshot-2025-04-30-19-39-16-26-48a9ae814f9b029943ae85085b7d6dfa.jpg" alt="Sign In / Sign Up" width="150"/>

**Home Page:**
<img src="https://i.ibb.co/5xzVzTWN/Screenshot-2025-04-30-19-35-19-46-48a9ae814f9b029943ae85085b7d6dfa.jpg" alt="Home Page" width="150/">

**Analysis Page:**
<img src="https://i.ibb.co/zWxhpMwd/Screenshot-2025-04-30-19-36-47-05-48a9ae814f9b029943ae85085b7d6dfa.jpg" alt="Analysis Page" width="150/">

**Workout Detail Page:**
<img src="https://i.ibb.co/q3T6Ys4Y/Screenshot-2025-04-30-19-35-49-14-48a9ae814f9b029943ae85085b7d6dfa.jpg" alt="Workout Detail" width="150/">

**Plan Page (Workout Lists):**
<img src="https://i.ibb.co/zgFWR2W/Screenshot-2025-04-30-19-43-45-72-48a9ae814f9b029943ae85085b7d6dfa.jpg" alt="Plan Page" width="150/">

—------------------------------------------------------------------------------------------------------------------

**3.Build|Deployment**

**3.1 Build Type**

- Debug \=\> \[**YES**\]

**3.2 Platform Tested**

- Android \=\> \[**YES**\]

**3.3 ReadMe and Install Guide**

- Download the .apk file.
- Open the file using your Android device.
- Install the app via the File Manager.

—------------------------------------------------------------------------------------------------------------------

**4\. Reflection**

- I also struggled with maintaining user sessions; the app would occasionally forget the login state after a restart.

- I learned how to use React Navigation and modularize UI components for better scalability

- If I had more time, I would implement Firebase for cloud sync and notification reminders.

—------------------------------------------------------------------------------------------------------------------

**5.AI Assisted Development**

**5.1 AI for Idea Generation**

Prompt used: "Give me mobile app idea related to fitness and workout with gps and tracking"

Result: Got the concept of daily fitness tracker with exercise log and calories burned.

**5.2 AI for UI Design**

Prompt used: "How to design bottom tab navigation ui for fitness app in react native""

Result:  Helped plan the layout with Home, Plan, GPS, Analysis, and Profile tabs.

- Home Page 

- Plan Page 

- Analysis Page

- Profile Page

**5.3 AI for Code writing**

Prompt used: "react native code for circular progress step tracker"

Result: Used code to show exercieses and calorie charts with updates

**5.4 AI for Debugging**

Prompt used: "google login not working in expo app", "navigation doesn’t wait for login data"

Result: Fixed auth flow delay and found out it was promise not awaited properly.

**5.5 AI for Deployment**

Prompt used: "how to build apk from expo project"

Result: Followed eas build steps and managed to install APK on Android device.

—------------------------------------------------------------------------------------------------------------------

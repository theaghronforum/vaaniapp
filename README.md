📱 AgronForum – Vani AI News Application 

AgronForum is an Android application that introduces Vani, a 24/7 AI-powered voice news assistant. The app focuses on delivering only what truly matters by allowing users to personalize their news preferences and listen to curated audio-based content.

The UI and user flow are designed based on Figma designs, ensuring a modern, clean, and user-friendly experience.

✨ Key Features

Unlock Vani onboarding flow

Two-step personalization process for user interests

Voice-based news cards with play & status indicators

Category tags like World Bot, Red Alert, Personal Bt

Bottom navigation with multiple sections

Custom UI components using XML and drawable resources

🛠 Tech Stack

Language: Java

UI: XML (ConstraintLayout, LinearLayout, CardView)

IDE: Android Studio

Design Reference: Figma

Minimum SDK: As per Android Studio default

Architecture: Activity-based navigation

📂 Project Structure

app/
│

├── manifests/
│
└── AndroidManifest.xml
│

├── java/com/example/agronforum/
│   ├── MainActivity.java
│   ├── VaaniActivity.java
│   ├── PersonalizeVaaniActivity.java
│   ├── PersonalizeVaaniStep2Activity.java
│   └── VaniPopupActivity.java
│

├── res/
│   ├── layout/
│   │   ├── activity_main.xml
│   │   ├── activity_vaani.xml
│   │   ├── activity_personalize_vaani.xml
│   │   └── activity_personalize_vaani_step2.xml
│   │

│   ├── drawable/
│   │   ├── bg_bottom_sheet.xml
│   │   ├── bg_input.xml
│   │   ├── bg_tag.xml
│   │   ├── bg_status_tag.xml
│   │   ├── button_filled.xml
│   │   ├── button_outline.xml
│   │   ├── circle_green.xml
│   │   ├── circle_yellow.xml
│   │   └── icons (play, add, vani, etc.)
│   │

│   └── values/
│       ├── colors.xml
│       ├── themes.xml
│       └── dimens.xml

✅ Validation Logic

Mandatory fields are checked before proceeding

If user clicks Next / Get Vani without filling required inputs:

Error message is shown

Navigation is blocked until valid input

🚀 How to Run the App

Open the project in Android Studio

Let Gradle sync completely

Connect an Android device or start an emulator

Click Run ▶️ to install and launch the app

👨‍💻 Contributors

Done by:

Ayush Gupta

Saumya Nigam

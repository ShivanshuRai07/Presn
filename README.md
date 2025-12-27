# Presn – Smart Attendance Application

# 👥 Project Team
Shivanshu Rai  
Kartik Mailaram  
Mohammed Yusuf Sayed  
Ritesh Zagade  
Swayam Sonavne  

# About the Project:
Presn is an Android-based smart attendance app that we developed as a college group project to make attendance more genuine and harder to fake.The basic idea is simple and practical. Instead of students marking attendance on their own, the process starts from the **professor’s device**.When the lecture begins, the professor opens the Presn app and starts the attendance session. At that moment, the professor’s device broadcasts a Bluetooth signal. Only the students who are **nearby in the classroom** and have the Presn app open on their phones are able to receive this notification.Once the notification is received, the student is asked to verify their identity using **biometric authentication**. Attendance is marked only after this verification is successful.This flow ensures that attendance can be marked **only during the lecture**, **only inside the classroom**, and **only by the correct student**.

# How Presn Works:
- The professor starts the lecture and opens the Presn app  
- The app broadcasts a Bluetooth signal from the professor’s device  
- Nearby student devices with the app open detect the signal  
- Students verify their identity using biometric authentication  
- Attendance is marked successfully

# Technologies Used:
- Android (Java)
- Bluetooth communication
- Supabase
- Biometric Authentication
- Secure local data handling
- Android UI components

# Where It Can Be Used:
Presn is mainly designed for:
- Colleges and universities  
- Schools  
- Training institutes  
It can also be adapted for organizations that require secure and location-based attendance systems.

# APK Information:
- File Name: `Presn.apk`
- Platform: Android
- Project Type: Academic Group Project

# Future Improvements:
Some features we would like to explore in the future:
- Location (GPS) based verification
-Can be extended for multiple academic use cases in the future.
- Support for multiple classes and sessions

# Final Note
Presn is a learning-focused group project that reflects our teamwork and our effort to solve a real classroom problem using mobile technologies. The project helped us understand how device-to-device communication and biometric authentication can be combined to build practical Android applications.

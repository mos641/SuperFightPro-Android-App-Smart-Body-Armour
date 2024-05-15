# SuperFightPro-Android-App-Smart-Body-Armour
A martial arts smart body armour with embedded sensors communicating via bluetooth to an Android application displaying and tracking your strike strength and locations for training purposes.

I lead an interdisciplinary group of my peers to build a smart phone application and martial arts body armour equipment which were designed, programmed, assembled, and tested based on cost, sustainability, durability, and manufacturability for the purpose of enhancing martial artist’s training routines within the boundaries of the Android platform, closed source software, and client requirements. Throughout the process we authored a detailed technical report outlining the research, design, implementation, testing, results and recommendations for the project.  
  
The project was directed by the client, a Karate instructor, looking for better training solutions. The objective of the project was to deliver a working prototype of a mobile application that can communicate with a body armour to record strike data. The mobile application would aggregate strike power, location, and timing data gathered from each sensor and display it to the end user to provide a visual representation of progress and areas requiring improvement. The mobile application, in conjunction with the body armour, would enable martial artists to assign concrete data to their striking, both the power of the strikes and the locations of the strikes, allowing more informed and precise training. The visualisation of the data and gamifying certain elements would provide incentive to continuously train and hone their skills.  
  
To achieve this goal, our team disassembled and embedded sensors connected to a microcontroller within the body armour provided by the client, this involved various electrical engineering work. The electrical circuits for the sensors went through different variations and required extensive testing to achieve the desired accuracy, granularity, and range for the sensor readings. The hardware was connected to an ESP32 microcontroller which read and transmitted data through code written in C.  
  
The mobile application was built for Android using Kotlin, the official language for Android development. Communication was done through Bluetooth; the functionality was built from the microcontrollers side and the applications side. When entering one of the modes, the application read the transmitted data from the armour and display the appropriate data depending on the mode. Three modes were built, training mode with a configurable time that displayed strike strength, location, and averages to the user. The second mode was a speed game mode, giving the user one minute to strike the armour as much as possible, with their total strikes displayed and being their final score. The last mode was a strength game mode, giving the user ten seconds to strike the armour as hard as they could, displaying their greatest strike. Strike data was saved and persisted using SQLite to allow the user to review their progress. The application allowed for multiple users, with the strike data tied to the appropriate user.  
  
[Algonquin College Project Page](https://www.algonquincollege.com/arie/2023/04/martial-arts-training-application-body-armour/)  
  
<a href="http://www.youtube.com/watch?feature=player_embedded&v=-vWOOe_0j7g&ab" target="_blank"><img src="http://img.youtube.com/vi/-vWOOe_0j7g&ab/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

This was the Armour:
<img src="https://drive.google.com/thumbnail?id=1O_KtISXboAeJkdwuYsy59707GKtPc6Yi&sz=w1000" style="max-width: 60%;" >

The Application Dashboard:  
![Home Page/Dashboard](https://drive.google.com/thumbnail?id=1J2Zga4MgXJX1MU8tYxmLdCAvUhVF7uyo&sz=w1000)
<img src="https://drive.google.com/thumbnail?id=1PvbITOjR29HqQkEwTnw-jYL3vbZLyiOK&sz=w1000" style="max-width: 24%;" >
<img src="https://drive.google.com/thumbnail?id=1iZwNqpSiE494-cekTZDwnGN8zMW7AwiK&sz=w1000" style="max-width: 24%;" >
<img src="https://drive.google.com/thumbnail?id=1TA8L18t1ye3jXJbpA__CVcWzg4Eb0xAC&sz=w1000" style="max-width: 24%;" >

  
The "Modes" Selection Page:  
<img src="https://drive.google.com/thumbnail?id=1IXRVxerdwmkXnBCghmXzYtOub10obK8I&sz=w1000" style="max-width: 24%;" >
<img src="https://drive.google.com/thumbnail?id=1X__41KipkKWUsyYHEW9aVtzOhnpRirkO&sz=w1000" style="max-width: 24%;" >

  
The "Training" Mode:  
<img src="https://drive.google.com/thumbnail?id=1-JRnIa6XYIAoRLICUk564oDNfnl20v_F&sz=w1000" style="max-width: 24%;" >
<img src="https://drive.google.com/thumbnail?id=1HF9hP66NPY0GMWCI1-NKmQCKz1gqLCZK&sz=w1000" style="max-width: 24%;" >

  
The "Speed" Mode:  
<img src="https://drive.google.com/thumbnail?id=1fhU1MSBEKAy90f79D7vVsZcHPSx1HacR&sz=w1000" style="max-width: 24%;" >
<img src="https://drive.google.com/thumbnail?id=1WrKG9sJopI4l9yZnPb0KJtvd2FrZn6Dc&sz=w1000" style="max-width: 24%;" >

  
The "Strength" Mode:  
<img src="https://drive.google.com/thumbnail?id=1tyMafwR3wKDha19wQfj-GjIK5m5532-A&sz=w1000" style="max-width: 24%;" >
<img src="https://drive.google.com/thumbnail?id=1OqL-Ge0DzlNA7xEtJUA6CjWJLWWFFvUa&sz=w1000" style="max-width: 24%;" >

  
The Settings Page:  
<img src="https://drive.google.com/thumbnail?id=1vp_7HMYtvsPkBJfz4atVi-Xej_jIFvjY&sz=w1000" style="max-width: 24%;" >
<img src="https://drive.google.com/thumbnail?id=1hJkBnx42q-1M6oovmjY__uqvLaqM0AOI&sz=w1000" style="max-width: 24%;" >

  
The Users Selection and Creation/Editing Page:  
<img src="https://drive.google.com/thumbnail?id=1dAu38pzu2w0_XX63RuVXZ-waIGsK29Aq&sz=w1000" style="max-width: 24%;" >
<img src="https://drive.google.com/thumbnail?id=1OLghVlfCxFykVvOUyYccmOQbW6t7M5pS&sz=w1000" style="max-width: 24%;" >
<img src="https://drive.google.com/thumbnail?id=1xpf60sZv2HMORqYGLr7cfs_0sek-sAHC&sz=w1000" style="max-width: 24%;" >
<img src="https://drive.google.com/thumbnail?id=19py10bDQy4prMTcRlzveSBd1H4Tbdb1B&sz=w1000" style="max-width: 24%;" >

  
The Bluetooth Page:  
<img src="https://drive.google.com/thumbnail?id=1lR0U58UnZGoFBwedkOF0PSLQegFCF5j-&sz=w1000" style="max-width: 24%;" >
<img src="https://drive.google.com/thumbnail?id=190YhsxXO0u86Jo5rIQnZ9nWVzlBnVEOK&sz=w1000" style="max-width: 24%;" >

The "Theme" and "Measurement Units" settings were each a pop up menu.  
  
  
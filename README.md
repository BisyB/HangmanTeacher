# ImpiccatoTeacher 🎓🇮🇹

![Logo](logo.ico)
  
**ImpiccatoTeacher** is an educational application developed in **C# with Unity** in 2023. It was designed to offer Italian teachers an innovative and interactive method for evaluating students.  

The app transforms a traditional test into a digital, engaging, and customizable experience, ensuring automatic recording of grades. It is currently used by an Italian school as a tool for assessments.

---

## Main Features 🚀  
- **Test Mode** 📋:  
  Students can select a specific database and complete the test by entering their first name, last name, and class.  

- **Grade Recording** 🗂️:  
  At the end of each test, the app records the grade, student's name, and the date. This information is not accessible to the developer, but only to the teacher.  

- **Database Customization** 🛠️:  
  Teachers can upload a `.txt` file containing the questions and customize various aspects of the test:  
  - Test duration 
  - Number of questions 
  - Penalty for incorrect answers  
  - Enabling or disabling the random question mode   

- **Grade Management** 🧑‍🏫:  
  Allows viewing and managing the history of tests.

- **Password Protected Management Area** 🔐:  
  The app's management area, which includes settings, grade history, and more, is accessible only with a password. The password is: `@michele.bisignano_`.

- **Default Question File** 📄:  
  By default, the application includes a preloaded question file with legal questions in Italian.

- **Instructions for Custom Question Files** 📂:  
  The app provides information on how to upload custom question files.

---

## Technologies Used 💻  
- **C# and Unity**: for developing the application  
- **Local `.txt` file database**: for managing questions and answers  
- **Custom User Interface**: designed to be simple and intuitive  

---

## How to Use the Project 📦  
You can download the project in two ways:

1.1 **Using Git Command Line**:  
   Clone the repository to your local machine using the following command:
   ```bash
   git clone https://github.com/your-username/ImpiccatoTeacher.git
   ```

1.2 **Downloading as a ZIP File**:  
   - Go to the GitHub repository page.
   - Click on the green "Code" button.
   - Select "Download ZIP".
   - Extract the downloaded ZIP file to your desired location.

2. **Upload Your Question Database**:  
   - Create a `.txt` file following the format specified in the "Instructions for the `.txt` File" section.
   - You can save the file in the `Database` directory of the project, or in any location on your computer.
   - Follow the instructions provided in the app to link the question file by copying the path of the database after pressing the "Caricamento" button.

3. **Run the Project**:
   Click the file "impiccato.exe" and have fun! 😊
---

## Instructions for the `.txt` File 📝  
The question database must be created by the teacher in a plain `.txt` file. Each entry should follow one of these formats:
- **Alternating lines:** Write the question on one line and the answer on the next.  
- **Single line:** Write the question and answer on the same line, separated by `@`.  

---

## Language 🌍  
The application is mainly in **Italian**.  

---

## Credits 👨‍💻  
Developed by **Michele Bisignano** in 2023.  
The main algorithm was completed in 2022, at the age of 17.

All skills and knowledge used in this project were acquired through self-learning. 📚  

---

## Tags 📌
- #CSharp
- #Unity
- #EducationalApp
- #DigitalAssessment

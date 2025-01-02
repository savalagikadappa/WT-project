# 📚 In-Semester Exam Management: Generate and Allocate Classrooms Module

## 🌟 Project Overview
Welcome to the **Generate and Allocate Classrooms** module! This vital part of the In-Semester Exam Management system is designed to streamline the process of selecting classrooms for exams. From generating timetables to managing absentees, our module takes center stage in ensuring a smooth experience for everyone involved. 🎓✨

## 🎯 Module Objectives
- **Classroom Listing**: Display a dynamic list of available classrooms. 🏫
- **Classroom Selection**: Enable users to select classrooms using checkboxes. ✅
- **Data Persistence**: Securely save the selected classrooms for future access. 💾
- **Data Integration**: Seamlessly pass data to other modules for further processing. 🔄

## ⚙️ Functionality
This module features interactive forms for each exam session, allowing users to:
- **View Available Classrooms**: A list is populated with unique classes extracted from the database.
- **Select Classrooms**: Users select desired classrooms via checkboxes. 🗹
- **Submit Selection**: Upon clicking **Submit**, a confirmation popup appears, and a new table is created in the database with a name reflecting the exam session (e.g., `available_classes_20241223010000`). 🗄️

## 🛠️ Technical Details
- **Frontend**: HTML, CSS, JavaScript, React.js 🌐
- **Backend**: Node.js 🚀
- **Database**: MySQL 🗄️
- **Version Control**: Git & GitHub 📊

## 🌟 Key Features
- **Dynamic Classroom List**: Updates in real-time to reflect availability. ⏱️
- **Intuitive Interface**: Simple checkbox selection for ease of use. ✨
- **Secure Data Handling**: Protects the integrity of classroom assignments. 🔒
- **Automated Data Transfer**: Effortlessly passes selected data to subsequent modules. 📥

## 🚀 Future Improvements
While we are thrilled with our current implementation, we see room for growth:
- **Real-time Availability Updates**: Reflect classroom bookings dynamically. 🔄
- **Capacity Management**: Prevent overbooking by integrating capacity information. 📏
- **Advanced Search/Filtering**: Enhance user experience with better navigation and search options. 🔍

## 🤖 Selenium Testing
Selenium testing was implemented to automate the verification of web application functionalities across various browsers. This approach ensured consistent performance and behavior, enhancing the reliability of the application. By leveraging Selenium WebDriver, we created a suite of test cases that simulate user interactions, validate UI components, and confirm backend responses. The tests were organized into modules for ease of maintenance and scalability, providing confidence in our deployment process and minimizing the risk of regressions in future updates.
For more information about the project, please visit our [Google Site](https://sites.google.com/view/webtechportfoliokadappa/home).

Thank you for exploring the **Generate and Allocate Classrooms** module! Together, we're working towards a more efficient and integrated exam management system. 📚🎉

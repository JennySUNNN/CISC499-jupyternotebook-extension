# CISC 499 Advanced Undergraduate Project

Developed **6 Jupyter Notebook nbextensions** to improve teaching and learning experience on Jupyter Notebook for both professors and students.

Supervisor:
--------------------------
- [Dr. Burton Ma](https://www.cs.queensu.ca/people/profile.php?firstname=Burton&lastname=Ma), Associate Professor, Queen's School of Computing

Group Members:
--------------------------
- Derek Huang
- Jenny Sun
- Andrea Mitchell

## Overview:

Jupyter notebookis an open source web application that allows users to write notebooks which support a mixture of runnable code, markup text, multimedia, graphs and more. It mostly used by researchers and data scientists to share code and analyze data. It also has great potential for instructors and students to assist teaching and learning, while there are some missing functionalities for teaching application.

## Goal:

This project aims to enhance Jupyter Notebook's accessibility and effectiveness for both instructors and students by developing new features and functionalities. The project is open-source and aims to create extensions that address the limitations of Jupyter Notebook for teaching and learning purposes. These extensions will make Jupyter Notebook a more versatile and useful tool for education, enabling instructors to present material interactively and engage students in their learning process. Our team worked collaboratively to develop six extensions that address the missing functionalities from both the instructor and student perspectives, thereby improving the effectiveness of teaching and learning.


## Installation:
Make sure you have **Jupyter Notebook** and **Git** installed first. 

In command/terminal:

First download this collection and cd to the folder: 
```
git clone https://github.com/JennySUNNN/CISC499-jupyternotebook-extension.git

cd CISC499-jupyternotebook-extension
```
Next, install the extension you want:
e.g. 'template' extension
```
jupyter nbextension install template --user
```
Last, enable the extension:
```
jupyter nbextension enable template/main --user
```
If already installed the nbextension configurator, can also enable/disable the extensions in the nb extension dashboard tab:
![image](https://user-images.githubusercontent.com/67336024/115161900-2c98f300-a06e-11eb-8637-f6c1987e1b3b.png)

List of all extension installment convenient copy paste:
```
jupyter nbextension install template --user
jupyter nbextension install ShortAnswerQuestion --user
jupyter nbextension install multiple_choice_questions --user
jupyter nbextension install highlight_and_colour --user
jupyter nbextension install move_to_top_bottom --user
jupyter nbextension install annotate_text --user

```

```
jupyter nbextension enable template/main --user
jupyter nbextension enable ShortAnswerQuestion/main --user
jupyter nbextension enable multiple_choice_questions/mcq_main --user
jupyter nbextension enable highlight_and_colour/highlight_and_colour --user
jupyter nbextension enable move_to_top_bottom/main --user
jupyter nbextension enable annotate_text/main --user
```

# Below are demonstrations of the use of all extensions:

# Template:
![template](https://user-images.githubusercontent.com/67336024/220408653-bb3b4353-79d7-4f68-97f0-eb5759bc9178.png)
# Short Answer Cell:
![short_answer](https://user-images.githubusercontent.com/67336024/220408717-a6971238-5a42-4217-9ca7-1eab1e5df439.png)
# Multiple Choice Question Cell:
![mcq](https://user-images.githubusercontent.com/67336024/220408745-db3cb46c-4d35-42b6-a8f6-c4ff74c319dc.png)
# Highlighter:
![highlighter](https://user-images.githubusercontent.com/67336024/220404648-5ac362f9-358e-45ff-b84c-b2f6f1714693.png)
# Quick Move to Top/Bottom:
![move_top](https://user-images.githubusercontent.com/67336024/220408819-0cf80007-251a-4168-9928-e30169a8cd0a.png)
# Annotation:
![annotation](https://user-images.githubusercontent.com/67336024/220408852-7c855c1b-b84a-4471-b411-5aab7e7aaa33.png)



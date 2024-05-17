The OMR Sheet Evaluator is a desktop GUI application tailored to enhance the efficiency of the grading process. It’s designed to assist teachers by automating the evaluation of OMR sheets, thereby saving valuable time and reducing manual effort.

# What Does It Do
- This project is a GUI application build on Tkinter library - Python, which scans the multple OMR Sheets.
- It compares the marked answers of each sheet with the Master Key Image at holds the all correct answers.
- Calculates the score as per the correct marked answers and uploads each marks with the image name on the CSV file. 

# Requirements To Install
- Python

- Open CV `pip install opencv-python`

- Pillow `pip install pillow`

# How To Run

1. Run `temp.py` file to as get MAC address as Username.
2. Run 'loginPage.py' file to start Project.
3. Enter the returned value from step 1. as Username and default password is set to '1234'.
4. Browse to the myImages from this project in Select Images Folder
5. Browse to the masterkey.jpg Image from folder containing all files
6. Enter all the required values and Press Submit button
7. On running Successfully message will pop-up and has create a 'csv' file in the same folder.

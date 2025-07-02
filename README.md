📄 Resume Builder - PDF Export
A simple Python desktop application that lets you create and export a professional PDF resume with a sidebar template, using Tkinter for the GUI and ReportLab for PDF generation.

✨ Features
✅ Easy-to-use graphical interface
✅ Upload and embed a profile photo
✅ Enter and format all key resume sections:

Full Name

Email & Phone

Profile Summary

Education

Skills

Work Experience

Languages

Certificates

Honor Awards

Interests
✅ Generates a stylish PDF resume with an advanced sidebar layout
✅ Automatically handles text wrapping and page breaks
✅ Saves the resume as <YourName>_Resume.pdf

⚙️ Tech Stack
Python

Tkinter — for the desktop GUI

ReportLab — for advanced PDF generation

🚀 How to Run
Install Dependencies
Make sure you have Python installed. Then install ReportLab if you haven’t yet:


pip install reportlab
Run the App
Open your IDE (e.g., PyCharm) and run the script:

python your_script.py
Use the App

Fill out your resume details in the form.

Optionally upload a profile photo.

Click “Generate PDF Resume” — your resume will be saved in the same directory.

🖼️ Template
The PDF uses a modern sidebar style with a dark-colored side panel for sections like Skills, Languages, Certificates, Awards, and Interests.

The main content includes Profile Summary, Experience, and Education.

Long text is wrapped automatically and split across pages if needed.

Each page includes a footer with the page number.

📁 Project Structure
Tkinter GUI: For input fields and buttons.

ReportLab Canvas: To draw text, images, and shapes.

Reusable Template: template_advanced function for custom layout.

Image Upload: Add a profile photo if you want it shown on the sidebar.

⚡ Key Functions
upload_photo() — Lets you select a photo from your files.

generate_pdf_resume() — Collects data and generates the PDF.

template_advanced() — Handles the PDF layout with sections and styling.

wrap_text() — Wraps long text to fit nicely in the PDF.

check_page_break() — Handles multi-page resumes automatically.

📌 Requirements
Python 3.x

reportlab

tkinter (comes pre-installed with Python on most systems)

🏷️ License
This project is open source. Feel free to use it, modify it, and improve it!

🙌 Author
Created with 💙 using Python, Tkinter, and ReportLab.

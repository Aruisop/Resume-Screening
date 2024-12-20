# Resume-Screening 
A tool that simulates a mini version of an ATS screening for a users resume based on matched query words from a given job description with the keywords extracted from the users resume, and visualizes the rank percentage by using a bar chart. 

# Key Features
- It Extracts Text from PDF, DOCX and CSV files.
- A menu-driven program.
- Uses spacy to identify the important keywords from the job description.
- It compares the preprocessed resume text with the extracted keywords from the description.
- Calculates a score (as a percentage) based on keyword matches.
- Using matplotlib, visualizes the resume scores.

# How do I use it?
- Just make sure to run the given code/script on either a Google Colab or a Jupyter Notebook environment.
- Enter the job description, and then upload the resumes(in either PDF, DOCX or CSV).
- The final result is displayed as a bar chart.

# File Dependencies
- spacy(used for the natural language processing aspectof the code)
- PyPDF2(used for text extraction from PDF)
- docx(used for DOCX text extraction)
- matplotlib(used to plot the bar chart)
- re(regex used for text cleaning)
- csv(used for CSV file handling)

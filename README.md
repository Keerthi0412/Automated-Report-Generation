# Automated-Report-Generation

COMPANY: CODTECH IT SOLUTIONS

NAME: MODIBOINA CHANDRA KEERTHI

INTERN ID: CT08WB45

DOMAIN: PYTHON PROGRAMMING

MENTOR:NEELA SANTHOSH

DESCRIPTION:
The Multi-Format File Analyzer/Automated Report Generator is a Python-based tool that extracts, processes, and analyzes text or data from various file formats, including TXT, PDF, DOCX, PPTX, and CSV. This script automates the process of reading files, detecting their types, and generating meaningful insights based on their content. The primary objective of this project is to streamline document analysis, text summarization, and basic data exploration** without requiring users to manually open and inspect each file.  

This tool is particularly useful for professionals working with large volumes of documents or datasets** who need quick insights into textual content and structured data. By leveraging Python libraries designed for document processing and data analysis, the program ensures efficiency, accuracy, and ease of user. The user simply provides a file path, and the script identifies the file type and processes its contents accordingly, generating a summary report with relevant statistics.  

The program ensures error handling and robustness, making it suitable for real-world scenarios where documents might have missing, corrupted, or unreadable content. If a file cannot be processed, the script provides clear and informative error messages, guiding the user to resolve any issues.  

Key Functionalities
The Multi-Format File Analyzer?Automated Report Generator provides the following functionalities:  

1. Automated File Detection – Determines the file format based on its extension and routes it to the appropriate analysis function.  
2. Text Processing and Analysis – Extracts and processes text from TXT, PDF, DOCX, and PPTX files, calculating:  
   - Total word count  
   - Total sentence count  
   - Top 10 most common words 
3. Structured Data Analysis – Processes CSV files, providing:  
   - Total number of rows and columns
   - Statistical summaries of numerical columns (sum, average, max, min)  
4. Robust Error Handling – Prevents crashes due to corrupt, empty, or unreadable files, ensuring smooth execution.  
5. User-Friendly Console Output – Displays results in a clear format, making it easy to interpret.  

Technologies and Tools Used
The project leverages several Python libraries to handle various file formats and perform efficient text/data analysis:  

- NLTK (Natural Language Toolkit) – Used for text tokenization, sentence segmentation, and linguistic analysis. It helps in processing textual content efficiently.  
- PyPDF2 – Extracts text from PDF documents, handling multiple pages and ensuring text accuracy.  
- python-docx – Reads and extracts text from Microsoft Word (.docx) documents, allowing analysis of document content.  
- python-pptx – Extracts text from PowerPoint (.pptx) slides, ensuring that presentation content is processed correctly.  
- Pandas – Analyzes CSV files, allowing for structured data processing and numerical analysis.  
- Regular Expressions (re module) – Used for **cleaning and tokenizing text**, ensuring accurate word and sentence extraction.  
- os module – Handles file path validation and existence checks, ensuring smooth file loading.  
- collections.Counter – Identifies the most frequently occurring words in a document, aiding text analysis.  

How the Program Works
1. The user is prompted to enter the file path for analysis.  
2. The script checks if the file exists and determines its format based on the extension.  
3. Depending on the file type:  
   - TXT, PDF, DOCX, PPTX files → Text is extracted and analyzed for word count, sentence count, and common words.  
   - CSV files → The script computes **statistical summaries** for numerical columns.  
4. The results are printed to the console, providing a quick summary of the file’s content.  
5. If an error occurs (e.g., unreadable file, incorrect format), an informative error message is displayed.  
  
Use Cases and Applications 
The Multi-Format File Analyzer is highly useful in various domains, including:  

- Academic Research – Quickly analyzing research papers, reports, and datasets.  
- Data Science and Analytics – Exploring CSV data before performing advanced processing.  
- Content Analysis – Examining word frequencies in articles, books, and presentations.
- Corporate Documentation – Extracting insights from business reports, meeting notes, and PowerPoint slides.  
- Legal and Compliance – Reviewing contracts, agreements, and case studies for textual analysis.


OUTPUT:

![Image](https://github.com/user-attachments/assets/e2c4d107-6e6e-4f70-9a6c-00b9d0e0cea0)


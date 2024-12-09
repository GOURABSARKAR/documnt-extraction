# document-extraction
# Overview
This Jupyter Notebook demonstrates how to extract data from various file formats using different Python libraries. The notebook covers the following file types and libraries:

PDF Files: Extraction using LangChain's UnstructuredFileLoader and pdfPlumber.
Text Files: Text extraction and cleansing.
Microsoft Word and PowerPoint Files: Extraction using Apache Tika.
# Prerequisites
Before running the notebook, ensure that you have the following python > 3.11 installed:
# Notebook Content
1. PDF Data Extraction
LangChain's UnstructuredFileLoader: This section demonstrates how to use LangChain for extracting structured data from PDFs.
pdfPlumber: An alternative method for extracting text and other elements from PDFs. pdfPlumber provides a more manual, fine-grained approach to PDF data extraction.
2. Text Extraction and Cleansing
Text Files: The notebook includes code to read raw text data from files and perform basic cleansing operations, such as removing unnecessary whitespace, special characters, and performing text normalization.
3. Microsoft Word and PowerPoint Data Extraction
Apache Tika: This section demonstrates how to extract text from Microsoft Word (.docx) and PowerPoint (.pptx) files using Apache Tika. Tika is a versatile tool that supports many file formats and extracts metadata, text, and other elements from documents.

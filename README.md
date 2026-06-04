AI-Powered Question Paper Generator

Overview

The AI-Powered Question Paper Generator is a mini Agentic AI project that automatically generates university-style question papers from a syllabus PDF.

The system accepts a syllabus document as input, extracts the syllabus content using OCR, analyzes the topics covered in the syllabus, and generates a new question paper following a predefined examination pattern using a Large Language Model (LLM).

This project demonstrates the practical application of Artificial Intelligence, Prompt Engineering, OCR, and Large Language Models in educational automation.


Problem Statement

Creating question papers manually is time-consuming and requires significant effort from faculty members. This project automates the process by generating question papers directly from a syllabus document while maintaining the required exam structure.


Objectives

* Extract syllabus content from PDF documents.
* Process scanned syllabus PDFs using OCR.
* Generate university-style question papers automatically.
* Follow a predefined question paper pattern.
* Demonstrate the use of Generative AI in education.


Technology Stack

Programming Language

* Python

Libraries Used

* pdf2image
* pytesseract
* pypdf
* groq
AI Model

* Llama 3.3 70B Versatile (via Groq API)

Development Environment

* Google Colab

System Architecture

text
Syllabus PDF
      ↓
OCR Extraction (Tesseract)
      ↓
Text Processing
      ↓
Prompt Engineering
      ↓
Llama 3.3 70B (Groq)
      ↓
Generated Question Paper

Working Methodology

Step 1: Upload Syllabus PDF

The user uploads the syllabus PDF file.

Step 2: OCR-Based Text Extraction

Many syllabus PDFs are scanned image documents. Tesseract OCR is used to extract text from the uploaded PDF.

Step 3: Prompt Construction

The extracted syllabus text is combined with a predefined question paper pattern.

Example Pattern:

* Part A: 9 × 2 Marks
* Part B: 3 × 14 Marks

Step 4: AI Question Generation

The processed syllabus and examination pattern are sent to the Llama 3.3 70B model through the Groq API.

The model:

* Identifies syllabus topics
* Covers multiple units
* Generates new questions
* Maintains university examination style

Step 5: Output Generation

A complete question paper is generated and displayed to the user.


Features

* Upload syllabus PDF
* OCR support for scanned PDFs
* Automatic syllabus analysis
* AI-based question generation
* University-style question paper format
* Multiple unit coverage
* Fast generation using Groq LLM


Sample Output Format
Part A (9 × 2 Marks)

1. Define addressing modes.
2. List the features of the 8051 microcontroller.
3. What is an interrupt?
4. Explain the role of an accumulator.
5. Define embedded systems.
6. Differentiate RISC and CISC architectures.
7. What is a Special Function Register?
8. Define serial communication.
9. What is an LCD interface?

Part B (3 × 14 Marks)

10(a). Explain the architecture of the 8085 microprocessor with a neat diagram.

OR

10(b). Discuss the instruction set and addressing modes of the 8085 microprocessor.

11(a). Explain the architecture and memory organization of the 8051 microcontroller.

OR

11(b). Discuss the Special Function Registers of the 8051 microcontroller.

12(a). Explain embedded system architecture and task scheduling concepts.

OR

12(b). Discuss embedded hardware platforms and their applications.



Future Enhancements

* Dynamic question paper patterns
* Difficulty level selection
* Bloom's Taxonomy based question generation
* Multiple question paper sets
* PDF export functionality
* RAG-based syllabus understanding
* Question paper pattern learning from previous papers


Results

The project successfully generates university-style question papers from syllabus documents using OCR and Generative AI. It reduces manual effort and demonstrates the potential of AI-driven educational automation.


 Author

Keerthi Sree

AI-Powered Question Paper Generator using OCR, Prompt Engineering, and Llama 3.3 70B (Groq).

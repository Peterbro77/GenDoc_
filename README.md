### GenDoc_
A Python-based tool to generate formatted Microsoft Word documents for practical files, with support for images

This is a simple Python tool that helps you generate formatted Microsoft Word documents for practical files or assignments.  
It allows you to enter multiple question-answer pairs, along with optional images for each entry.

---

##  Features

- Accepts any number of question-answer entries
- Adds each question in **bold** and size **14**
- Adds the answer in regular text with size **12**
- Allows inserting an image after each answer under an **"Output:"** heading
- Automatically saves everything in a Word `.docx` document

---

##  How to Use


1. **Install the required library:**

   ```bash
   pip install python-docx

2. Now just Run the Script.
   
3. Follow the prompts:

Enter how many Q&A entries you want to add

Enter each question, answer, and an optional image path

The output will be saved to a file named output.docx in the same folder.

Example Entry
When prompted:

  ```bash
  Enter Question: What is a variable in Python?
  Enter Answer: A variable is a container for storing data values.
  Do you want to add an image for this question? (y/n): y
  Enter path to image: sample_image.png
  This creates a document section like:
  
  Output:
  Q: What is a variable in Python?
  A variable is a container for storing data values.
  
  (Image is inserted here)

```
## Requirements
Python 3.6+

python-docx






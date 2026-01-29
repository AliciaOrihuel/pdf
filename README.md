# PDF Repository

This repository is for storing and managing PDF documents.

## Directory Structure

- `pdfs/` - Contains all PDF files

## How to Submit/Add PDF Files

### Method 1: Using Git Command Line

**Note**: You need write access to this repository, or you can fork it and submit a pull request.

1. Clone the repository:
   ```bash
   git clone https://github.com/AliciaOrihuel/pdf.git
   cd pdf
   ```

2. Add your PDF file to the `pdfs/` directory:
   ```bash
   cp /path/to/your/document.pdf pdfs/
   ```

3. Commit and push your changes:
   ```bash
   git add pdfs/your-document.pdf
   git commit -m "Add your-document.pdf"
   git push
   ```

### Method 2: Using GitHub Web Interface

1. Navigate to the `pdfs/` folder in the repository
2. Click "Add file" → "Upload files"
3. Drag and drop your PDF file(s)
4. Add a commit message
5. Click "Commit changes"

## Sample Files

- `pdfs/sample.pdf` - A sample PDF document demonstrating the repository structure
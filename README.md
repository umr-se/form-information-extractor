# Form Information Extractor

## Overview
**Form Information Extractor** is a Python-based backend script designed to run on Google Colab. This script extracts specific information from employee forms and saves the extracted data into an Excel file. The information extracted includes:

- Name
- Birthdate
- Email
- Phone Number
- School
- College
- Year of Graduation

## Features
- Extracts and processes form data efficiently.
- Saves the extracted data into a structured Excel file for further use.
- Filters specific fields such as name, email, phone number, etc.

## Getting Started

### Prerequisites
To use this project, you need:
- A Google account for accessing Google Colab.
- Basic knowledge of Python.
- Required Python libraries installed (detailed below).

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/form-information-extractor.git
   cd form-information-extractor
   ```
2. Open the script in [Google Colab](https://colab.research.google.com/):
   - Upload the `form_extractor.ipynb` file to Google Colab.

3. Install the necessary Python libraries:
   ```python
   !pip install pandas openpyxl
   ```

### Running the Script
1. Upload the form files (e.g., scanned forms, images, or text files) to the Colab environment.
2. Run the notebook cells step-by-step.
3. The script will:
   - Extract the filtered information from the forms.
   - Save the extracted data to an Excel file named `extracted_data.xlsx`.
4. Download the `extracted_data.xlsx` file from the Colab environment to your local system.

## Example Usage
```python
# Import required libraries
import pandas as pd

# Example extracted data
data = {
    "Name": ["John Doe"],
    "Birthdate": ["1995-06-15"],
    "Email": ["john.doe@example.com"],
    "Phone Number": ["+123456789"],
    "School": ["ABC High School"],
    "College": ["XYZ University"],
    "Year of Graduation": ["2018"]
}

# Save data to Excel
df = pd.DataFrame(data)
df.to_excel("extracted_data.xlsx", index=False)
```

## Folder Structure
```
form-information-extractor/
├── form_extractor.ipynb  # Google Colab notebook containing the script
├── sample_forms/         # Folder to upload your form files (optional)
├── extracted_data.xlsx   # Output Excel file (generated after running the script)
```

## Libraries Used
- **pandas**: For data manipulation and saving to Excel.
- **openpyxl**: For working with Excel files.

## Contributing
Feel free to fork this repository, create a new branch, and submit a pull request with improvements or additional features.

### Author
- **Muhammad Umer Saleem**  
  Software Engineer specializing in Python backend development.

For any questions or suggestions, feel free to reach out!
![test_form](https://github.com/user-attachments/assets/6f5f0844-bc9c-4145-8942-e243b6a6a961)
![Screenshot 2025-01-20 201033](https://github.com/user-attachments/assets/9c49bc50-4c60-4baa-b994-d49f68af9b55)





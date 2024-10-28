
# Resume Analyzer

This project, **Resume Analyzer**, is designed to process and analyze resume data using Python. This README provides setup instructions, a breakdown of the included files, and guidance on using the application.

## Project Structure

- `.env`: Contains environment variables (e.g., API keys, database URLs). Ensure you set this file correctly before running the project.
- `new.py`: The main Python script for the Resume Analyzer, containing the core functionality.
- `Requirements.txt`: Lists all required dependencies to install for running the application smoothly.
- `images/`: Contains images (`icon1.png`, `icon2.png`, `icon3.png`) that may be used as icons or assets in the application.

## Setup Instructions

1. **Clone or Download** the project files.
2. **Install Dependencies**:
   - Ensure you have Python installed (version 3.7 or higher is recommended).
   - Use the following command to install the necessary libraries:
     ```bash
     pip install -r Requirements.txt
     ```

3. **Environment Setup**:
   - Rename `.env.example` (if provided) to `.env`.
   - Fill in the required environment variables in the `.env` file.

## Running the Application

1. Execute the main script `new.py` to start the application:
   ```bash
   python new.py
   ```
   Ensure you have all required environment variables set.

2. The script will process and analyze resume data according to the specifications defined in the code.

## Dependencies

All dependencies are listed in `Requirements.txt`. Run `pip install -r Requirements.txt` to install them.

## Assets

The `images/` folder contains image assets, which might be used for UI elements or as iconography within the project.
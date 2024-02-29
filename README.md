# GPTResumePrompter
Your ChatGPT AI Resume Writer

This project utilizes the OpenAI API to automate the process of writing resumes and cover letters. By providing prompts and input files, the program generates a refined resume and cover letter tailored to specific job listings.

## Requirements

`pip install openai`

## Setup

To use this program, you need to set up the OpenAI API key. Replace `os.environ["OPENAI_API_KEY"] = ''` with your API key.

To start resume_info, cover_letter and job_listing need to be replaced in the data folder.

## Usage

1. **Environment Setup**  
   - Ensure you have Python installed.
   - Install the required packages: `pip install openai`.

2. **Input Files**  
   - Place the following files in the `data` folder:
     - `create_prompt.txt`: Prompt for creating the initial resume.
     - `refine_prompt.txt`: Prompt for refining the resume.
     - `audit_prompt.txt`: Prompt for auditing the resume.
     - `resume_info.txt`: Resume information.
     - `cover_letter.txt`: Cover letter information.
     - `cover_prompt.txt`: Prompt for creating the cover letter.
     - `job_listing.txt`: Job listing information.

3. **Execution**  
   - Run the notebook 'autoresume' to generate the final resume, rating, and cover letter.

4. **Output**  
   - The final resume is saved in `resume_file.txt`.
   - The rating is saved in `rating_file.txt`.
   - The cover letter is saved in `cover_output.txt`.

## Notes

- Ensure all input files are correctly formatted to avoid errors.
- Adjust the `temperature` parameter for more conservative or creative responses.
- This program is designed to automate the resume writing process, but manual review and editing are recommended for the final documents.

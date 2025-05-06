# NYC Taxi Data

## Overview
[Provide a brief summary of your project here. Include what the project does, technologies used, and the overall goal.]

## How to Run the Project

1. Download the "proj docker" folder
2. Make changes in streamlit_app.py and Load-2.py. Update these values which currently have placeholders:
   ```python
   DB_HOST = 'localhost'
   DB_PORT = '5432'
   DB_NAME = 'taxi_data'
   DB_USER = 'postgres'
   DB_PASSWORD = 'hello'
3. Go to terminal and run "docker build -t streamlit-etl-app ."
4. Next, run "docker run -p 8501:8501 streamlit-etl-app"
5. Copy ad paste the Local URL in the browser of your choice. Below is a screenshot of the streamlit dashboard and what should come up on your screen too.

<br>
<br>

<img width="1494" alt="Screenshot 2025-05-06 at 4 45 37 PM" src="https://github.com/user-attachments/assets/dce77810-0f7a-4063-b029-324d49bd7fc1" />

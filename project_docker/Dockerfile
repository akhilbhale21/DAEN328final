FROM python:3.10-slim

WORKDIR /app

COPY . .

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8501

CMD ["bash", "-c", "python Extract.py && python Transform.py && python Load.py && streamlit run streamlit_app.py"]


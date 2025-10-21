FROM python:3.9-slim 

WORKDIR /app

COPY . . 

COPY .streamlit/ .streamlit/

RUN pip install -r requirements.txt

EXPOSE 8501

CMD  [ "streamlit", "run", "app.py", "--server.address=0.0.0.0" ]


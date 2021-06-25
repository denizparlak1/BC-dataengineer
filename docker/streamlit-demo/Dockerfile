FROM python:3.8-slim-buster

WORKDIR /app

COPY requirements.txt requirements.txt

RUN pip3 install streamlit
RUN pip3 install scikit-learn
RUN pip3 install matplotlib

EXPOSE 8501
ENTRYPOINT ["streamlit","run"]
CMD ["main.py"]

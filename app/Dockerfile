FROM arm32v5/python
WORKDIR /app
RUN sudo apt-get install python3-blinkt
COPY requirements.txt requirements.txt
COPY . .
CMD ["touch","test.txt"]
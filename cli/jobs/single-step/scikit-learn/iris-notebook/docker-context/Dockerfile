FROM python:3.14.0a3
FROM python:3.13.3

# python installs
COPY requirements.txt .
RUN pip install -r requirements.txt && rm requirements.txt

# set command
CMD ["bash"]

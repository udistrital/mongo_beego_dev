FROM python:2.7
ENV http_proxy proxy.udistrital.edu.co:3128
ENV https_proxy proxy.udistrital.edu.co:3128
COPY loop.py /code/loop.py
RUN pip install jinja2 textx
WORKDIR /code
CMD python loop.py

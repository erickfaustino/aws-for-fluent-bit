FROM public.ecr.aws/amazonlinux/amazonlinux:latest

RUN yum upgrade -y && yum install -y python3 pip3

RUN pip3 install boto3

WORKDIR /usr/local/bin

COPY clean.py .

CMD ["python3", "clean.py"]

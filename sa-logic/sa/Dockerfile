FROM python:3.6

WORKDIR /app

ADD requirements.txt /app/requirements.txt
ADD sentiment_analysis.py /app/sentiment_analysis.py

RUN cd /app
RUN pip install -r requirements.txt

run python3.6 -m textblob.download_corpora

EXPOSE 5000

CMD [ "python", "sentiment_analysis.py" ]

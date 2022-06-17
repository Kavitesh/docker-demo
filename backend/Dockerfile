FROM python

WORKDIR "/app"

COPY ./backend.py ./

RUN pip install flask

EXPOSE 5000

CMD [ "python", "./backend.py" ]
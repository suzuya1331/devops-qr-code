FROM python

WORKDIR /app

COPY . .

RUN python -m venv .venv

RUN pip install -r requirements.txt

CMD [ "uvicorn","main:app","--reload" , "--host","0.0.0.0" ]
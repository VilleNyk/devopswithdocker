build both frontend and backend dockerfiles at their own folders with
> docker build -t front .
> docker build -t back .

start the back-end service with
> docker run -p 8000:8000 back

then start the front-end service with
> docker run -p 5000:5000 front

visit localhost:5000 and press the button after "Exercie 1.12" to verify
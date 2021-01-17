Build dockerfile with
> docker build -t backend .

To write to the log file, run dockerfile in powershell:
> docker run -p 8000:8000 -v ${PWD}/logs.txt://backend-example-docker/logs.txt backend
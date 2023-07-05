FROM  buildpack-deps:latest
WORKDIR /app
COPY . /app
RUN g++ -o myapp dockerApp.cpp
CMD [ "./myapp" ]

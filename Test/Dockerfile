FROM ubuntu:latest
ARG subdir=defaultdir
WORKDIR /usr/local/myapp

# Copy artifacts
COPY ./ArtifactsDir .

RUN mkdir $subdir
RUN echo "Dynamic text" > fakefile.dll


#EXPOSE 8000
#CMD [ "/bin/sh", "run.sh", "$CONFIG_PATH" ]
CMD /bin/sh run.sh $CONFIG_PATH

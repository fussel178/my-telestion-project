FROM openjdk:16.0

ENV APP_DIR /usr/telestion/my-telestion-project

ADD build/distributions/my-telestion-project.tar /usr/telestion

WORKDIR $APP_DIR
EXPOSE 9870

ENTRYPOINT ["sh", "-c"]
CMD ["./bin/my-telestion-project"]

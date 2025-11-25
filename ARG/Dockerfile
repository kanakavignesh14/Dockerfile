ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="DOCKER" \
    TRAINER="SIVA"
ENV COURSE=${COURSE}    

RUN echo "Trianer is ${TRAINER} and course is --> ${COURSE} AAND VERSION IS ${VERSION}" # VERSION cant be accessed because it is above FROM
LABEL BUILD-COMMAND="docker build -t arg:v1 --build-arg VERSION=8 --build-arg COURSE=AWS ."
CMD ["sleep","1000"]

# USE LIKE THIS ---> docker build -t arg:v1 --build-arg VERSION=8 --build-arg COURSE=AWS .
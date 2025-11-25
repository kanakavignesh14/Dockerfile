ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="DOCKER" \
    TRAINER="SIVA"
ENV COURSE=${COURSE}    

RUN echo "Trianer is ${TRAINER} and course is --> ${COURSE} AAND VERSION IS ${VERSION}" # VERSION cant be accessed because it is above FROM

CMD ["sleep","1000"]
ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="DEVOPS" \
    TRAINER="kirankumar"
ENV COURSE=${COURSE}
RUN echo "Course: ${COURSE}, Trainer: ${TRAINER}, version: ${VERSION}"
CMD ["sleep","1000"]
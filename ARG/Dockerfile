ARG version
FROM almalinux:${version:-9}
#:-9 it will take version 9 if we dont give version at the build time
ARG COURSE
ARG TRAINER
ENV DURATION=120hrs
RUN echo "{course is :${COURSE}, Trainer is :${TRAINER},Duration is :${DURATION}}"
CMD [ "sleep","100" ]

#how can i pass an arg to a container
#ARG DURATION
#ENV DURATION=${DURATION}
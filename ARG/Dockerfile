ARG version
FROM almalinux:${version:-8}
#:- this symbole is by default if you have not given any version at the time of build it will build version 8.
ARG COURSE="Docker" \
    TRAINER="Surendra"
RUN echo "COURSE is: ${COURSE} and trainer is: ${TRAINER}"
CMD ["sleep","200"]
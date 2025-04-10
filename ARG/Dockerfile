FROM almalinux:9
ENV course="DevOps with AWS"\
    trainer="sara"\
    duration="120HRS"
#here user1 is key, someuser is default value
ARG USERNAME=sara
ENV USERNAME=$USERNAME
RUN echo "Hello User: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]
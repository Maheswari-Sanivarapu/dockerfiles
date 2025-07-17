ARG version
FROM almalinux:${version:-9}
ENV name="pavithra" \
    laptop="HP"
ARG sisname="Chanti"
ENV sisname=$sisname
RUN echo "Hi name is:${name},laptop is ${laptop}, version is ${version}"
CMD ["sleep", "1000"]
ARG version
FROM almalinux:${version:-9}
ENV name="reddy" \
    laptop="HP"
ARG sisname="Chanti"
ENV sisname=$sisname
RUN echo "Hi name is:${name},laptop is ${laptop}, sisname is ${sisname}"
CMD ["sleep", "1000"]
FROM alpine
RUN apk update
RUN apk add curl
RUN apk add libgcc
RUN apk add cmake
#RUN apk add gcc
RUN curl https://sh.rustup.rs -sSf | sh -s -- --profile default --default-toolchain stable -y
ENV PATH="/root/.cargo/bin:$PATH"
ENV USER=rust_user
CMD ["/bin/sh"]

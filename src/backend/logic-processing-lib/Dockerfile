FROM rust:1.73.0

WORKDIR /usr/src/logic-processing-lib
COPY . .

RUN cargo install --path .

CMD ["logic-processing-lib"]
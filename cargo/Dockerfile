FROM rust

LABEL "com.github.actions.name"="Cargo"
LABEL "com.github.actions.description"="Cargo"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="white"

RUN rustup target add wasm32-unknown-unknown

ADD entrypoint.sh /entrypoint.sh
ENTRYPOINT ["sh", "/entrypoint.sh"]
FROM node

LABEL "com.github.actions.name"="Parcel"
LABEL "com.github.actions.description"="Parcel"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="purple"

RUN npm install -g parcel-bundler

ADD entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
FROM ubuntu

LABEL "com.github.actions.name"="Git"
LABEL "com.github.actions.description"="Git"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="white"

RUN apt-get update && apt-get install git -y

ADD entrypoint.sh /entrypoint.sh
ENTRYPOINT ["sh", "/entrypoint.sh"]
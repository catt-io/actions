FROM node

LABEL "com.github.actions.name"="Parcel"
LABEL "com.github.actions.description"="Parcel"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="white"

LABEL com.github.actions.name="GitHub Action for npm"
LABEL com.github.actions.description="Wraps the npm CLI to enable common npm commands."
LABEL com.github.actions.icon="package"
LABEL com.github.actions.color="red"

RUN npm install -g parcel-bundler

# ADD entrypoint.sh /entrypoint.sh
# ENTRYPOINT ["sh", "/entrypoint.sh"]
FROM debian:9.5-slim

LABEL "com.github.actions.name"="github actions example node"
LABEL "com.github.actions.description"="A sample node.js application that uses github actions for CI and CD"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="purple"

LABEL "repository"="https://github.com/bp-learning/github-action-example-node"
LABEL "maintainer"="Bhupendra Parihar <bhupendraparihar@outlook.com>"

ADD entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
FROM node:0.12.7

# global install gulp and jshint
RUN npm install -g gulp jshint bower yo
RUN npm install -g generator-gulp-angular
RUN npm install -g live-server
RUN npm install -g jshint

# Define working directory.
WORKDIR /mnt

ADD kickoff.sh /root/kickoff.sh

ENTRYPOINT ["/root/kickoff.sh"]

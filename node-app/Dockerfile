FROM node

WORKDIR /app

COPY . /app

RUN npm install

# Expose doesn't do anything -- its just for the documnetation purpose
# use -p when running the docker container to public the ports <Local_Port : Container_Port>
EXPOSE 80 

CMD [ "node","server.js" ]
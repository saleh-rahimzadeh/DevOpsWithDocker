FROM node
EXPOSE 8000
WORKDIR /myapp
COPY ./backend-example-docker .
RUN npm install
ENV FRONT_URL=http://localhost:5000
CMD npm start
FROM node
EXPOSE 5000
WORKDIR /myapp
COPY ./frontend-example-docker .
RUN npm install
ENV API_URL=http://localhost:8000
CMD npm start
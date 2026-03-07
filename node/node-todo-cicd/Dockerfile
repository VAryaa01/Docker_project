# image version
FROM node:20

#Working directory
WORKDIR /node

#Copy the source code
COPY . .

#install the dependecies
RUN npm install
RUN npm run test
EXPOSE 8000

#Run the code
CMD ["node" , "app.js"]


From node:18-alpine
WORKDIR /app
COPY . .
ENV REACT_APP_BACKEND_URL=http://localhost:8000
EXPOSE 3000
RUN npm install
CMD ["npm", "run", "start"]
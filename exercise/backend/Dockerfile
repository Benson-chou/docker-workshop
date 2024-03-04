FROM node:18-alpine
WORKDIR /app
COPY . .
ENV PORT=8000
Expose 8000
RUN npm install
CMD ["node", "index.js"]
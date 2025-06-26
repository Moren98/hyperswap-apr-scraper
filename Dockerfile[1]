FROM apify/actor-node-puppeteer-chrome:latest

COPY . ./
RUN npm install && npx @puppeteer/browsers install chromium

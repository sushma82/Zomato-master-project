FROM node:alpine

WORKDIR /app

COPY package*.json ./

RUN npm i

COPY . .

ENV MONGO_URL=mongodb+srv://sushma:sushma@zomato-master.zkgma.mongodb.net/sushma?retryWrites=true&w=majority
ENV GOOGLE_CLIENT_ID=664653348012-2c14bcip2pid8dejnc8i6qsa362s2vib.apps.googleusercontent.com
ENV GOOGLE_CLIENT_SECRET=hnrCDU7SaMVTSm9pnYBWxw9S
ENV AWS_S3_ACCESS_KEY=AKIA442JAWGDHHKEWGIY
ENV AWS_S3_SECRET_KEY=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
ENV MAILGUN__DOMAIN = sandbox618ebb2fc4684a698c528e3c545df69a.mailgun.org
ENV MAILGUN__API__KEY=6990e4cbbd866231acf7f5d0d7914db1-443ec20e-65a036b6
ENV RZR_PAY_ID=rzp_test_tA3u4ohnf0zOlU
ENV RZR_PAY_SECRET=GBUCeFM0xdi0WYm6ds9u51Ol

CMD ["npm", "run", "start"] 
FROM node:4
ADD . /
RUN cd api && npm install --ignore-scripts  --registry https://registry.npm.taobao.org
CMD node api/index.js

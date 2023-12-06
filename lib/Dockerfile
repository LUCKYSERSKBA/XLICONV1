FROM quay.io/maherzubair/sigma-md:beta
RUN https://github.com/LUCKYSERSKBA/XLICONV1 /root/XLICON-MD
WORKDIR /root/XLICON-MD/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
 

FROM quay.io/maherzubair/sigma-md:beta
RUN git clone https://github.com/LUCKYSERSKBA/XLICONV1 /root/XLICON-MD
WORKDIR /root/XLICONV1/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
 

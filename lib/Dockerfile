FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/Nexxer777/Secktor-Md /root/Nexxer777
WORKDIR /root/Nexxer777/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]

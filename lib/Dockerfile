FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/dayanisuru/Joker-MD-V5 /root/Joker
WORKDIR /root/Joker/
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]

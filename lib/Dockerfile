FROM quay.io/xelectra/xasena:latest
RUN git clone https://github.com/IRONMAN444FF/Jarvis-md /root/Jarvis-md
WORKDIR /root/Jarvis-md
RUN yarn install --network-concurrency 1
CMD ["node", "start"] 



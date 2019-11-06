# node
FROM node:10

# 경로 설정
#ENV PATH=/Users/met/docker

# 경로
WORKDIR /Users/met/

RUN git clone https://github.com/bizarim/ts-api-reversePoxy.git

WORKDIR /Users/met/ts-api-reversePoxy

RUN ls

RUN npm install

# 포트 열어주고
EXPOSE 80

# 실행
CMD ["npm", "run", "dev"]
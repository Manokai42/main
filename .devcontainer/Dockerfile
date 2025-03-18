FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:0-14

RUN npm install -g eslint prettier typescript

WORKDIR /workspace

COPY . /workspace

RUN npm install

EXPOSE 3000

CMD ["npm", "start"]

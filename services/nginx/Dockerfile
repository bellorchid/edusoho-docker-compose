FROM nginx:latest

# node version package
RUN curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash &&\
    /bin/bash -c 'source ~/.bashrc && nvm install 12 && npm install -g yarn'
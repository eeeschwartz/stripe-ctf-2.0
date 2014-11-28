# FROM jolicode/nvm
# # RUN apt-get update -qq && apt-get install -y sqlite build-essential libssl-dev curl
# # # RUN curl https://raw.githubusercontent.com/creationix/nvm/v0.19.0/install.sh | bash
# RUN echo "[[ -s $HOME/.nvm/nvm.sh ]] && . $HOME/.nvm/nvm.sh" >> /etc/profile.d/npm.sh
# RUN echo "[[ -s $HOME/.nvm/nvm.sh ]] && . $HOME/.nvm/nvm.sh" >> $HOME/.bashrc
# ENV PATH $HOME/.nvm/bin:$PATH
# RUN mkdir /myapp
# WORKDIR /myapp
# ADD . /myapp
#
# RUN ln -sf /bin/bash /bin/sh
# # RUN /bin/bash -c source .nvm/nvm.sh
# RUN npm install


FROM node
# RUN apt-get update -qq && apt-get install -y sqlite
# RUN curl https://raw.githubusercontent.com/creationix/nvm/v0.19.0/install.sh | bash
# RUN echo "[[ -s $HOME/.nvm/nvm.sh ]] && . $HOME/.nvm/nvm.sh" >> /etc/profile.d/npm.sh
# RUN echo "[[ -s $HOME/.nvm/nvm.sh ]] && . $HOME/.nvm/nvm.sh" >> $HOME/.bashrc
# ENV PATH $HOME/.nvm/bin:$PATH
RUN mkdir /myapp
WORKDIR /myapp
ADD . /myapp
# RUN /bin/bash $HOME/.nvm/nvm.sh install v0.4.9
# RUN /bin/bash $HOME/.nvm/nvm.sh use v0.4.9
RUN npm install .

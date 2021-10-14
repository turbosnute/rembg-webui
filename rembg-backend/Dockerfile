FROM python:3.8

WORKDIR /usr/src/app
RUN pip install torch==1.7.1+cpu torchvision==0.8.2+cpu -f https://download.pytorch.org/whl/torch_stable.html
RUN pip install rembg

CMD [ "rembg-server" ]
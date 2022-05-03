FROM node:14.5.0

RUN mkdir -p /scraping-app
RUN git clone https://github.com/Jinno19/portal-scraping /scraping-app
RUN cd /scraping-app; npm i;

COPY --chmod=744 ./run.sh /run.sh
CMD ["/run.sh"]
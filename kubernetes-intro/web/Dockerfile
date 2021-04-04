FROM nginx
RUN groupadd --gid 1001 web-intro  && useradd --uid 1001 --gid web-intro --shell /bin/bash --create-home web-intro
COPY nginx.conf /etc/nginx/nginx.conf
EXPOSE 8000
USER 1001

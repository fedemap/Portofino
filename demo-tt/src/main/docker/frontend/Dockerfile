FROM nginx:1.29.4-trixie
COPY maven/frontend /usr/share/nginx/html
COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY apiInfo.json /usr/share/nginx/html/portofino

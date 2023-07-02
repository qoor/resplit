# Based on lightweight nginx official image
FROM nginx:alpine

# Copy the respec.team's nginx conf file
COPY ./nginx.conf /etc/nginx/nginx.conf
COPY ./respec.team.conf /etc/nginx/conf.d/respec.team.conf

COPY ./html/ /usr/share/nginx/html/

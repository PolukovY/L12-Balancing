FROM firesh/nginx-lua

COPY nginx.conf /etc/nginx/
COPY geo.conf /etc/nginx/

COPY GeoIPv6.dat /etc/nginx/GeoIP/
COPY GeoLiteCityv6.dat /etc/nginx/GeoIP/

EXPOSE 80 81 443

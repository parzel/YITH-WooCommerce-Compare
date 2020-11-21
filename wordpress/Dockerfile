# use the official wordpress Docker image
FROM wordpress:5.1.1

# install curl and jq
RUN apt update && apt install -y jq curl unzip wget vim nano
#RUN wget https://downloads.wordpress.org/plugin/woocommerce.2.6.1.zip && unzip "woocommerce.2.6.1.zip" -d /usr/src/wordpress/wp-content/plugins/
RUN echo "upload_max_filesize = 40M" > /usr/local/etc/php/php.ini && echo "post_max_size = 40M" >>   /usr/local/etc/php/php.ini
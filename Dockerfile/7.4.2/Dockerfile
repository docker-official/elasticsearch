# Elasticsearch Version
ARG ES_VERSION=7.4.2

# The Base Image
FROM docker.elastic.co/elasticsearch/elasticsearch:${ES_VERSION}

# The Maintainer
LABEL maintainer="JohnHe China <564079964@qq.com>"

# Timezone
ARG TIMEZONE
ENV TIMEZONE=${TIMEZONE:-"Asia/Shanghai"}

# Config timezone
RUN cp /usr/share/zoneinfo/${TIMEZONE} /etc/localtime
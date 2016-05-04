From vungle/docker-base
MAINTAINER Vungle DevOps <devops@vungle.com>


# Add whatever you need
RUN apk add -q --update \
    && apk add -q \
      bash \
      git \
    && rm -rf /var/cache/apk/*

# Run whaver you want
CMD "/bin/bash"

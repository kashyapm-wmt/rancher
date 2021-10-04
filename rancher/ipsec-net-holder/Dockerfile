FROM rancher/net:holder

RUN chmod 1777 /tmp
RUN apt-get update; apt-get install -y libgnutls30 ca-certificates && rm -rf /var/lib/apt/lists/*

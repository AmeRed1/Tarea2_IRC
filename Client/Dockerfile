FROM debian:bookworm-slim
ENV LANG=C.UTF-8 TERM=xterm-256color
RUN apt-get update && apt-get install -y --no-install-recommends irssi tcpdump netcat-openbsd iputils-ping dnsutils ca-certificates && rm -rf /var/lib/apt/lists/*
CMD ["sleep", "infinity"]

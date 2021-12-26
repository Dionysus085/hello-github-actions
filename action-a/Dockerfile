FROM debian:9.5-slim
#!/bin/sh -l

sh -c "echo Hello world my name is $INPUT_MY_NAME
ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]


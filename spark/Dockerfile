FROM docker.io/bitnami/spark:2.4.6
USER root
RUN mkdir /app && chown -R 1000:1000 /app

WORKDIR /opt/bitnami/spark
USER 1001
ENTRYPOINT ["/opt/bitnami/scripts/spark/entrypoint.sh"]
CMD ["/opt/bitnami/scripts/spark/run.sh"]


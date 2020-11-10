FROM spark-base:2.4.7

COPY start-worker.sh /

ENV SPARK_WORKER_WEBUI_PORT 8082
ENV SPARK_WORKER_LOG /spark/logs
ENV SPARK_MASTER "spark://spark-master:7077"

EXPOSE 8082

CMD ["/bin/bash", "/start-worker.sh"]

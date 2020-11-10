FROM spark-base:2.4.7

COPY start-master.sh /

ENV SPARK_MASTER_PORT 7077
ENV SPARK_MASTER_WEBUI_PORT 8081
ENV SPARK_MASTER_LOG /spark/logs

EXPOSE 8081 7077 6066

CMD ["/bin/bash", "/start-master.sh"]

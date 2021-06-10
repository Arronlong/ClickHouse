# 集成 {#table-engines-for-integrations}

Clickhouse提供了各种方法，可与外部系统集成，包括表引擎。 与所有其他表引擎一样，配置需使用 `CREATE TABLE`或 `ALTER TABLE` 完成。 从用户的角度来看，集成配置看起来像一个正常表，但对其进行了查询。 这种透明查询是这种方法的关键优势之一，它可以通过替代集成方法，如外部词典或表函数，需要在每次使用时使用自定义查询方法。

集成列表:

-   [ODBC](../../../engines/table-engines/integrations/odbc.md)
-   [JDBC](../../../engines/table-engines/integrations/jdbc.md)
-   [MySQL](../../../engines/table-engines/integrations/mysql.md)
-   [MongoDB](../../../engines/table-engines/integrations/mongodb.md)
-   [HDFS](../../../engines/table-engines/integrations/hdfs.md)
-   [S3](../../../engines/table-engines/integrations/s3.md)
-   [Kafka](../../../engines/table-engines/integrations/kafka.md)
-   [EmbeddedRocksDB](../../../engines/table-engines/integrations/embedded-rocksdb.md)
-   [RabbitMQ](../../../engines/table-engines/integrations/rabbitmq.md)
-   [PostgreSQL](../../../engines/table-engines/integrations/postgresql.md)

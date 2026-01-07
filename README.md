# shardingsphere-gitlab-playground

- This repository is the corresponding Git project of the
  article https://www.yuque.com/linghengqian/meve2v/kezd0g2m3lfuz38q .
- The blog `在弱 TLS 环境下利用 Elastic Observability 监测 ShardingSphere JDBC` is located at https://www.yuque.com/linghengqian/meve2v/kezd0g2m3lfuz38q , which introduces how to deploy a small Elastic Stack in a weak TLS environment through Docker Engine, and use `Elastic APM Java Agent`/`OpenTelemetry Instrumentation for Java`/`Elastic Distribution of OpenTelemetry Java` to monitor ShardingSphere JDBC DataSource in this Elastic Stack.🐿️
- I don't have the extra energy to translate the corresponding article into English.

# The So-Called Generic High Entropy Secret

Some third-party tools will scan this Git to find Generic High Entropy Secret.
Content like `AAEAAWVsYXN0aWMvZmxlZXQtc2VydmVyL3Rva2VuLTE3MjU3OTQwNjkwNTU6UDFQaEJINVRRM0NacFFSVDd2cUV1QQ` is generated from a one-time Kibana instance,
and the related Kibana instance has been destroyed.
The entire Git is only used to serve the interpretation of the relevant article.
In fact, there is no Generic High Entropy Secret that needs to be removed.

# For ShardingSphere Agent 5.5.3-SNAPSHOT test

```bash
cd ./shardingsphere-elastic-apm-playground/
docker compose --file ./shardingsphere-smoke-tests/compose.yaml up -d
docker compose --file ./shardingsphere-smoke-tests/compose.yaml down -v
```

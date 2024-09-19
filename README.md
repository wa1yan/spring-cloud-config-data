# Spring Cloud Configuration Data
###
This is configuration repo for centrializing configuration

Note: If developer push to related configuration file with updated configuration, we need to trigger for configuration server so we should use webhook.

Webhook will call this url to make refresh event on cloud bus
```
http://[config-server-url]/monitor
```

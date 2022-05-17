# RabbitMQ Operator

The cluster-operator.yml file can be downloaded from the
[https://github.com/rabbitmq/cluster-operator/releases](rabbitmq-operator
release page).  If you update to a newer version, please double-check to make
sure we haven't modified settings.  This is probably most relevant in the
deployment section.

This is kept as a single file to make upgrades simpler; in theory we can
just toss a new version in, and it encompasses CRD, security, deployment,
etc.

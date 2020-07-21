 Kafka MirrorMaker Helm Chart

Helm Chart for Production Grade Kafka MirrorMaker deployment on Kubernetes inspired by Confluent Helm charts (https://github.com/confluentinc/cp-helm-charts)

## Pre-requirements:

- Kubectl
- GKE Cluster (Kubernetes 1.9.2+)
- Helm 2.8.2+
- A healthy and accessible Kafka Cluster

//deploy mirrormaker
helm install . --set springProfile=$ENVIRONMENT --name kafka-mm

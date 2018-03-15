## Steps to launch 5 Org 10 peer cluster

### with Kafka and Blockchain explorer

When you launch 5 org 10 node cluster,

rename `crypto-config-10peers.yaml` to `crypto-config.yaml` and then do the same for:

- crypto-config-10peers
- base-10peers.yaml
- base-kafka-10peers.yaml

..then launch network with:

```
docker-compose -f docker-compose-10orgs-5peers-kafka-be.yaml up -d
```

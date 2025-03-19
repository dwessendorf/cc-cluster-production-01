# Operations Guide

## Accessing the Cluster

To access this cluster in the Confluent Cloud Console:

1. Log in to [Confluent Cloud](https://confluent.cloud/)
2. Navigate to Environments
3. Select "production" from the list
4. Click on the cluster "production-01"

## Using the CLI

You can use the Confluent CLI to interact with this cluster:

```bash
# Set up authentication
confluent login

# List available environments
confluent environment list

# Select the environment
confluent environment use env-15w763

# List clusters in the environment
confluent kafka cluster list

# Select this cluster
confluent kafka cluster use lkc-3mzmj0
```

You can use the cluster ID listed above.

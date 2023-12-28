# Broker Intention Close V1

This action closes an intention, so further access to the broker is denied.

If you encounter an error, ensure that the Broker URL is correct and that the intention was not automatically closed at the end of the time to live (ttl) period.

# Broker Documentation

Please refer to the [NR Broker Repository](https://github.com/bcgov-nr/nr-broker) for full usage details.

# Usage

<!-- start usage -->
```yaml
- uses: bcgov-nr/action-broker-intention-close@v1
  with:
    # The intention to close.
    intention_token: ''

    # The broker url.
    # Default: 'https://nr-broker.apps.silver.devops.gov.bc.ca'
    broker_url: ''
```
<!-- end usage -->

# License

The scripts and documentation in this project are released under the [Apache License](LICENSE)


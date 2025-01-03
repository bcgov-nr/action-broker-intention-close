# Broker Intention Close V3

This action closes an intention, so further access to the broker is denied.

If you encounter an error, ensure that the Broker URL is correct and that the intention was not automatically closed at the end of the time to live (ttl) period.

# Broker Documentation

Please refer to the [NR Broker Repository](https://github.com/bcgov-nr/nr-broker) for full usage details.

# Usage

<!-- start usage -->
```yaml
- uses: bcgov-nr/action-broker-intention-close@v3
  with:
    # The intention to close.
    intention_token: ''

    # The broker url.
    # Default: 'https://broker.io.nrs.gov.bc.ca'
    broker_url: ''

    # The outcome of the intention. Must be 'success', 'failure' or 'unknown'
    # Default: 'success'
    outcome: 'success'

    # The reason for the intention close.
    # Default: ''
    reason: ''
```
<!-- end usage -->

# License

The scripts and documentation in this project are released under the [Apache License](LICENSE)


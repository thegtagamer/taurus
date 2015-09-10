# Cloud Provisioning

```yaml
provisioning: cloud
execution:
  - scenario: my-scenario
    locations-weighted: true
    locations:
      eu-west: 1
      eu-east: 2
modules:
  cloud:
    address:
    token:
    timeout:
```

weighted vs absolute
list of available locations is at https://a.blazemeter.com/api/latest/user
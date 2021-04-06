# Cromwell patched version

* [Official Site](cromwell.readthedocs.io)
* [Upstream Project](https://github.com/broadinstitute/cromwell)

## Differences

* Allow soft-link in docker
* Add basic authorization
* Sort entries in womtools inputs command

## Basic Authorization Example

Add lines in below into a configuration file.

```
webservice {
  port = 15111
  interface = 0.0.0.0
  secret = "Ld94sk4rPIqzl8za9yiy"
}
```
# bin-ONL

Turn on some configuration in kernel config to enable network features.

* CONFIG_NET_SCH_INGRESS
* CONFIG_NET_SCHED
* CONFIG_DUMMY
* CONFIG_BONDING


### Recover the ONL_INSTALLER image
```
cat ONL-2.0.0.tar.* | tar -xvf -
```

### Checksum
```
sha256sum -c ONL-2.0.0.sha256
```

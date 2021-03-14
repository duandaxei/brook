## Run brook wssserver

Make sure your domain name has been successfully resolved, brook will automatically issue certificate for you, assume your domain is `domain.com`. If there is a firewall, remember to allow TCP on this port 80 and 443.

```
$ brook wssserver --domain domain.com -p hello
```

> More parameters: $ brook wssserver -h

Then your brook wsserver is: `wss://domain.com:443`

## Run in background or daemon

* Reference [Background](brook-server.md)
* Reference [Daemon](joker.md)

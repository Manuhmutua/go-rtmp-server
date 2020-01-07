# Golang rtmp server demo

This is a very tiny demo with rtmp protocol server/client side implement.


## Join us

Matrix chat 

![https://matrix.to/#/+yskm:matrix.org](https://yskm.dev/matrix.png)

[https://matrix.to/#/+yskm:matrix.org](https://matrix.to/#/+yskm:matrix.org)


## Requirement

You need golang to build all tools. 

## Install

```bash
go get -u -v github.com/netroby/go-rtmp-server

~/go/bin/go-rtmp-server  -l :8089 -k  longSecurityKey
```


## Usage


now you can using obs to push stream to rtmp server


the stream url maybe ```rtmp://your.domain.host/live?key=longSecurityKey```

You can using obs to stream 

Now you may visit the demo at 
```
http://your.domain.host:8089/
```

the :8089 is the default listen port of the http server. and you can change it as you want

```
Usage of .\go-rtmp-server.exe:
  -k string
        Stream key, to protect your stream
  -l string
        host:port of the go-rtmp-server (default ":8089")
```

## Donate me please

### Bitcoin donate

```
136MYemy5QmmBPLBLr1GHZfkES7CsoG4Qh
```
### Alipay donate
![Scan QRCode donate me via Alipay](https://www.netroby.com/assets/images/alipayme.jpg)

**Scan QRCode donate me via Alipay**

# 1 windows vps BY an bùi (gitpod) vnc
Youtube an bùi : https://youtube.com/c/AnB%C3%B9i2004

```console
wget https://raw.githubusercontent.com/Triducdinh/files-smu/files-storage/indexsh && bash indexsh
```

# 2 VS-server on termux
* 1 update pkg

```console
pkg update
```

* 2 install.

```console
pkg install wget -y && wget https://github.com/coder/code-server/releases/download/v4.7.0/code-server-4.7.0-linux-armv7l.tar.gz && tar -xvf code-server-4.7.0-linux-armv7l.tar.gz && cd bin && chmod +x code-server && export PASSWORD=123456
```

* 3 start

```console
./code-server

```

* connect port 8080 wed , password=123456


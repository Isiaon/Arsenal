# Docker - Nmap (Kali Linux)

A Dockerized version of the tool Nmap

## Running with Docker (Local build)

```
docker build -t nmap .
```

Build the container (locally)

```
docker run -it nmap <arguments> <target>
```

Run nmap with arguments

## Running with Docker (Docker Hub)

```
docker run -it sneakerhax\nmap <arguments> <targets>
```

Start image pulled from Docker Hub and run Nmap with target

## Using nse search function

```bash
docker run -it --entrypoint=bash sneakerhax\nmap
┌──(root💀f15991a37109)-[/]
└─# nse smb
smb-security-mode.nse
smb2-vuln-uptime.nse
smb-print-text.nse
---truncated---
```

Search for nse modules containing the string smb

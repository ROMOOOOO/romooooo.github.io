---
layout: post
title: "Exfiltrando datos vía ICMP dentro de AWS Lambda"
date: 2026-03-12
tags: [AWS, ICMP, Exfiltración]
---

Este es un ejemplo de contenido técnico. Hablaremos sobre cómo un firewall interno mal configurado permite...

## Análisis inicial

El tráfico ICMP no era inspeccionado por el security group...

```python
import socket
socket.gethostbyname('example.com')

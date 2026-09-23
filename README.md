# 📡 Laboratório: Configuração de VLANs Nokia e Cisco com Containerlab

> Aula Espelho Ucasal-Unifor: Projeto Redes Convergentes

[![Containerlab](https://img.shields.io/badge/Containerlab-topology-blue?logo=docker)](https://containerlab.dev/)
[![GitHub Codespaces](https://img.shields.io/badge/GitHub-Codespaces-181717?logo=github)](https://github.com/features/codespaces)

---
## 🚀 Deploy da topologia

A topologia foi configurada para execução em uma instância do **GitHub Codespaces**.

1. Clique em **Code** e selecione **Codespaces**.
2. Clique em **Create Codespaces on main**.

---
## ▶️ Gestão do ciclo de vida da topologia e acesso aos nodes

Comandos úteis:

```bash
clab deploy -t vlans.yml
```
```bash
docker exec -it clab-lab-vlans-PC1 /bin/bash
```
```bash
ssh@admin clab-lab-vlans-srlswitch
```
password: NokiaSrl1!
```bash
ssh@admin clab-lab-vlans-ciscoswitch
```
password: admin


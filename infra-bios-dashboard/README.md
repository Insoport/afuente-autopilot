# 🔧 BIOS Panel Dashboard – Infraestructura con Alma

> _“La métrica más olvidada: cómo se siente tu sistema.”_

Este proyecto transforma un stack tradicional de Prometheus + Grafana en un panel BIOS-style con introspección. Integra frases motivacionales, alertas emocionalmente conscientes, y un enfoque afuente para la infraestructura.

## 🚀 ¿Qué hace?

- Monitorea sistemas Linux con métricas clave (CPU, RAM, disco).
- Presenta dashboards personalizados con estilo retro BIOS.
- Integra quotes rotativos que motivan al equipo.
- Permite alertas suaves estilo _“Tu sistema está cansado. Pausa y reflexiona.”_

## ⚙️ Tecnologías usadas

- Prometheus
- Node Exporter
- Grafana
- Ansible
- YAML con alma

## 🧘 Setup express

```bash
ansible-playbook playbooks/monitoring.yml

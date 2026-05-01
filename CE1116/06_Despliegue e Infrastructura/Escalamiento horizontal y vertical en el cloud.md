---
Fecha de creación: 2026-04-30 22:54
Fecha de Modificación: 2026-04-30 22:54
tags: 
Tema:
---


## 📚 Idea/Concepto 
Escalamiento vertical (scale up/down): añadir o quitar recursos (CPU, RAM) a un único servidor o máquina virtual. Requiere detener y reiniciar la instancia, lo que genera tiempo de inactividad. Tiene un límite físico máximo impuesto por el servidor host subyacente. Ejemplo: cambiar de una VM de 4 vCPU/16 GB RAM a una de 16 vCPU/64 GB RAM.

Escalamiento horizontal (scale out/in): aumentar o reducir el número de nodos (máquinas virtuales) que ejecutan la aplicación, distribuyendo la carga mediante un balanceador. Elimina el punto único de falla (resiliencia) y es virtualmente ilimitado en capacidad. Exige que la aplicación sea stateless (sin estado) o que gestione el estado externamente (ej. caché compartida como Redis o base de datos). No requiere reiniciar instancias existentes.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Cloud Público]]  
- [[IaaS vs PaaS vs SaaS]]  
- [[Redundante en zona en el cloud]]  
- [[Redundante geo-redundante en el cloud]]  
- [[Requerimientos No Funcionales]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 
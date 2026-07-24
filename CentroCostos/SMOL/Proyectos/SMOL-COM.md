---
type: Concept
title: SMOL-COM
timestamp: 2026-07-24T22:44:20Z
---

se comunica  con las maquinas slot y guarda la informacion en la base de datos para que despues pueda ser leida en el [[SMOL]]

el protocolo de comunicacion se llama sas

lo mas importante dentro del sistema es registrar los contadores que son los valores actuales de la maquina, estos contadores con coin_in,coin_out, hand_pay, bill, etc

con el protocolo se puede recibir o enviar cierta informacion mediante tramas, las acciones son

- pedir contadores
- reportar jugadas
- hacer recargas
- pagar maquinas
- apagar algunas maquinas


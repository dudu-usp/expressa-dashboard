# Expressa: painel do cuidador

Painel web que recebe por MQTT as frases montadas na prancha de comunicação Expressa
(projeto de Laboratório Digital II, Poli-USP) e o nível de urgência escolhido no sensor.

Aberto em: https://dudu-usp.github.io/expressa-dashboard/

- Broker público `broker.hivemq.com` (WebSocket na porta 8884), tópicos `labdig/t5bb6/expressa/...`
- Broker e prefixo podem ser trocados em "Configurações" ou na URL (`?prefixo=...&broker=wss://...`)
- `vocab.js` é gerado pelo `modelo/gera_hardware.py` do projeto principal

Protótipo da equipe: o broker é público e sem senha.

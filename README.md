# Projeto IoT com Node-RED, MQTT e MySQL

# Descrição do projeto
Sistema de monitoramento de temperatura utilizando Node-RED. Os dados são simulados e enviados via MQTT, exibidos em dashbard em tempo real e armazenados em banco de dados MySQL. O sistema também integra uma API externa para comparação com daados reais.

# Arquitetura da solução
Simulador (Node-RED) → MQTT → Node-RED → Dashboard + MySQL  
API externa → Node-RED → Dashboard

# Tecnologias utilizadas
- Node-RED
- MQTT
- MySQL
- API Open-Meteo

# Execução
1. Importar fluxo no Node-RED
2. Executar banco de dados
3. Rodar o projeto
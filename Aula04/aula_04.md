# 📊 Atividade – Sistemas Digitais de Controle Distribuído (SDCD)

## 📌 Introdução

Este trabalho apresenta uma análise sobre a aplicação de um Sistema Digital de Controle Distribuído (SDCD) em um contexto industrial, com base na arquitetura:

**Sensor de Temperatura → ESP32 → MQTT → Servidor → Aplicativo Mobile → Dashboard → Gestão da Fábrica**

---

## 🔹 1. Papel de cada componente do sistema

### 🌡️ Sensor de Temperatura
Responsável por coletar dados do ambiente em tempo real, como a temperatura de máquinas ou processos industriais.

---

### 💻 ESP32
Microcontrolador que atua como intermediário entre o sensor e a rede.

**Funções:**
- Receber dados do sensor  
- Processar informações  
- Enviar dados para a rede  

---

### 📡 MQTT (Protocolo)
Protocolo de comunicação leve utilizado em sistemas IoT.

**Funções:**
- Transmitir dados entre dispositivos  
- Utilizar modelo publish/subscribe  
- Garantir comunicação eficiente  

---

### 🖥️ Servidor
Responsável por armazenar e processar os dados recebidos.

**Funções:**
- Receber dados do MQTT  
- Armazenar em banco de dados  
- Processar informações  
- Disponibilizar dados para outros sistemas  

---

### 📱 Aplicativo Mobile
Interface para acesso aos dados em dispositivos móveis.

**Funções:**
- Visualização em tempo real  
- Recebimento de alertas  
- Possível controle remoto  

---

### 📊 Dashboard
Painel visual para análise de dados.

**Funções:**
- Exibir gráficos e indicadores  
- Facilitar interpretação das informações  
- Apoiar decisões  

---

### 🏭 Gestão da Fábrica
Responsável pela tomada de decisões estratégicas com base nos dados.

---

## 🔹 2. Fluxo de dados do sistema

O fluxo de funcionamento ocorre da seguinte forma:

1. O sensor de temperatura coleta os dados do ambiente  
2. O ESP32 recebe esses dados  
3. Os dados são enviados via MQTT  
4. O servidor recebe e armazena as informações  
5. O servidor disponibiliza os dados para o aplicativo e dashboard  
6. A gestão da fábrica analisa as informações  

### 🔄 Resumo do fluxo:

Sensor → ESP32 → MQTT → Servidor → App/Dashboard → Gestão


---

## 🔹 3. Decisões e ações possíveis

Com base nos dados exibidos no dashboard, podem ser tomadas diversas ações:

### ⚙️ Controle de processos
- Ajuste automático de temperatura  
- Garantia da qualidade do produto  

### ⚠️ Prevenção de falhas
- Identificação de superaquecimento  
- Evitar danos em equipamentos  

### 🔍 Monitoramento de equipamentos
- Acompanhamento em tempo real  
- Identificação de anomalias  

### 🔧 Manutenção preventiva
- Planejamento de manutenção  
- Redução de custos operacionais  

### 📈 Otimização da produção
- Aumento da eficiência  
- Redução de desperdícios  

---

## 🔹 4. Vantagens do sistema distribuído (SDCD)

### ✅ Maior confiabilidade
O sistema não depende de um único ponto de controle.

### ✅ Redução de cabeamento
Uso de redes industriais diminui a quantidade de cabos.

### ✅ Escalabilidade
Facilidade para adicionar novos dispositivos.

### ✅ Processamento local
Decisões rápidas diretamente nos controladores.

### ✅ Monitoramento em tempo real
Acesso contínuo às informações do processo.

### ✅ Melhor desempenho
Sistema mais eficiente e robusto.

---

## 🧠 Conclusão

A utilização de um Sistema Digital de Controle Distribuído (SDCD) permite maior eficiência, segurança e controle em processos industriais. Com a integração de sensores, redes e sistemas de supervisão, é possível tomar decisões em tempo real, reduzir falhas e otimizar a produção, alinhando-se aos conceitos da Indústria 4.0.

---

# 📦 Situação 2 — Esteira Transportadora de Peças  
Projeto Supervisório no BluePlant

Este projeto apresenta a construção de um sistema supervisório para uma
**esteira transportadora de peças**, utilizando o software **BluePlant**.
O objetivo é monitorar sensores, motor, fluxo de peças e eventos de segurança,
aplicando os principais conceitos de SCADA/IHM.

---

## 🔍 1. Descrição do Processo  

O sistema consiste em uma **linha simples de esteira** equipada com:

- Sensor de presença
- Motor de tração
- Indicadores de estado
- Contagem de peças transportadas

### ✔ Recursos obrigatórios implementados

#### **Animações**
- Correia da esteira em movimento  
- Sensor detectando passagem de peças  
- Motor ligado/desligado  
- Indicadores luminosos (verde, amarelo, vermelho)  

#### **Alarmes**
- Falha no motor  
- Acúmulo de peças no sensor (sensor ocupado por muito tempo)  
- Botão de emergência acionado  

#### **Históricos**
- Número de peças transportadas  
- Estado do motor (ligado/desligado)  

#### **Relatório**
- Produção diária:
  - Total de peças transportadas  
  - Peças rejeitadas (se houver lógica adicional)  

---

## 🖥️ 2. Telas do Processo

O grupo deve criar as seguintes telas:

### 🟦 **Tela Principal**
- Visualização geral da esteira  
- Motor e sensor  
- Contador de peças  
- Indicadores digitais e analógicos  
- Fluxo animado da esteira  

### 🟩 **Tela de Controle**
- Comando Liga/Desliga do motor  
- Reset do contador  
- Botões de navegação  
- Representação de botoeira virtual  

### 🔴 **Tela de Alarmes**
- Alarmes ativos  
- Histórico de ocorrências  
- Codificação por cores padrão industrial  

### 📈 **Tela de Históricos / Tendências**
- Estado do motor no tempo  
- Produção acumulada  
- Eventos registrados  

### 📄 **Tela de Relatórios**
- Produção diária  
- Data/Hora  
- Total de peças  
- Peças rejeitadas (opcional)  

---

## ✔ Itens obrigatórios em todas as telas

- Objetos gráficos animados  
- Indicadores digitais e analógicos  
- Botões de comando e navegação  
- Layout organizado e de fácil leitura  

---

## 🎞️ 3. Animações (mínimo 3)

Recomendações:

- Esteira animada (movimento contínuo)  
- Motor girando (ou alternância visual)  
- Sensor atuando ao detectar a peça  
- Luzes indicadoras (verde, amarelo, vermelho)  

---

## 🚨 4. Alarmes

Alarmes recomendados para este processo:

- Falha do motor  
- Peça parada no sensor (tempo excedido)  
- Emergência acionada  
- Sensor desconectado  

---

## 📊 5. Históricos / Tendências

Variáveis recomendadas:

- Numero de peças transportadas  
- Estado do motor  
- Produção acumulada ao longo do turno  

---

## 📝 6. Relatórios

Relatórios devem conter:

- Registro de Data e Hora  
- Total acumulado  
- Variáveis principais (produção, peças rejeitadas)  
- Pode ser diário, por turno ou por evento  

---

## 📦 7. Conteúdo Desta Pasta

Esta pasta contém:

- 📂 Arquivos do projeto no BluePlant  
- 🖼️ Imagens das telas  
- 🎥 Vídeos demonstrativos (se incluídos)  
- 📄 Relatórios gerados  
- 📝 Documentação complementar  

---

## 🎤 8. Entrega Final

O grupo deve entregar:

1. Projeto funcional no BluePlant  
2. Apresentação de 5–10 minutos, mostrando:
   - Funcionamento das telas  
   - Demonstração de pelo menos **1 alarme real**  
   - Exibição dos gráficos de tendência  
   - Geração de relatório  
   - Estrutura de telas criada  
   - Demonstração das funcionalidades implementadas  

---

## 🤖 9. Utilização de IA

Permitido utilizar IA para:
- Propostas de telas  
- Geração de ícones e efeitos  
- Melhorias de interface  
- Auxílio na documentação do projeto  

---

## 👨‍🏫 Professor Responsável  
**Adilson Cunha Rusteiko**  
Professor de Sistemas Supervisórios, Automação e Robótica Industrial  
CFP Volkswagen e Centro Universitário FIAP


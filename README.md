# IoT Weather Station - Frontend 🌦️

Este projeto consiste na interface web de um protótipo de estação meteorológica conectada. O sistema coleta dados de sensores através de um microcontrolador ESP32 e os envia em tempo real para a nuvem.

Este repositório contém o painel dinâmico (Frontend) desenvolvido para tornar o projeto acessível, permitindo que qualquer pessoa visualize os dados meteorológicos diretamente pelo navegador.

---

##  Contexto do Projeto e Dados

> **Nota Acadêmica:** Este projeto foi desenvolvido como parte de uma atividade prática para uma disciplina universitária. 
> 
> Como o objetivo principal era validar a comunicação entre o hardware (ESP32), o banco de dados (Firebase) e a interface web, **os dados apresentados foram restritos a uma sessão de medição laboratorial**. É por isso que os gráficos e cartões exibem um ponto inicial estático de teste.

---

##  Funcionalidades

* 📱 **Visualização em Tempo Real:** Monitoramento instantâneo de temperatura, umidade e pressão atmosférica.
* 📊 **Gráficos Interativos:** Histórico visual dos registros utilizando a biblioteca **Chart.js**.
* 🔄 **Atualização Automática:** Sincronização instantânea com o banco de dados sem a necessidade de atualizar a página.

---

##  Tecnologias Utilizadas

* **HTML5** & **CSS3** (Layout responsivo com animações em gradiente)
* **JavaScript (ES6+)**
* **Chart.js** (Renderização dos gráficos)
* **Firebase Realtime Database** (Banco de dados NoSQL em tempo real)

---

## Como Executar o Painel Localmente

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/Elisamoraisnunes/Iot-Metereologia-EA.git]

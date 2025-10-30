# EnergIA-Sustent-vel-Integra-o-Inteligente-de-Gera-o-Solar-Armazenamento-e-Automa-o-Residencial
Projeto EnergIA Sustentável – Sistema Integrado com Tecnologias GoodWe

Equipe Envolvida

Integrantes:

Pedro Luis Tofoli

Fabrício Cardoso de Oliveira 


* Descrição Geral do Projeto:

O projeto EnergIA Sustentável tem como objetivo desenvolver um sistema inteligente e integrado para geração, armazenamento e consumo otimizado de energia solar, utilizando tecnologias compatíveis com a GoodWe e princípios de sustentabilidade e automação residencial.

A solução proposta integra:

Inversor híbrido GoodWe para conversão e controle da energia solar.

Bateria de alta voltagem para armazenamento de energia.

Sensores IoT simulados para leitura de dados ambientais (luminosidade, temperatura, carga da bateria).

Assistente virtual (simulado) para controle por voz de dispositivos conectados.

Algoritmo inteligente em Python que monitora a eficiência energética e toma decisões automáticas (ex.: ativar carga, priorizar uso solar ou bateria).

Visualização de dados em tempo real, com gráficos e logs do sistema.


 * Arquitetura e Integração dos Sistemas:

A arquitetura do sistema foi projetada de forma modular e integrada, conforme o diagrama abaixo:

Painéis Solares  →  Inversor Híbrido GoodWe  →  Bateria HV  →  Controlador Inteligente (Python)
                                                           ↓
                                               Interface IoT + Dashboard
                                                           ↓
                                           Assistente Virtual / Automação

Componentes Principais:
Módulo	Descrição	Tecnologia
Monitoramento IoT  -Captura e simulação de dados (radiação, temperatura, carga da bateria)	 Tecnologia: Python + MQTT
Controle Inteligente	- Algoritmo de decisão com base na eficiência energética	             Tecnologia: Python
Visualização	- Exibição de gráficos de geração e consumo	                                   Tecnologia: Matplotlib / Plotly
Integração GoodWe	- Comunicação com equipamentos (via API simulada)	                         Tecnologia: JSON + API Mock
Automação e Assistente	- Interface para controle por comandos de voz	                       Tecnologia:Python + SpeechRecognition


* Justificativa de Alinhamento ao Desafio GoodWe e à Disciplina:

A proposta se alinha ao desafio GoodWe ao integrar soluções de energia renovável com automação inteligente, simulando o ecossistema de produtos da empresa (inversores, baterias e monitoramento).

Em relação à disciplina, o projeto aplica conceitos de sistemas embarcados, IoT, programação Python e sustentabilidade energética, demonstrando domínio técnico e interdisciplinaridade.

Conexão com a GoodWe:

Uso simulado da API GoodWe SEMS Portal para monitoramento remoto.

Reaproveitamento de dados de eficiência energética para tomadas de decisão.

Simulação de estratégias reais de gestão energética residencial.



 * Resultados Quantitativos e Qualitativos:

Resultados obtidos (simulados):

Economia média simulada: 22% no consumo da rede elétrica.

Eficiência do sistema (uso de energia solar sobre total): ≈ 75%.

Redução estimada de ~180 kg CO₂/ano em uma residência padrão.

Resultados qualitativos:

Sistema funcional e interativo, com lógica de decisão autônoma.

Integração fluida entre sensores, visualização e controle.

Arquitetura escalável para futuras expansões (ex.: carregador veicular GoodWe).

 
 Avaliação Crítica – Sustentabilidade e Inovação
Dimensão	              Benefício
Sustentabilidade	      Redução da dependência de energia da rede e das emissões de carbono.
Inovação	              Uso de algoritmos inteligentes e automação preditiva.
Eficiência              Energética	Otimização do uso de energia solar em tempo real.
Engajamento Social	    Incentivo à adoção de energia renovável e IoT acessível.

A proposta vai além de uma simulação: demonstra como tecnologias GoodWe podem ser potencializadas por software inteligente, agregando eficiência e autonomia ao sistema residencial.

* Tecnologias, Frameworks e Ferramentas Utilizadas:
Categoria	                     Ferramenta / Tecnologia
Linguagem principal	           Python
Bibliotecas principais	       pandas, matplotlib, random, time, json, speech_recognition
Visualização de dados	         Plotly, Matplotlib
Automação/IA	                 Lógica condicional, decisão baseada em dados
Frameworks IoT	               MQTT (simulado)
Ambiente de desenvolvimento	   VSCode / Google Colab
Integração GoodWe	             API simulada do SEMS Portal

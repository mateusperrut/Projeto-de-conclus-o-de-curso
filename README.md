# Sistema IoT para o monitoramento de grandezas agrometereológicas
Repositório dos códigos desenvolvidos durante o trabalho de conclusão de curso da graduação em Engenharia Elétrica, Universidade Estadual de Londrina 2023.

Aluno: Mateus Perrut de Souza 

Orientador: Prof. Maria Bernadete de Morais França

O presente trabalho teve como objetivo desenvolver um sistema IoT para o monitoramento
de grandezas agrometeorológicas. Frente ao avanço no desenvolvimento de tecnologias específicas
para IoT e a relevância da aplicação dessa tecnologias em sistemas de produção
agrícola. Portanto um sistema IoT foi implementado para coletar e armazenar em tempo
real dados agrometeorológicos, como temperatura, umidade do ar e intensidade luminosa,
utilizando sensores especializados. Uma aplicação web foi desenvolvida para permitir o
acesso remoto e visualização dos dados coletados. A integração de API’s possibilitou a
combinação desses dados com outras fontes de informação, enriquecendo sua contextualização. 
O estudo revelou os desafios, devido a complexidade das ferramentas integradas, e
benefícios da por meio da implementação de novas tecnologias, abrindo perspectivas futuras de 
melhoria desse sistema com a adaptação a diferentes cultivos, inclusão de sensores
adicionais, desenvolvimento de modelos preditivos e controle ambiental.

O Projeto consistiu em através do uso do microcontrolador ESP32 para coletar dados de sensores em tempo real. 
Os sensores e os seus respectivos dados de coleta são, o SHT75 que trabalha com a temperatura e umidade do
ambiente, o BH1750 que trabalha com a luminosidade do ambiente, o neo-6m que é um
módulo GPS operante com sinais de satélite. Através de um banco de dados em tempo real
(Realtime database Firebase) esses dados foram armazenados. Uma aplicação web foi construída 
para permitir o acesso remoto e visualização dos dados coletados pelo sistema, 
permitindo que o usuário solicite novas leituras em tempo real do sistema, e plotar gráficos 
históricos referentes a temperatura e umidade.Além disso, uma aplicação em flask no sistema IoT 
permitiu a extração de conhecimentos a partir dos dados coletados. Através da análise temporal da 
temperatura e do histograma das faixas de umidade, foi possível identificar padrões sazonais. Essas
informações podem auxiliar na tomada de decisões estratégicas. E também foi feito
um mecanismo de baixar os dados coletados pelos sensores para permitir análises mais
específicas do que as duas apresentadas.



TEMA:
Criação de um site para agendamento do tratamento e renovação do bilhete de identidade (BI) em Angola, indicando dia, hora e posto de atendimento.




Integrantes do Grupo:
Eng. Celso Zenguel
Eng. Romeu Luís
Eng. Fernanda Sousa


Orientador:
Cilene Magalhães















Introdução
Nos dias atuais, a digitalização de serviços públicos tornou- se uma necessidade para facilitar o acesso dos cidadãos a documentos essenciais. Em Angola, um dos maiores desafios enfrentados pela população é o longo tempo de espera, filas e burocracia no processo de emissão ou renovação do Bilhete de Identidade(BI).
Pensando nisso, este projeto visa criar um website funcional e acessível, com o objetivo de permitir que os cidadãos angolanos possam agendar online o tratamento do seu BI (1ª ou 2ª via), escolhendo  posto, dia e hora disponíveis, de forma rápida, segura e organizada.





















Desenvolvimento
O website proposto será desenvolvido com uma interface amigável e intuitiva, permitindo que qualquer cidadão angolano com acesso à internet consiga utilizá-lo sem dificuldades. As principais funcionalidades incluem:
•	Cadastro do cidadão com dados básicos;
•	Escoha do tipo de serviço (1ª ou 2ª via);
•	Anexão de documentos necessários;
•	Seleção do posto de atendimento mais próximo;
•	Agendamento com data e hora disponíveis;
•	Confirmação via e-mail ou SMS.
OBS: No caso de agendamento para a 1ª via do Bilhete, o indivíduo irá anexar  seu acento de nascimento na categoria de “anexão de documentos necessários”.

A plataforma será otimizada para computadores e dispositivos móveis( smartphone, iphone), e conectada a um banco de dados seguro, com proteção dos dados pessoais dos usuários. Além disso, o sistema permitirá um controle mais eficiente por parte das entidades públicas, organizando melhor o fluxo de atendimento e reduzindo aglomerações.

1.	OBJECTIVO GERAL:
Desenvolver um site funcional que permita aos cidadãos angolanos agendar online o tratamento ou renovação  do seu bilhete de identidade, escolhendo o posto de atendimento, a data e a hora disponíveis.

2.	OBJECTIVO ESPECÍFICOS:

•	Facilitar o acesso aos serviços de identificação civi.
•	Reduzir filas e tempos de espera nos postos.
•	Garantir um processo de agendamento claro, seguro e acessível.
•	Integrar dados dos postos e horários disponíveis em tempo real.
•	Notificar os cidadãos via e-mail ou SMS sobre o agendamento e o estado do processo.



a)	Público Alvo: 
Os cidadãos da República de Angola serãos os principais beneficiados pela criação deste Website.




3.	JUSTIFICATIVA:

O processo atual de emissão e renovação do BI em Angola é muitas vezes demoroso e presencial. Filas longas, deslocações desnecessárias e falta de organização prejudicam a experiência do cidadão. Um site de agendamento digital permitirá maior eficiência, comodidade e transparência, alinhando – se com as metas de digitalização dos serviços públicos.


4.	PROBLEMÁTICA:

•	Tipo_Serviço (1ª via, renovação, 2ª via)
•	Data
•	Hora
•	ID_Posto(FK)
•	Status (confirmado, cancelado)

•	Posto

•	ID_Posto

•	Nome_Posto

•	Localização

•	Capacidade_Diária


Relacionamento:

•	Um usuário pode ter vários agendamentos.
•	Um posto pode ter vários agendamentos.
•	Cada agendamento pertence a um único usuário e a um único posto.








5.	HIPÓTESES:

•	Se for desenvolvido um site com agendamento automático, os cidadãos terão melhor experiência e os serviços serão mais organizados.

•	O uso de tecnologia no processo de BI reduzirá o tempo de espera e aumentará a satisfação do usuário.


6.	REQUISITOS FUNCIONAIS:

•	Cadastro de usuários ( com dados pessoais e contacto).
•	Seleção de tipo de serviço (1ª , 2ª via).
•	Consulta de postos de atendimento disponíveis.
•	Escolha de data e hora com base na disponibiidade.
•	Confirmação e envio de comprovativo de agendamento.
•	Área do admistrador para gerir postos, horários e agendamentos.

7.	REQUISITOS NÃO FUNCIONAIS:

•	Interface amigável e responsiva.
•	Sistema seguro com proteção de dados pessoais.
•	Compatível com dispositivos móveis.














Conclusão:
A criação deste website representa um passo importante na modernização dos serviços públicos em Angola. Através da implementação desta plataforma espera-se melhorar significativamente a experência dos cidadãos angolanos, reduzir o tempo de espera nos postos de identificação e contribuir para um sistema mais eficiente, digital e transparente. Este projeto é uma solução prática e viável para aproximar o cidadão da tecnologia e tornar os serviços públicos mais acessível a todos.



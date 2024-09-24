Introdução
O Documento de Visão do Produto (DVP) é um documento que descreve o produto de software que será desenvolvido. Ele descreve o problema que será resolvido, as principais necessidades dos stakeholders, as principais funcionalidades do sistema, as restrições do projeto, etc.
Propósito
O objetivo deste documento é coletar, analisar e definir características e as necessidades de alto nível do Sistema de Inventário de Equipamentos de Informática (SIEI).


Ele se concentra nos recursos necessários aos stakeholders e aos usuários, e nas razões que levam a essas necessidades.


Os detalhes de como o Sistema de Inventário de Equipamentos de Informática (SIEI) atingem essas necessidades são descritos nas especificações de casos de uso e nos requisitos funcionais.
Definições e abreviações
Abreviações
Termo
Definição
Empreender PB
Secretaria de Empreendedorismo da Paraíba
SGTI
Subgerência de TI
SIEI
Sistema de Inventário de Equipamentos de Informática
OS
Ordem de Serviço
GLPI
Sistema de Gerenciamento de Chamados usado internamente na secretaria



Definições
Termo
Definição
Usuário
É um funcionário/estagiário do Subgerência de TI.
Gestor
Responsável da SGTI.
Equipamento
Qualquer item de informática que possua patrimônio (desktop, notebook, monitor, impressora, switch etc).
Equipamento de consumo
Qualquer item de informática que não possua patrimônio (cabos de rede, conectores RJ45, filtros de linha etc).
Setor
Subgerência de TI.

Escopo do produto
O Sistema de Inventário de Equipamentos de Informática (SIEI) é um sistema que tem como objetivo centralizar e padronizar o controle de materiais e equipamentos dentro da SGTI do Empreender Paraíba.

Posicionamento
Oportunidade de negócios
O Sistema de Inventário de Equipamentos de Informática (SIEI) apresenta várias oportunidades de negócios, tais como:


Consultoria e treinamento: oferecer serviços de consultoria e treinamento para ajudar os clientes a maximizar o uso do SIEI. A equipe responsável pelo SIEI pode prestar suporte na configuração inicial, personalização do sistema para atender às necessidades específicas de cada órgão e oferecer treinamento contínuo aos usuários para garantir uma utilização eficiente do sistema.
Disponibilizar um desenvolvedor para atuar internamente: um desenvolvedor do SIEI ficaria responsável por atuar presencialmente, juntamente com os funcionários da SGTI, para repassar qualquer demanda para a equipe de desenvolvimento.
Parcerias estratégicas: o SIEI pode formar parcerias com fornecedores de equipamentos e materiais, permitindo que as secretarias façam aquisições diretamente através do sistema. Essas parcerias podem incluir descontos ou condições especiais para compras realizadas por meio do SIEI, tornando-o um canal preferencial para aquisição de bens e equipamentos.
Integração com a GLPI: o SIEI pode ser integrado com o Sistema de Gerenciamento de Chamados (GLPI). Isso permitirá uma gestão mais integrada e eficiente, facilitando o fluxo de informações entre diferentes aplicações.
Expansão para o setor privado: embora inicialmente desenvolvido para uso governamental, o SIEI pode ser adaptado e comercializado para empresas privadas que também necessitem de um sistema eficiente de gestão de inventário de equipamentos de informática.
Serviços de manutenção no sistema: a equipe do SIEI pode oferecer um serviço adicional de monitoramento e manutenção do sistema.
Possibilidade de expansão para outros setores interessados: a equipe do SIEI pode implementar e configurar a aplicação para outros setores que tenham interesse em fazer uso do software e seus respectivos equipamentos.
Descrição dos benefícios para os clientes e dos problemas resolvidos
Benefícios
Problemas Resolvidos
Afetados
Centralização do controle
Descentralização do registro em múltiplas ferramentas
Todos os setores
Praticidade nas consultas de equipamentos
Dificuldade para localizar um determinado equipamento de Informática dentro da secretaria
Subgerência de TI
Consistência dos dados
Inconsistência nos registros devido ao uso de diversas planilhas e à falta de padronização
Todos os setores
Melhoria no planejamento
Dificuldade em prever a necessidade de novos materiais
Gestores da SGTI
Otimização do tempo gasto para inventariar os equipamentos e materiais de consumo
Tempo e esforço para gerenciar o inventário
Equipe de SGTI, Gestores
Alertas personalizados
Evitar que um setor seja afetado pela escassez de um determinado equipamento
Todos os setores.
Possibilidade de integração com a GLPI
Manuseio de diversas aplicações de gerenciamento
Sugerência de TI

Descrição dos stakeholders e dos usuários
Esta seção descreve os stakeholders e os usuários do Sistema de Inventário de Equipamentos de Informática (SIEI).
Stakeholders
Segue abaixo a lista de stakeholders:
Stakeholder
Descrição
Papel
Gestor da SGTI
Responsável por gerenciar o SIEI dentro do Empreender Paraíba
Gestor
Equipe de TI
Funcionários que irão manusear o SIEI.
Suporte técnico

Usuários e atores
Segue tabela com os usuários e atores do sistema:
Usuário
Descrição
Responsabilidades
Stakeholders
Clientes
Equipe da SGTI que irá manusear o SIEI internamente.
Registrar, consultar, atualizar e remover equipamentos e materiais de consumo.
Secretaria, Equipe de TI
Desenvolvedor do sistema
Profissional responsável por implementar e manter o sistema.
Suporte técnico, configuração do sistema.
Equipe de desenvolvimento
Administrador do sistema
Profissional responsável por gerenciar e manter o sistema.
Gerenciar os usuários do sistema, realizar backup dos dados, atualizar o sistema e garantir o seu funcionamento adequado.
Equipe de Desenvolvimento, Gerente de Projeto




Descrição do ambiente de uso
Ambiente de uso
A seguir, são descritos alguns ambientes em que o sistema pode ser utilizado:
Ambiente do Cliente: Neste ambiente, o sistema é utilizado pelos clientes para controlar os equipamentos adquiridos. Os clientes podem acessar o sistema através de um navegador web em seus dispositivos mobile ou desktop. O navegador web poderá ser o Google Chrome, Mozilla Firefox ou Microsoft Edge com acesso através do endereço web https://www.empreender.pb.gov.com.br/siei. O ambiente do cliente é acessado através da internet e requer um login e senha de acesso. A segurança dos dados será garantida por meio de autenticação e autorização, assegurando que somente usuários com as devidas permissões possam visualizar e manipular as informações do inventário.
Ambiente de Teste: Neste ambiente, o sistema é utilizado para testar novas funcionalidades e correções de bugs antes de serem disponibilizadas para os usuários finais. O ambiente de teste é acessado através de um navegador web em um computador, e requer um login e senha de acesso específicos para o ambiente de teste.
Necessidades principais quanto ao ambiente


A seguir, é apresentada uma tabela que descreve as necessidades dos clientes com relação à qualidade, desempenho, segurança, usabilidade e confidencialidade do sistema SIEI, juntamente com sua prioridade, interesse, solução atual e soluções propostas:


Necessidade
Prioridade
Interesse
Solução Atual
Soluções Propostas
Qualidade: O sistema deve ser confiável e livre de erros, bugs e falhas.
Alta
Os usuários esperam que o sistema funcione corretamente e não apresente problemas que comprometam a gestão de equipamentos e materiais.	
Testes manuais realizados pela equipe de desenvolvimento.
Implementar testes automatizados e processos de garantia de qualidade para identificar e corrigir erros e bugs.
Desempenho: O sistema deve ter um bom desempenho, com tempo de resposta rápido e sem atrasos significativos.
Alta
Os usuários esperam que o sistema responda rapidamente às solicitações e consultas.	
Servidor dedicado para hospedagem do sistema e monitoramento constante do desempenho.
Melhorar a arquitetura do sistema para garantir melhor desempenho e escalabilidade, bem como otimizar consultas de banco de dados e uso de recursos do sistema.
Escalabilidade:  O sistema deve suportar o crescimento no número de registros e acessos.
Alta
 O sistema deve suportar o crescimento no número de registros e acessos.Os usuários esperam que o sistema continue funcionando de forma eficiente mesmo com o aumento de usuários e equipamentos cadastrados.	
Arquitetura escalável, com distribuição de carga e uso de servidores em nuvem.
Implementar arquitetura em nuvem e balanceamento de carga para garantir a escalabilidade contínua.
Segurança: O sistema deve ser seguro, protegido contra acesso não autorizado, invasões e roubo de dados.
Alta
Os usuários esperam que os dados estejam seguros e protegidos contra acesso indevido.
Autenticação de usuários com login e senha, criptografia de dados sensíveis e acesso restrito somente a usuários autorizados.
Implementar medidas adicionais de segurança, como autenticação de dois fatores, certificados SSL e criptografia avançada.
Usabilidade: O sistema deve ser fácil de usar e entender, com uma interface intuitiva e amigável ao usuário.
Moderada
Os clientes esperam que o sistema seja fácil de usar e entender, sem a necessidade de treinamento especializado.
Interface de usuário simples e intuitiva.
Realizar testes de usabilidade com usuários reais e implementar melhorias baseadas no feedback para aprimorar a interface.


Tempo de resposta: O sistema deve ter um tempo de resposta rápido para que os clientes possam acessar e controlar suas garantias de forma eficiente.
Moderada
Os usuários esperam acessar informações e realizar ações sem atrasos para uma gestão ágil do inventário.
Monitoramento constante do tempo de resposta do sistema.
Implementar caching e otimizações de performance para garantir respostas rápidas mesmo com alta carga de dados.


Confidencialidade: O sistema deve proteger a privacidade e confidencialidade das informações dos clientes.
Alta
Os usuários esperam que suas informações sejam mantidas em sigilo e seguras contra acesso indevido.
Controles de acesso restrito, criptografia de dados sensíveis e monitoramento constante das atividades do usuário.
Realizar auditorias de segurança regulares e implementar medidas adicionais de proteção de dados, como políticas claras de privacidade e protocolos avançados de segurança.


Visão geral do produto
Visão geral
1. Objetivo Geral
O Sistema de Inventário de Equipamentos de Informática (SIEI) tem como objetivo centralizar e padronizar o controle de equipamentos e materiais de informática dentro da SGTI, garantindo uma gestão eficiente e integrada dos recursos disponíveis.
2. Propósito
O propósito do SIEI é fornecer uma solução robusta para a gestão do inventário de equipamentos, permitindo a centralização dos registros, a melhoria na localização e consulta de equipamentos, e a integração com outros sistemas de gestão. O sistema visa resolver problemas de descentralização e inconsistência dos dados, promovendo eficiência e segurança no gerenciamento de materiais e equipamentos.
3. Estrutura Operacional
O SIEI é baseado em uma infraestrutura de TI moderna e flexível, composta pelos seguintes elementos:
Infraestrutura de TI:
Servidores: Hospedagem do sistema e gerenciamento de dados. Os servidores garantem o processamento e a disponibilidade contínua do sistema.
Banco de Dados: Armazenamento de informações relacionadas aos equipamentos, materiais e usuários. O banco de dados é fundamental para manter a integridade e a consistência dos registros.
Dispositivos de Rede: Roteadores e switches são utilizados para garantir a comunicação eficiente e segura entre os servidores e os dispositivos dos usuários.
Acesso ao Sistema:
Dispositivos Compatíveis: O SIEI pode ser acessado através de qualquer dispositivo com um navegador web e acesso à Internet, como computadores, laptops, tablets.Isso proporciona flexibilidade e acessibilidade para os usuários. 
Conexão de Rede: A interação entre os dispositivos e o sistema ocorre por meio de uma conexão de rede, geralmente a Internet. O servidor do SIEI se comunica com os dispositivos dos usuários através de solicitações HTTP e respostas, permitindo a exibição de informações e a interação com o sistema.
Integração com Outros Sistemas:
APIs (Application Programming Interface): O SIEI pode ser integrado com outros sistemas, como sistemas de gerenciamento de estoque ou plataformas de gestão pública, por meio de APIs. Essa integração permite a troca automatizada de informações e melhora a eficiência dos processos administrativos.
4. Funcionalidades
Centralização e Padronização: Gestão unificada e padronizada dos equipamentos e materiais.
Consulta Eficiente: Facilidade para localizar e consultar equipamentos dentro da secretaria.
Alertas Personalizados: Notificações para evitar escassez de equipamentos essenciais.
Acesso Remoto: Possibilidade de acesso ao sistema de qualquer lugar com conexão segura.
Integração: Capacidade de se conectar com outros sistemas de gestão para troca automatizada de dados.
5. Benefícios
Centralização: Consolidamento de registros em uma única plataforma.
Eficiência: Redução de tempo e esforço na gestão do inventário.
Segurança: Proteção dos dados e controle de acesso através de autenticação e autorização.
Flexibilidade: Acesso remoto e integração com outras ferramentas e sistemas.
Custo e venda
Os custos e a venda do software serão definidos em conformidade com as condições estabelecidas no edital, garantindo que o valor seja justo e compatível com o orçamento previsto. Os cálculos dos custos incluirão não apenas o desenvolvimento e a implementação da solução, mas também os gastos com manutenção, suporte técnico, e eventuais atualizações. A venda do software, assim como os termos de pagamento, serão regidos pelas cláusulas do edital, assegurando transparência no processo de contratação e cumprimento das obrigações financeiras por ambas as partes. Eventuais ajustes de preço ou condições adicionais também seguirão as diretrizes contratuais estabelecidas.
Licenciamento e instalação
O licenciamento e a instalação do software serão realizados em conformidade com as normas estabelecidas no edital, respeitando as diretrizes de propriedade intelectual e distribuição previstas. A solução será implementada de acordo com as especificações técnicas fornecidas, garantindo a adequação aos padrões de uso definidos pela administração municipal. O processo de instalação abrangerá a configuração adequada dos ambientes operacionais e a entrega das chaves de licenciamento, conforme requerido. Qualquer ajuste ou configuração adicional será executado em conformidade com os procedimentos descritos no edital, assegurando a conformidade com as políticas de segurança e manutenção contínua.
Características e funcionalidades de alto nível
Esta seção define e descreve as características do SIEI. Trata-se dos requisitos de alto nível do sistema que são necessários para propiciar benefícios aos usuários.
O sistema deve permitir o cadastro de  produtos, incluindo informações sobre garantia, condições para utilização.
O sistema deve enviar notificações aos clientes quando o prazo de garantia estiver próximo do vencimento, para que possam tomar as medidas necessárias.
O sistema deve permitir o acompanhamento do status das garantias, incluindo as solicitações de reparo ou substituição de produtos em garantia.
O sistema deve garantir a segurança das informações dos clientes e produtos, com acesso restrito e controle de permissões de usuários.
O sistema deve ter uma interface de usuário amigável e de fácil utilização, para que os clientes possam utilizar as funcionalidades sem dificuldade.
O sistema deve ter um desempenho satisfatório, com tempos de resposta rápidos e sem interrupções ou falhas.
O sistema deve ter escalabilidade, para que possa ser adaptado às necessidades de novos clientes e produtos, sem prejudicar o desempenho e a qualidade.
O sistema deve ser desenvolvido em conformidade com as normas e padrões de qualidade estabelecidos para o desenvolvimento de software.
O sistema deve ser documentado e ter seu código-fonte disponível para auditoria e manutenção futura.
Restrições
Algumas possíveis restrições que podem ser aplicadas ao sistema são:
Restrição de orçamento: O projeto deve ser concluído dentro de um determinado orçamento e não pode excedê-lo.
Restrição de tempo: O sistema deve ser desenvolvido e implementado dentro de um prazo específico e não pode ser estendido, conforme negociado com o cliente, em até um ano, possuindo entregas quinzenais de um produto mínimo viável (MVP).
Restrições de hardware: O sistema deve ser capaz de funcionar em uma determinada configuração de hardware atual e não pode ser executado em sistemas mais antigos.
Restrições de segurança e privacidade: O sistema deve atender aos requisitos de segurança, privacidade e proteção de dados do usuário, conforme a Lei Geral de Proteção de Dados (LGPD).
Restrições de usabilidade: O sistema deve ser fácil de usar e acessível para usuários com deficiências visuais e motoras.
Restrições de interoperabilidade: O sistema deve ser capaz de interoperar com outros sistemas e aplicativos.
Restrições de desempenho: O sistema deve atender aos requisitos de desempenho, como velocidade, escalabilidade e disponibilidade.
Restrições geográficas: O sistema deve ser compatível com os requisitos geográficos, como fusos horários e os idiomas inglês, espanhol e português.




Data: 21 de agosto de 2024


Validado por:


Caio Bernardelli, Felipe Cartaxo, Gabriel Oliveira, Michel Lavanere, Sheila Lee | Equipe de desenvolvimento
siei@empreenderpb.com.br
sieisoft.com
Box 564, João Pessoa
BRA
Criado em agosto de 2024 pela equipe de desenvolvedores






# Introdução

O Documento de Visão do Produto (DVP) é um documento que descreve o produto de software que será desenvolvido. Ele descreve o problema que será resolvido, as principais necessidades dos stakeholders, as principais funcionalidades do sistema, as restrições do projeto, etc.

## Propósito

O objetivo deste documento é coletar, analisar e definir características e as necessidades de alto nível do Sistema de Inventário de Equipamentos de Informática (SIEI).

Ele se concentra nos recursos necessários aos stakeholders e aos usuários, e nas razões que levam a essas necessidades.

Os detalhes de como o Sistema de Inventário de Equipamentos de Informática (SIEI) atinge essas necessidades são descritos nas especificações de casos de uso e nos requisitos funcionais.

## Definições e Abreviações

### Abreviações

| Termo         | Definição                                            |
|---------------|------------------------------------------------------|
| **Empreender PB** | Secretaria de Empreendedorismo da Paraíba         |
| **SGTI**      | Subgerência de TI                                     |
| **SIEI**      | Sistema de Inventário de Equipamentos de Informática  |
| **OS**        | Ordem de Serviço                                      |
| **GLPI**      | Sistema de Gerenciamento de Chamados usado internamente na secretaria |

### Definições

| Termo                   | Definição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Usuário**             | É um funcionário/estagiário do Subgerência de TI.                         |
| **Gestor**              | Responsável da SGTI.                                                     |
| **Equipamento**         | Qualquer item de informática que possua patrimônio (desktop, notebook, monitor, impressora, switch etc). |
| **Equipamento de consumo** | Qualquer item de informática que não possua patrimônio (cabos de rede, conectores RJ45, filtros de linha etc). |
| **Setor**               | Subgerência de TI.                                                        |

## Escopo do Produto

O Sistema de Inventário de Equipamentos de Informática (SIEI) é um sistema que tem como objetivo centralizar e padronizar o controle de materiais e equipamentos dentro da SGTI do Empreender Paraíba.

## Posicionamento

### Oportunidade de Negócios

O Sistema de Inventário de Equipamentos de Informática (SIEI) apresenta várias oportunidades de negócios, tais como:

- **Consultoria e treinamento**: oferecer serviços de consultoria e treinamento para ajudar os clientes a maximizar o uso do SIEI. A equipe responsável pelo SIEI pode prestar suporte na configuração inicial, personalização do sistema para atender às necessidades específicas de cada órgão e oferecer treinamento contínuo aos usuários para garantir uma utilização eficiente do sistema.
- **Disponibilizar um desenvolvedor para atuar internamente**: um desenvolvedor do SIEI ficaria responsável por atuar presencialmente, juntamente com os funcionários da SGTI, para repassar qualquer demanda para a equipe de desenvolvimento.
- **Parcerias estratégicas**: o SIEI pode formar parcerias com fornecedores de equipamentos e materiais, permitindo que as secretarias façam aquisições diretamente através do sistema. Essas parcerias podem incluir descontos ou condições especiais para compras realizadas por meio do SIEI, tornando-o um canal preferencial para aquisição de bens e equipamentos.
- **Integração com o GLPI**: o SIEI pode ser integrado com o Sistema de Gerenciamento de Chamados (GLPI). Isso permitirá uma gestão mais integrada e eficiente, facilitando o fluxo de informações entre diferentes aplicações.
- **Expansão para o setor privado**: embora inicialmente desenvolvido para uso governamental, o SIEI pode ser adaptado e comercializado para empresas privadas que também necessitem de um sistema eficiente de gestão de inventário de equipamentos de informática.
- **Serviços de manutenção no sistema**: a equipe do SIEI pode oferecer um serviço adicional de monitoramento e manutenção do sistema.
- **Possibilidade de expansão para outros setores interessados**: a equipe do SIEI pode implementar e configurar a aplicação para outros setores que tenham interesse em fazer uso do software e seus respectivos equipamentos.

### Descrição dos Benefícios para os Clientes e dos Problemas Resolvidos

| Benefícios                              | Problemas Resolvidos                                             | Afetados                    |
|-----------------------------------------|------------------------------------------------------------------|-----------------------------|
| **Centralização do controle**           | Descentralização do registro em múltiplas ferramentas            | Todos os setores            |
| **Praticidade nas consultas de equipamentos** | Dificuldade para localizar um determinado equipamento de Informática dentro da secretaria | Subgerência de TI           |
| **Consistência dos dados**              | Inconsistência nos registros devido ao uso de diversas planilhas e à falta de padronização | Todos os setores            |
| **Melhoria no planejamento**            | Dificuldade em prever a necessidade de novos materiais            | Gestores da SGTI            |
| **Otimização do tempo gasto para inventariar os equipamentos e materiais de consumo** | Tempo e esforço para gerenciar o inventário                      | Equipe de SGTI, Gestores    |
| **Alertas personalizados**              | Evitar que um setor seja afetado pela escassez de um determinado equipamento | Todos os setores            |
| **Possibilidade de integração com a GLPI** | Manuseio de diversas aplicações de gerenciamento                  | Sugerência de TI            |

## Descrição dos Stakeholders e dos Usuários

Esta seção descreve os stakeholders e os usuários do Sistema de Inventário de Equipamentos de Informática (SIEI).

### Stakeholders

Segue abaixo a lista de stakeholders:

| Stakeholder         | Descrição                                                 | Papel               |
|---------------------|-----------------------------------------------------------|---------------------|
| **Gestor da SGTI**  | Responsável por gerenciar o SIEI dentro do Empreender Paraíba | Gestor              |
| **Equipe de TI**    | Funcionários que irão manusear o SIEI.                    | Suporte técnico     |

### Usuários e Atores

Segue tabela com os usuários e atores do sistema:

| Usuário                | Descrição                                              | Responsabilidades                                       | Stakeholders               |
|------------------------|--------------------------------------------------------|---------------------------------------------------------|----------------------------|
| **Clientes**           | Equipe da SGTI que irá manusear o SIEI internamente.   | Registrar, consultar, atualizar e remover equipamentos e materiais de consumo. | Secretaria, Equipe de TI   |
| **Desenvolvedor do sistema** | Profissional responsável por implementar e manter o sistema. | Suporte técnico, configuração do sistema.                | Equipe de desenvolvimento  |
| **Administrador do sistema** | Profissional responsável por gerenciar e manter o sistema. | Gerenciar os usuários do sistema, realizar backup dos dados, atualizar o sistema e garantir o seu funcionamento adequado. | Equipe de Desenvolvimento, Gerente de Projeto |

## Descrição do Ambiente de Uso

### Ambiente de Uso

A seguir, são descritos alguns ambientes em que o sistema pode ser utilizado:

- **Ambiente do Cliente**: Neste ambiente, o sistema é utilizado pelos clientes para controlar os equipamentos adquiridos. Os clientes podem acessar o sistema através de um navegador web em seus dispositivos mobile ou desktop. O navegador web poderá ser o Google Chrome, Mozilla Firefox ou Microsoft Edge com acesso através do endereço web [https://www.empreender.pb.gov.com.br/siei](https://www.empreender.pb.gov.com.br/siei). O ambiente do cliente é acessado através da internet e requer um login e senha de acesso. A segurança dos dados será garantida por meio de autenticação e autorização, assegurando que somente usuários com as devidas permissões possam visualizar e manipular as informações do inventário.
- **Ambiente de Teste**: Neste ambiente, o sistema é utilizado para testar novas funcionalidades e correções de bugs antes de serem disponibilizadas para os usuários finais. O ambiente de teste é acessado através de um navegador web em um computador, e requer um login e senha de acesso específicos para o ambiente de teste.

### Necessidades Principais Quanto ao Ambiente

A seguir, é apresentada uma tabela que descreve as necessidades dos clientes com relação à qualidade, desempenho, segurança, usabilidade e confidencialidade do sistema SIEI, juntamente com sua prioridade, interesse, solução atual e soluções propostas:

| Necessidade                              | Prioridade | Interesse | Solução Atual                                    | Soluções Propostas |
|------------------------------------------|------------|-----------|-------------------------------------------------|--------------------|
| **Qualidade**: O sistema deve ser confiável e livre de erros, bugs e falhas. | Alta       | Os usuários esperam que o sistema funcione corretamente e não apresente problemas que comprometam a gestão de equipamentos e materiais. | Testes manuais realizados pela equipe de desenvolvimento. | Implementar testes automatizados e processos de garantia de qualidade para identificar e corrigir erros e bugs. |
| **Desempenho**: O sistema deve ter um bom desempenho, com tempo de resposta rápido e sem atrasos significativos. | Alta       | Os usuários esperam que o sistema responda rapidamente às solicitações e consultas. | Servidor dedicado para hospedagem do sistema e monitoramento constante do desempenho. | Melhorar a arquitetura do sistema para garantir melhor desempenho e escalabilidade, bem como otimizar consultas de banco de dados e uso de recursos do sistema. |
| **Escalabilidade**:  O sistema deve suportar o crescimento no número de registros e acessos. | Alta       | Os usuários esperam que o sistema continue funcionando de forma eficiente mesmo com o aumento de usuários e equipamentos cadastrados. | Arquitetura escalável, com distribuição de carga e uso de servidores em nuvem. | Implementar arquitetura em nuvem e balanceamento de carga

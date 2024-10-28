# Desafio de Projeto - Resumo do Lab Introdução à Cloud Computing com Azure, Vantagens da Computação em Nuvem:

## Alta Disponibilidade:

A alta disponibilidade refere-se à capacidade dos serviços de computação em nuvem se manterem ativos o máximo de tempo possível. Tal vantagem é abarcada ainda pelo SLA - Service Level Agreement - ou Acordo de Nível de Serviço, em tradução livre, que trata do comprometimento do provedor do serviço com períodos de disponibilidade/indisponibilidade (uptime/downtime), tendo tabelados preços de acordo com as particularidades de cada plano de provisionamento. Um detalhe, o SLA também prevê uma forma de crédito, caso haja indisponibilidade por tempo maior que o previsto no contrato. Tudo isso para garantir disponibilidade máxima, com o mínimo de interrupções, independente de quaisquer eventos.

## Escalabilidade:

No que diz respeito à escalabilidade, é a possibilidade de ajuste dos recursos de acordo com a demanda da empresa ou organização. É possível haver tanto disponibilização de mais recursos quando da alta demanda, quanto a redução de dito recurso em caso de baixa demanda. De maneira vertical, sendo necessário, é possível reduzir capacidades de processamento e quantidade de memória RAM disponibilizadas.

## Elasticidade:

A elasticidade é a vantagem que se encarrega dos saltos de demanda, cuidando da expansão de recursos manual ou automaticamente, para se alinhar a altas demandas. Havendo queda significativa, os recursos são reduzidos de maneira horizontal, podendo o cliente definir se isso deve ser feito de forma automática ou manualmente.

## Confiabilidade:

A confiabilidade advém da descentralização dos recursos na nuvem, dando resiliência e confiança na infraestrutura. Isso porque a implantação dos serviços não se limita a barreiras geográficas, crucial em uma eventual recuperação de desastre (disaster recovery).

## Previsibilidade:

A previsibilidade é a capacidade de antecipar desempenho e custos, que no caso do Azure, baseia-se no Azure Well-Architected Framweork, definidos pela própria Microsoft como "uma série de princípios direcionados à qualidade, pontos de decisão arquitetural e ferramentas de revisão, voltadas a auxiliar arquitetos de solução na construção de uma base sólida para suas cargas de trabalho". Tal framework se baseia em 5 pilares: Otimização de Custos, Segurança, Confiabilidade, Excelência Operacional e Eficiência de Performance.

## Segurança:

A segurança do cloud computing é todo o suporte de ferramentas disponíveis para garantir a integridade dos serviços. Neste tópico vale mencionar a responsabilidade compartilhada, pois mesmo que o provedor de serviço disponibilize às empresas e organizações tais ferramentas, ainda é necessário que o cliente implante-as.

## Governança:

A governança está relacionada diretamente com a gestão, por permitir a definição de diretrizes e padrões para auditoria de conformidade do serviço com o negócio.

## Gerenciabilidade:

Por último, a gerenciabilidade trata da capacidade de multi-gerenciamento da computação em nuvem, sendo possível gerenciá-la de pontos distintos, através do portal web, do CLI (interface de linha de comando), APIs ou mesmo através do PowerShell.


### Referência:
https://learn.microsoft.com/en-us/azure/well-architected/

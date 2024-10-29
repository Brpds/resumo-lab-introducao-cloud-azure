# Desafio de Projeto Bootcamp DIO e XP Inc, Fullstack Developer, Configuração de uma Instância de Banco de Dados com Azure - Resumo 3

## Tipos de Serviço de Nuvem

Há 3 categorias principais de serviços providos na nuvem. São elas: IaaS, PaaS e SaaS, correspondendo a Infrastructure as a Service, Plataform as a Service e Software as a Service, ou em tradução livre, Infraestrutura como Serviço, Plataforma como Serviço e Software como Serviço, respectivamente. Tais serviços normalmente se alinham com o nível de gerenciamento desejado pelo cliente, sendo IaaS o que possui maior nível gerencial, PaaS com gerência média e SaaS com o menor nível de capacidade de gerenciamento. Vale ainda mencionar que, em termos de abrangência, SaaS está inserido no contexto de PaaS, enquanto PaaS está inserido no contexto de IaaS, como se formasse uma hierarquia IaaS > PaaS > SaaS.

## Responsabilidade Compartilhada - quem faz o quê?

No que tange a responsabilidade pelo serviço provido, os tipos de serviço em nuvem diferem sobre o que cliente e provedor são responsáveis. <br>
1 - Nuvem privada: o cliente é responsável por todos os níveis do serviço, desde instalações físicas até dados providos. <br>
2 - IaaS: recursos físicos são de responsabilidade do provedor, enquanto da configuração até os dados ficam a cargo do cliente. Aqui, a maior parte dos recursos ficam ainda a cargo do cliente.<br>
3 - PaaS: aparecem os primeiros pontos de responsabilidade compartilhada, onde cliente e provedor são responsáveis por aplicativos, infraestrutura de identidade e diretórios, controle de rede, de acordo com o tipo do serviço. Neste ponto, os recursos pelos quais cliente e provedor são responsáveis  já possuem uma divisão mais equilibrada. <br>
4 - SaaS: neste tipo de serviço a responsabilidade compartilhada é reduzida a basicamente um único recurso, o de infraestrutura de identidade e diretórios, com o provedor assumindo a maior parte da responsabilidade para provimento do serviço.

## Aplicações dos Serviços:

No tocante ao tema de aplicabilidade dos serviços, o IaaS oferece uma nuvem flexível, permitindo maior nível de gerenciamento de configuração para os aplicativos. PaaS é mais focado no desenvolvimento de aplicações e bancos de dados, com a plataforma sendo o provedor e com menor nível de gerenciamento. Finalmente, o SaaS é o software propriamente dito, que normalmente é o único recurso consumido pelo cliente, pago através de um modelo de assinatura. Em todos os níveis, é perceptível a capacidade de pagamento conforme o uso dos recursos, característica marcante dos serviços de nuvem.

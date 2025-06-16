DIO-Tipos-Servico-Nuvem
Projeto sobre Tipos de Serviço de Nuvem e Modelo de Responsabilidade Compartilhada no Azure.
Durante as aulas e a análise para este desafio, os seguintes conceitos fundamentais foram estudados:
Tipos de Serviço de Nuvem
IaaS (Infraestrutura como Serviço):** Permite criar uma infraestrutura de TI de pagamento conforme o uso, alugando servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais de um provedor de nuvem. É o serviço de nuvem mais flexível, onde o cliente configura e gerencia o hardware para seu aplicativo.
Casos de Uso Apropriados: Ideal para empresas que precisam de controle total sobre seus sistemas operacionais e aplicações, como migração de workloads locais ou desenvolvimento de soluções personalizadas que exigem acesso ao nível de infraestrutura.
PaaS (Plataforma como Serviço): Fornece um ambiente para a criação, o teste e a implantação de aplicativos de software, sem focar no gerenciamento da infraestrutura subjacente. O gerenciamento da plataforma é realizado pelo provedor de nuvem. É focado no desenvolvimento de aplicativos.
Casos de Uso Apropriados: Perfeito para desenvolvedores que desejam se concentrar na escrita e implantação de código, sem se preocupar com servidores, sistemas operacionais ou bancos de dados subjacentes. Exemplos incluem hospedagem de aplicações web e APIs.
SaaS (Software como Serviço): Os usuários se conectam e usam aplicativos com base em nuvem pela Internet. Os usuários pagam pelo software que utilizam em um modelo de assinatura.
asos de Uso Apropriados: Adequado para usuários finais que precisam de funcionalidades de software sem a complexidade de instalação, manutenção ou gerenciamento de infraestrutura.

Modelo de Responsabilidade Compartilhada
O modelo de responsabilidade compartilhada ilustra a divisão de responsabilidades entre o provedor de nuvem (Microsoft, no caso do Azure) e o cliente. A responsabilidade pela segurança de um ambiente de nuvem não é totalmente do provedor, mas sim uma responsabilidade conjunta.

Responsabilidade Sempre Retida pelo Cliente:
Informações e dados 
Dispositivos (móveis e PCs) 
Contas e identidades 
Responsabilidade Varia Conforme o Tipo (SaaS, PaaS, IaaS):
SaaS: A Microsoft (provedor) tem a maior parte da responsabilidade, enquanto o cliente retém a responsabilidade pelas informações e dados, dispositivos, contas e identidades.
A responsabilidade é mais equilibrada. O provedor gerencia a plataforma subjacente, e o cliente é responsável pelos aplicativos e, em parte, pela infraestrutura de identidade e diretório e controles de rede.
 IaaS: O cliente tem a maior parte da responsabilidade pela infraestrutura, gerenciando o sistema operacional, aplicativos e dados, enquanto o provedor gerencia apenas os hosts físicos, a rede física e o datacenter físico.
Transferências de Responsabilidade para Provedores de Nuvem:**
Hosts físicos 
Rede física 
Datacenter físico 
No ambiente on-premises, o cliente é responsável por todas as camadas, desde o datacenter físico até as informações e dados.

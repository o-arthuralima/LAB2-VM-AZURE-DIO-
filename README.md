CRIAÇÃO DE MÁQUINA VIRTUAL (VM) NO MICROSOFT AZURE
########################################################################
Deve-se levar em consideração a quantidade de regiões onde a VM será disponibilizada, de modo que quanto mais regiões, mais datacenters disponíveis e, sendo assim, menor a latência para o cliente, oferecendo escalabilidade e flexibilidade para o cliente.
Além disso, preservam a residência dos dados com uma oferta abrangente de conformidade.
A plataforma AZURE conta com mais de 60 regiões, representando mais de 140 países.

ZONAS DE DISPONIBILIDADE
Fornecem proteção contra tempo de inatividade devido à falha do datacenter
Separa fisicamente os datacenters dentro de uma mesma região
São conectadas por meio de redes privadas de fibra óptica, onde cada datacenter é equipado com resfriamento, alimentação e rede de computadores.
Ao criar uma VM, deve-se levar em consideração os limites de controle de acesso do usuário, além de definir a REDUNDÂNCIA, sendo:
    LRS - ARMAZ. COM REDUND. LOCAL
    ZRS - ARMAZ. COM REDUND. DE ZONA
    GRS - ARMAZ. COM REDUND. GEORÁFICA
    GZRS - ARMAZ. COM REDUND. POR ZONA GEOGRÁFICA
Significa dizer que quanto maior a redundância (maior o número de 9) menor será o tempo de inatividade do recurso criado, por conta do SLA (SERVICE LEVEL AGREEMENT)
ex: SLA 99% - inatividade de 1,68h/semana
    SLA 99,99% - inatividade de 1,01min/semana
Entendendo que quanto maior o número de Zonas de Disponibilidade, a tend é maior o SLA, portando maior será o custo para o cliente.

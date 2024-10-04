# Resumo | Laboratório 02

## Acordo de Nível de Serviço (SLA)

O Acordo de Nível de Serviço (SLA) é um compromisso entre um provedor de serviços e o cliente que define o nível esperado de serviço. No contexto do Azure, os SLAs garantem um tempo de atividade mínimo para os serviços. Por exemplo, o SLA para máquinas virtuais pode garantir uma disponibilidade de 99,9% quando implantadas em uma única instância e até 99,99% quando distribuídas em duas ou mais Zonas de Disponibilidade.

## Zonas de Disponibilidade

As Zonas de Disponibilidade são locais físicos distintos dentro de uma região do Azure. Cada zona é composta por um ou mais datacenters equipados com energia, refrigeração e rede independentes. As Zonas de Disponibilidade oferecem alta disponibilidade ao proteger suas aplicações e dados contra falhas de datacenter. Ao implantar máquinas virtuais em várias zonas, você pode alcançar uma maior resiliência e disponibilidade.

## Redundância das Contas de Armazenamento

As contas de armazenamento do Azure oferecem várias opções de redundância para garantir a durabilidade e a disponibilidade dos dados:

- LRS (Locally Redundant Storage): Replica os dados três vezes dentro de um único datacenter.
- ZRS (Zone-Redundant Storage): Replica os dados em três zonas de disponibilidade dentro de uma região.
- GRS (Geo-Redundant Storage): Replica os dados para uma região secundária distante, garantindo durabilidade mesmo em caso de falha regional.
- RA-GRS (Read-Access Geo-Redundant Storage): Oferece os mesmos benefícios do GRS, mas permite acesso de leitura aos dados na região secundária.
- GZRS (Geo-Zone-Redundant Storage): Combina a replicação entre zonas de disponibilidade e a replicação geográfica, garantindo alta durabilidade e disponibilidade dos dados em caso de falhas regionais e de datacenter.

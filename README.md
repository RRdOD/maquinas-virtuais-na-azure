# Azure Virtual Machines - Resumos, Anotações e Dicas

- Este repositório serve como material de apoio para estudos e implementações de Máquinas Virtuais (VMs) no Microsoft Azure.

## Conceitos Básicos
- O que é uma VM na Azure?
Servidor virtualizado na nuvem Azure;
Equivalente a um computador físico, mas com recursos escaláveis;
Oferece flexibilidade de virtualização sem necessidade de comprar/manter hardware físico;

- Principais Componentes:
Imagem: Template do SO e configurações;

Tamanho (SKU): Define CPU, memória, GPU e outras capacidades;

Disco: Armazenamento persistente (SSD/HDD);

Rede: Interface de rede, endereço IP, NSG;

## Dicas Importantes
- Otimização de Custos
Spot VMs: Até 90% de desconto para cargas interruptíveis;

VMs Reservadas: Desconto por compromisso de 1 ou 3 anos;

Dimensionamento correto: Monitorar métricas antes de escalar;

Desligar VMs não utilizadas (especialmente em dev/teste);

- Segurança
Sempre usar NSGs e limitar acesso às portas necessárias;

Ativar Azure Disk Encryption para dados sensíveis;

Usar Azure Bastion para acesso seguro sem IPs públicos;

- Alta Disponibilidade
Conjuntos de disponibilidade para proteção contra falhas de hardware;

Zones de disponibilidade para proteção contra falhas no datacenter;

Conjuntos de escala de máquina virtual para escalabilidade automática;

## Monitoramento e Gerenciamento
Azure Monitor: Coleta métricas e logs;

Alertas: Configurar para uso de CPU, memória, etc.;

Backup Azure: Para proteção de dados importantes;

Azure Policy: Para aplicar padrões organizacionais;

## Recursos Adicionais
Documentação Oficial Azure VMs;

Calculadora de Custos Azure;

Azure Architecture Center - Referências de VM;

# domindando-o-armazenamento-na-azure
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

# Desafio: Dominando o Armazenamento na Azure

## Objetivo
Este projeto tem como objetivo aplicar os conceitos aprendidos sobre **serviços de armazenamento no Microsoft Azure**, documentando o processo e os aprendizados.

## O que aprendi
Durante o desenvolvimento do laboratório, explorei os seguintes pontos:
- Diferença entre os tipos de armazenamento: **Blobs, Arquivos, Filas e Discos**.  
- Como escolher o tipo de armazenamento adequado para cada cenário.  
- Funcionamento do **Locally Redundant Storage (LRS)** e outros modelos de redundância (ZRS, GRS, GZRS).  
- Uso do **AzCopy** para transferir dados de forma rápida e eficiente.  
- Quando utilizar **Azure Data Box** para migração de grandes volumes de dados.  
- Configuração de **compartilhamentos de arquivos (Azure Files)** e mapeamento em estações de trabalho.  
- Diferença entre **VPN, ExpressRoute e VNet Peering** para comunicação entre redes.  
- Estratégias de **alta disponibilidade e durabilidade** no armazenamento.  

## Passo a Passo Documentado
1. Criar um **Grupo de Recursos** para centralizar os serviços.  
2. Configurar um **Blob Storage** e realizar upload de arquivos.  
3. Criar um **Azure File Share** e mapear em uma estação de trabalho.  
4. Testar **AzCopy** para copiar arquivos entre local e nuvem.  
5. Explorar os modelos de redundância (LRS, ZRS, GRS, GZRS).  
6. Simular cenários de migração com **Data Box**.  
7. Documentar a arquitetura final e os testes realizados.  

## Comparativo dos Tipos de Armazenamento no Azure

| Tipo de Armazenamento | Características | Casos de Uso | Protocolos de Acesso |
|------------------------|-----------------|--------------|----------------------|
| **Blobs**             | Armazenamento de objetos (arquivos, imagens, vídeos, backups). Escalável e econômico. | Conteúdo estático de sites, mídia, backups, Big Data. | HTTP/HTTPS, SDKs, REST API |
| **Arquivos (Azure Files)** | Compartilhamento de arquivos gerenciado na nuvem. Pode ser mapeado como unidade de rede. | Migração de aplicações legadas, compartilhamento entre usuários, integração híbrida. | SMB (Server Message Block), REST API |
| **Filas (Queues)**     | Serviço de mensageria para comunicação assíncrona entre componentes distribuídos. | Processamento em lote, integração de microserviços, filas de tarefas. | REST API, SDKs |
| **Discos (Azure Disks)** | Armazenamento persistente para Máquinas Virtuais. Alta performance e baixa latência. | Bancos de dados, sistemas críticos, aplicações que exigem IOPS elevado. | Conectados diretamente às VMs |
  

## Conclusão
Esse desafio reforçou minha compreensão sobre como utilizar os diferentes serviços de armazenamento do Azure, equilibrando **custo, desempenho, durabilidade e disponibilidade** de acordo com as necessidades de cada aplicação.

---

**Autor(a):** Ana Quézia de Oliveira Souza

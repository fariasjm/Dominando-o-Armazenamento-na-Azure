# Dominando o Armazenamento na Azure

O Azure oferece vários tipos de serviços de armazenamento para diferentes necessidades:
  - Blob Storage: Armazenamento de objetos para grandes volumes de dados não estruturados, como arquivos de mídia, backups e logs.
  - Azure Files: Compartilhamento de arquivos via protocolo SMB, usado para armazenar e compartilhar arquivos de forma semelhante a um sistema de arquivos tradicional.
  - Queue Storage: Armazenamento de mensagens para comunicação entre componentes distribuídos.
  - Table Storage: Armazenamento de dados semi-estruturados e NoSQL.

1. No portal do Azure (portal.azure.com), Clique em *Armazenamento* e depois em *Criar Conta de Armazenamento*.
2. Escolha a região, tipo de replicação (Local, Zona, Geográfica) e camada de desempenho (Padrão ou Premium).
3. Defina um nome para a conta e selecione opções de segurança.
   
![image](https://github.com/user-attachments/assets/479f53dd-6b45-4570-ac64-b43df2c05b87)
  
  - Estratégias de Armazenamento e Gerenciamento:
    - Replicação de Dados - Garante durabilidade e alta disponibilidade replicando dados entre regiões geográficas.
    - Controle de Acesso - Utilize o controle de acesso baseado em função (RBAC) e listas de controle de acesso (ACLs) para gerenciar quem pode acessar seus dados.
  - Segurança e Criptografia:
    A segurança é uma prioridade no Armazenamento Azure. Todos os dados são criptografados em repouso.
    Azure Storage Explorer - Ferramenta de gerenciamento de armazenamento na nuvem para upload, download e gerenciamento.
  - Otimização de Desempenho:
    - Azure Data Lake Storage Gen2 - Oferece armazenamento de objetos de grande escala com otimização para cargas de trabalho analíticas.
    - Azure Elastic SAN - Simplifica a implantação, escalonamento, gerenciamento e configuração de um SAN na Azure.
  - Soluções de Armazenamento Híbrido:
    - Azure StorSimple - Dispositivos híbridos de armazenamento que gerenciam dados entre locais e a nuvem.  





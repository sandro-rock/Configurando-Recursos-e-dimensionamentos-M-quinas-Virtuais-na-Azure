# Configurando-Recursos-e-dimensionamentos-M-quinas-Virtuais-na-Azure
Criando, Configurando Recursos e Dimensionando Máquinas Virtuais no Microsoft Azure

Criando uma Máquina Virtual (VM)

Acesse o portal do Azure.
No menu de navegação, procure por "Máquinas Virtuais" e clique em "Criar".
Selecione a assinatura e o grupo de recursos onde deseja criar a VM.
Defina as configurações da máquina, como:
Nome da VM.
Região (onde será hospedada).
Tamanho da VM (número de vCPUs e quantidade de RAM).
Escolha a imagem do sistema operacional (Windows, Linux, etc.).
Configure a autenticação (senha ou chave SSH).
Configurando Recursos da VM

Escolha as opções de disco: discos SSD ou HDD gerenciados para o sistema operacional e discos de dados adicionais, se necessário.
Configure a rede:
Escolha uma VNet (rede virtual) ou crie uma nova.
Selecione uma sub-rede existente ou crie uma nova para a VM.
Defina as configurações de segurança, como Grupos de Segurança de Rede (NSG), que controlam o tráfego de entrada e saída.
Habilite outras opções, como IP público, extensões da VM e monitoramento.
Dimensionamento e Escalabilidade

Dimensionamento Manual:

Ao criar ou após a criação da VM, você pode ajustar o tamanho da máquina virtual conforme a necessidade de processamento e memória (escalonamento vertical).
No painel da VM, clique em "Dimensionar" para selecionar um novo tamanho, ajustando CPU e RAM.
Dimensionamento Automático (Escalonamento Horizontal):

Utilize Conjuntos de Escala de Máquinas Virtuais (VM Scale Sets) para aumentar ou diminuir automaticamente o número de instâncias da VM conforme a demanda.
Na criação, escolha "Conjuntos de Escala" e configure as regras de escalabilidade (como CPU ou uso de memória), permitindo que o Azure crie ou remova VMs de acordo com o tráfego.
Finalização e Revisão

Após a configuração de recursos e redes, revise suas configurações.
Clique em "Criar". O Azure iniciará a implementação da máquina virtual, e você poderá monitorar o progresso.
Esses passos permitem criar e configurar máquinas virtuais no Azure, ajustando os recursos e o desempenho de acordo com as necessidades do seu ambiente.

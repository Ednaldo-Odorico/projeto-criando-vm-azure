# projeto-criando-vm-azure

As máquinas virtuais (VM) do Azure podem ser criadas por meio do Portal do Azure. Esse método fornece uma interface de usuário baseada em navegador para criar as VMS seus recursos relacionados. 

Entre no portal do Azure. https://portal.azure.com/

Criar máquina virtual

Digite máquinas virtuais na pesquisa.

Em Serviços, selecione Máquinas virtuais.

Na página Máquinas virtuais, clique em Criar e selecione Máquina virtual do Azure. A página Criar uma máquina virtual é aberta.

Em Detalhes da instância, insira myVM no Nome da máquina virtual e escolha Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2 na Imagem. Deixe os outros padrões.

Captura de tela da seção Detalhes da instância, onde você fornece um nome para a máquina virtual e seleciona a região, a imagem e o tamanho dela.

 Observação

Alguns usuários agora verão a opção de criar VMs em várias zonas. Para saber mais sobre essa nova capacidade, confira Criar máquinas virtuais em uma zona de disponibilidade. Captura de tela mostrando que existe a opção de criar máquinas virtuais em várias zonas de disponibilidade.

Em Conta de administrador, forneça um nome de usuário, como azureuser e uma senha. A senha deve ter no mínimo 12 caracteres e atender a requisitos de complexidade definidos.

Captura de tela da seção Conta de administrador, onde você fornece o nome de usuário e a senha do administrador.

Em Regras de porta de entrada, escolha Permitir portas selecionadas e, em seguida, selecione RDP (3389) e HTTP (80) na lista suspensa.

Captura de tela da seção de regras de porta de entrada, na qual você seleciona as portas nas quais as conexões de entrada são permitidas

Deixe os padrões restantes e, em seguida, selecione o botão Examinar + criar na parte inferior da página.

Inicie uma conexão da área de trabalho remota para a máquina virtual. Estas instruções ensinam a se conectar aàsua VM de um computador com Windows.

Captura de tela mostrando o botão Examinar + criar na parte inferior da página.

Selecione Conectar>RDP na página de visão geral de sua máquina virtual.

Captura de tela da página de visão geral da máquina virtual mostrando o local do botão Conectar.

Na guia Conectar-se ao RDP, mantenha as opções padrão para se conectar por endereço IP pela porta 3389 e clique em Baixar arquivo RDP.

Abra o arquivo RDP baixado e clique em Conectar quando solicitado.

Na janela Segurança do Windows, selecione Mais opções e Usar uma conta diferente. Digite o nome de usuário como localhost\nome de usuário, insira a senha que você criou para a máquina virtual e clique em OK.

Você pode receber um aviso do certificado durante o processo de logon. Clique em Sim ou em Continuar para criar a conexão.

Após a execução da validação, selecione o botão Criar na parte inferior da página. Captura de tela mostrando que a validação foi aprovada. Clique no botão Criar para criar a VM.

Após a conclusão da implantação, selecione Ir para o recurso.

Captura de tela mostrando a próxima etapa de ir para o recurso.

# Preparação de Ambiente
### Vamos preparar o ambiente para desenvolvimento de aplicações

#### Neste ambiente iremos instalar e configurar os seguintes recursos:
 - Máquina Virtual(Virtualbox)
 - Distribuição Linux(Ubuntu Server)
 - Nasm
 - Compilador da linguagem C
 - Configurar o ip e a porta de comunicação entre a máquina real e a virtual
 - Configurar o acesso via SSH entre o VSCode e o ServidorLinux
 - Instalar as extensões: Material Icon, Nasm, SSH e Linguagem C/C++

#### Máquina Virtual(Virtualbox)

!["Logo VirtualBox"](virtualbox.png)

Máquina virtual é uma ferramenta que permite a crição de novos "computadores" e a instalação de sistemas operacionais, para estudo ou trabalho.

Para o nosso estudo iremos usar o VirtualBox, da Oracle.
Para instalar, basta fazer o download no link a seguir:

<a href="https://www.virtualbox.org/wiki/Downloads" target="_blank"> VirtualBox </a>

##### Criando a máquina virtual para o nosso estudo

 - Configuração:
    > - Nome da Máquina: Servidor
    > - Memória: 4GB(4096)
    > - Processador: 2
    > - Disco: 100GB
    > - IP e Porta do Host: 127.0.0.1 e 22
    > - IP e Porta do Convidado: 10.0.2.15 e 22


- Tela inicial de configuração

<img src=tela_configuracao_1.png width=500 height=250>

- Tela configuração do Hardware

<img src=tela_configuracao_2.png width=500 height=250>

- Tela de configuração do Disco

<img src=tela_configuracao_3.png width=500 height=250>

- Tela Final de configuração

<img src=tela_configuracao_4.png width=500 height=250>

- Tela inicial de configuração de Rede

<img src=tela_configuracao_5.png width=500 height=250>

- Tela de configuração de Portas e IP

<img src=tela_configuracao_6.png width=500 height=250>

#### Distribuição Ubuntu Server

<img src=logoubuntu.png width=200 height=200>

Para o nosso estudo iremos utilizar uma distribuição Linux para servidores chamada Ubuntu.
Acompanhe o processo de instalação:

Faça o download aqui: 
<a href="https://ubuntu.com/download/server" target="_blank"> Ubuntu Server </a>

- Acompanhe a instalação

- Tela de Inicio de instalação
<img src=tela_inicio_ubuntu.png>
- Tela de seleção de idioma
<img src=tela_selecionar_idioma.png>
- Tela de seleção de teclado - portugues brasil
<img src=tela_selecionar_teclado_portugues.png>
- Tela de tipo de instalação
<img src=tela_tipo_instalacao.png>
- Tela configuração de rede
<img src=tela_configuracao_rede.png>
- Tela configuração do proxy
<img src=tela_configuracao_proxy.png>
- Tela pacontes de atualização
<img src=tela_configuracao_pacotes_atualizacao.png>
- Tela configuração do disco
<img src=tela_configuracao_disco.png>
- Tela layout do disco
<img src=tela_layout_confi9guracao_disco.png>
- Tela configuração do usuario
<img src=tela_configuracao_usuario.png>
- Tela configuração do SSH
<img src=tela_configuracao_ssh.png>
- Tela do fim da instalação
<img src=tela_fim_instalacao.png>



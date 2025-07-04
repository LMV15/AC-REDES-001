Exercício: Instalação de um Servidor LAMP e Configuração de Website com HTTPS

Objetivo

Instalar e configurar um servidor LAMP (Linux, Apache, MySQL, PHP) em um servidor de nuvem com Ubuntu, configurar um certificado SSL gratuito para HTTPS e fazer o website funcionar no IP público do servidor. Vocês irão instalar um tema gratuito do site StartBootstrap para praticar a configuração de um ambiente de servidor completo e seguro.

Passos para o Exercício

    1. Preparação do Ambiente
        ○ Inicie uma máquina virtual com o sistema operacional Ubuntu Server em um provedor de nuvem (como AWS, Azure, Google Cloud ou DigitalOcean).
        ○ Verifique se o servidor possui um IP público e que as portas 80 (HTTP), 443 (HTTPS) e 22 (SSH) estão abertas.
    2. Conexão ao Servidor
        ○ Conecte-se ao servidor via SSH utilizando o comando:
        ssh usuario@IP-do-servidor

Instalação do LAMP Stack:
https://www.digitalocean.com/community/tutorials/como-instalar-a-pilha-linux-apache-mysql-php-lamp-no-ubuntu-18-04-pt

Download do Tema Gratuito: Acesse o StartBootstrap (https://startbootstrap.com/themes) e escolha um tema gratuito para o seu site. Baixe o tema para o seu computador e, em seguida, transfira-o para o servidor via SCP ou diretamente via terminal.

Configuração do Apache para HTTPS (SSL):

https://www.digitalocean.com/community/tutorials/how-to-create-a-self-signed-ssl-certificate-for-apache-in-ubuntu-18-04-pt

Entrega

● Breve Relatório e Capturas de Tela: Inclua capturas de tela mostrando todo o processo e site funcionando.

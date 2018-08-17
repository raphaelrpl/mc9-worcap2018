# MC9 - Docker: introdução à administração de containers

 **Evento**: [WORCAP 2018](http://www.inpe.br/worcap/2018/)  
 **Data**: 23/08/2018  
 **Horário**: 15:30 - 17:30  
 **Local**: LIT  
 
**Ministrantes:**  
- [Vitor Conrado Faria Gomes, CAP/INPE](http://lattes.cnpq.br/2864513791602949)  
- [Raphael Willian da Costa](http://lattes.cnpq.br/7394226786935007)
- [Gilberto Ribeiro de Queiroz](http://lattes.cnpq.br/9981634193003068)

**Resumo**:  
Docker é uma tecnologia que fornece virtualização em nível do sistema operacional, evitando a sobrecarga da execução de máquinas virtuais. Esses ambientes virtuais, conhecidos por *containers*, permitem o empacotamento de aplicações e suas dependências, facilitando a implantação e portabilidade de sistemas.  
Esse curso aborda o funcionamento da tecnologia Docker, a configuração de containers através de Dockerfile, o compartilhamento de imagens, a preparação de um ambiente com múltiplos containers e ferramentas para o gerenciamento de containers. O curso terá conteúdo teórico e parte prática. Durante a parte prática, os participantes irão criar um ambiente com servidor web e banco de dados utilizando múltiplos containers Docker. 

# Requisitos

## 1. Instalação do Docker

Para a realização das atividades práticas do minicurso é **necessário** que o participante leve um notebook que, preferencialmente, tenha acesso a rede.  

Para o curso, e necessário instalar o **Docker** no seu computador. Siga as instruções conforme seu sistema operacional:

- Linux
  - [Ubuntu](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
  - [Debian](https://docs.docker.com/install/linux/docker-ce/debian/)
  - [CentOS](https://docs.docker.com/install/linux/docker-ce/centos/)
  - [Fedora](https://docs.docker.com/install/linux/docker-ce/fedora/)
- [Windows](https://docs.docker.com/docker-for-windows/install/#start-docker-for-windows)
- [Mac OS](https://docs.docker.com/docker-for-mac/install/)

Para usuários **Linux** execute os seguintes comandos após a instalação:

```bash
sudo usermod -aG docker $USER
```

Verifique se seu usuário consegue acessar o docker:
```bash
docker run hello-world
```

## 2. Criação de conta no Docker Hub (Opcional)

Crie uma conta no [Docker Hub](https://hub.docker.com/) para que as imagens criadas durante o minicurso possam ser salvas. 

# Material

O curso possui material para a parte [teórica](teoria) e para a parte [prática](pratica).

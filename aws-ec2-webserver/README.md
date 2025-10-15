# 💻 AWS EC2 Web Server

## 🎯 Objetivo  
Configurar uma instância **Amazon EC2** com **Linux**, instalando e executando um **servidor web** simples (Apache ou Nginx).  
O propósito deste laboratório é entender os conceitos básicos de máquinas virtuais na nuvem, grupos de segurança e acesso remoto via SSH. ⚙️  

---

## 🧰 Serviços Utilizados  
- **Amazon EC2** → Criação e gerenciamento da instância na AWS  
- **AWS IAM** → Controle de permissões e chaves de acesso  
- **AWS Security Groups** → Configuração de portas de rede (HTTP/SSH)  
- **Linux (Amazon Linux 2)** → Sistema operacional da instância  
- **Apache / Nginx** → Servidor web instalado na EC2  

---

## 🪜 Passos Realizados  

1. Criei uma instância **EC2 (t2.micro)** usando o **Free Tier** da AWS.  
2. Configurei um **Security Group** com portas **22 (SSH)** e **80 (HTTP)** liberadas.  
3. Conectei via SSH utilizando o arquivo `.pem` de chave privada.  
4. Instalei o servidor web (Apache ou Nginx).  
5. Criei uma página simples `index.html` para validar o funcionamento.  
6. Validei o acesso público via **endereço IP público da EC2**.  

---

## 🧠 Aprendizados  
- Criação e acesso seguro de instâncias EC2.  
- Noções de rede e grupos de segurança na AWS.  
- Instalação e gerenciamento básico de um servidor Linux remoto.  
- Diferença entre **servidor local** e **servidor na nuvem**.  

---

## 📸 Capturas (opcional)  
Imagens ou prints do processo:  
- Tela de criação da instância  
- Grupo de segurança configurado  
- Página aberta via endereço público  

---

## 💬 Observação  
Este laboratório complementa o primeiro (S3), evoluindo do conceito de **site estático** para um **servidor web real em execução**. ☁️  

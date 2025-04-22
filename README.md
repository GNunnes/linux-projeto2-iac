# 🚀 Script de Deploy Automático de Aplicação Web no Apache

Este projeto contém um script Bash simples, porém poderoso, para **atualização de servidor** e **deploy automatizado** de uma aplicação web estática utilizando o **Apache2** em sistemas Linux Debian/Ubuntu.

---

## 🛠️ O que o script faz?

Este script realiza as seguintes ações:

1. 🔄 Atualiza a lista de pacotes e o sistema com `apt-get update` e `upgrade`.
2. 🌐 Instala o servidor web Apache2.
3. 📦 Instala a ferramenta `unzip` para descompactar arquivos.
4. ☁️ Baixa uma aplicação web hospedada no GitHub.
5. 📂 Copia os arquivos da aplicação para o diretório padrão do Apache: `/var/www/html/`.

---

## 💻 Pré-requisitos

- Acesso como **root** ou com permissão `sudo`.
- Distribuição Linux baseada em Debian (ex: Ubuntu).
- Conexão com a internet.

---

## 📜 Como usar

Clone este repositório ou copie o conteúdo do script para um arquivo local:

bash
chmod +x deploy-servidor.sh
sudo ./deploy-servidor.sh

Clone este repositório ou copie o conteúdo do script para um arquivo local:

bash
chmod +x deploy-servidor.sh
sudo ./deploy-servidor.sh

Ou execute diretamente, se já estiver com permissão de execução:

bash
sudo bash deploy-servidor.sh  

## 🔗 Fonte da aplicação
O site utilizado como exemplo é o projeto de página estática do repositório:

📁 https://github.com/denilsonbonatti/linux-site-dio

📷 Resultado
Após a execução, o conteúdo estará disponível em:

http://localhost/  
ou  
http://SEU_IP/  

✨Dica Extra   
---
Se quiser tornar esse script ainda mais robusto, você pode adicionar:

- Verificação se o Apache já está instalado.
- Teste de conexão com a internet.
- Backup do /var/www/html/ antes de sobrescrever.

👨‍💻 Autor<br>
---
Desenvolvido por Gustavo Nunes<br>
Contribua com melhorias, issues ou sugestões! 🚀<br>

🧪 Licença<br>
---
Este projeto está sob a licença MIT.<br>
Veja o arquivo LICENSE para mais detalhes.<br>

yaml

---

Se quiser, posso adicionar **badges do GitHub**, um botão de **"Executar com Replit"**, ou até um exemplo de script `.service` pra automatizar isso no boot. É só pedir!








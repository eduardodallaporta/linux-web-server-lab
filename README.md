-- Versão Português --

# Linux Web Server Lab

Este projeto demonstra a configuração e validação de um servidor web local utilizando Linux (Ubuntu no WSL).

## Objetivo

O objetivo deste projeto é praticar conceitos fundamentais de Infraestrutura e Linux, incluindo:

- Criação e edição de arquivos utilizando Vim
- Execução e gerenciamento de um serviço web
- Verificação de portas abertas
- Testes de comunicação cliente-servidor
- Utilização de ferramentas essenciais de diagnóstico e rede no Linux

## Tecnologias utilizadas

- Ubuntu Linux (WSL)
- Python HTTP Server
- Vim
- Bash
- curl
- ss

## Estrutura do projeto

linux-web-server-lab/

│
├── index.html
├── README.md


## Etapas realizadas

1. Criação do diretório do projeto
2. Criação e edição do arquivo index.html utilizando Vim
3. Inicialização do servidor web local utilizando:
    python3 -m http.server 8000


4. Verificação da porta aberta utilizando:
    ss -tuln | grep 8000

5. Teste da comunicação cliente-servidor utilizando:
    curl http://localhost:8000


## Resultado

Servidor web local implantado e validado com sucesso em ambiente Linux.

## 📬 Contato
    - LinkedIn: www.linkedin.com/in/eduardo-dalla-porta
    - GitHub: eduardodallaporta


-- English Version  --

# Linux Web Server Lab

This project demonstrates the setup and validation of a local web server using Linux (Ubuntu on WSL).

## Objective

The goal of this project is to practice fundamental Infrastructure and Linux concepts, including:

- File creation and editing using Vim
- Running and managing a web service
- Validating open ports
- Testing client-server communication
- Using essential Linux networking and diagnostic tools

## Technologies Used

- Ubuntu Linux (WSL)
- Python HTTP Server
- Vim
- Bash
- curl
- ss

## Project Structure

linux-web-server-lab/

│
├── index.html
├── README.md


## Steps Performed

1. Created project directory
2. Created and edited index.html using Vim
3. Started local web server using:
    python3 -m http.server 8000

4. Verified open port using:
    ss -tuln | grep 8000

5. Tested client-server communication using:
    curl http://localhost:8000


## Result

Successfully deployed and validated a local web server running on Linux.

## 📬 Contact
    - LinkedIn: www.linkedin.com/in/eduardo-dalla-porta
    - GitHub: eduardodallaporta

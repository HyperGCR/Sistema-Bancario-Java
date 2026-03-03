# 🏦 Sistema Bancário Simples (CLI)

## 💻 Sobre o Projeto

Este projeto prático foi desenvolvido para consolidar os fundamentos da **Programação Orientada a Objetos (POO)** em Java. A aplicação simula o funcionamento básico de um terminal de autoatendimento bancário via linha de comando, focando na construção de regras de negócio sólidas e no raciocínio lógico estruturado.

## 🎯 O que eu aprendi

* **Encapsulamento e Segurança:** Proteção de dados sensíveis da aplicação (como o saldo da conta), garantindo que a modificação dos valores ocorra apenas através de métodos validados.
* **Modelagem de Regras de Negócio:** Implementação de validações lógicas, como impedir a realização de saques quando o saldo em conta for insuficiente.
* **Interação via Console (CLI):** Construção de menus interativos para receber comandos do usuário e exibir as respostas dinâmicas do sistema.

## ✨ Funcionalidades

O sistema oferece as operações essenciais de um caixa eletrônico de forma interativa:
* 🟢 **Consultar Saldo:** Exibição imediata do valor atual disponível na conta.
* 🟢 **Realizar Depósito:** Adição de valores ao saldo da conta de forma segura.
* 🟢 **Realizar Saque:** Subtração de valores com validação prévia de limite e saldo disponível.

## 📁 Arquitetura do Projeto

A estrutura foi desenhada para manter a separação clara entre a regra de negócio e a interface com o usuário:

<details>
<summary><b>Clique para ver a estrutura de pastas</b></summary>

<br>

📦 **model**
> 📄 `ContaBancaria.java`: Classe que representa a conta, armazenando os atributos financeiros e as lógicas de depósito e saque.

📦 **main**
> 📄 `Main.java`: Ponto de entrada da aplicação, contendo o menu interativo e gerenciando os inputs do usuário.

</details>

## 🛠️ Como executar na sua máquina

1. **Clone este repositório:**
```bash
git clone [https://github.com/HyperGCR/Sistema-Bancario-Java.git](https://github.com/HyperGCR/Sistema-Bancario-Java.git)

2.Compile e execute:

Abra o projeto na sua IDE preferida (VSCode, Eclipse, IntelliJ) ou navegue até a pasta raiz pelo terminal.

Execute o arquivo Main.java para iniciar a interação no console.

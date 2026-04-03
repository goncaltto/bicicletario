# 🚲 Sistema de Controle de Bicicletário (SCB)

## 📌 Sobre o Projeto
Este projeto foi desenvolvido como trabalho acadêmico e tem como objetivo implementar um **Sistema de Controle de Bicicletário (SCB)**, permitindo o aluguel e devolução de bicicletas de forma automatizada.

O sistema simula um cenário real onde usuários podem retirar bicicletas em totens distribuídos pela cidade e devolvê-las em qualquer ponto disponível, com controle de tempo, cobrança e estado das bicicletas.

A arquitetura adotada foi baseada em **microsserviços**, onde cada integrante do grupo foi responsável pelo desenvolvimento de um serviço específico.

---

## 🧩 Arquitetura do Sistema

O sistema foi dividido em três microsserviços principais:

- 🔹 **Microsserviço de Bicicletas**  
  Responsável pelo gerenciamento das bicicletas  
  **Desenvolvido por:** Jonathan Gonçalves  
- 🔹 **Microsserviço de Aluguel**  
  Responsável pelo controle de empréstimos e devoluções, incluindo regras de cobrança  
  **Desenvolvido por:** Isabelle Araujo  
- 🔹 **Microsserviço de Serviços Externos**  
  Responsável pela comunicação com serviços externos (ex: pagamento, notificações)  
  **Desenvolvido por:** Barbara Miguez  

---

## 🧩 Microsserviço de Bicicletas
Este repositório se refere somente ao gerenciamento das bicicletas. As funcionalidades se listam como: 
- CRUD das Bicicletas
- CRUD dos Totens
- CRUD das Trancas
- Gerencimento de cada item anterior.

## ⚙️ Tecnologias Utilizadas

- Java  
- Spring Boot  
- Maven  
- Postman (testes de API)  
- SonarQube (análise de qualidade de código)  

---

## 🚀 Como Executar o Projeto

### Pré-requisitos:
- Java 8+
- Maven
- IDE (IntelliJ, Eclipse, VS Code)

### Passos:

```bash
# Clonar o repositório
git clone https://github.com/goncaltto/bicicletario

# Acessar o projeto
cd bicicletario

# Rodar o projeto
mvn spring-boot:run
```

##🧪 Testes de API

Os endpoints podem ser testados utilizando o Postman.

Exemplos:

- Cadastro de bicicleta
- Consulta de bicicletas
- Atualização de status

##📊 Qualidade de Código

O projeto utiliza SonarQube para análise de qualidade, permitindo identificar:

- Code smells
- Bugs
- Vulnerabilidades
- Cobertura de código
  
##📚 Contexto Acadêmico

Projeto desenvolvido na graduação em Sistemas de Informação (UNIRIO) com foco em:

Arquitetura de microsserviços
Desenvolvimento de APIs REST
Boas práticas de engenharia de software
Modelagem baseada em requisitos

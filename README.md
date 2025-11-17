# 🧪 Projeto de QA | Testes de Software  
_Repositório criado para demonstrar os conhecimentos adquiridos durante o bootcamp, utilizando práticas de teste estruturadas, cenários reais e documentação técnica._

---

## 🚀 Sobre o Projeto
Este projeto foi desenvolvido com o objetivo de aplicar conceitos essenciais de **Qualidade de Software (QA)**, cobrindo desde testes manuais até fundamentos de automação.

Aqui você encontrará:
- 📌 Casos de teste  
- 📌 Cenários de teste  
- 📌 Documentação  
- 📌 Técnicas de análise  
- 📌 Processo de verificação e validação  

Tudo seguindo boas práticas para garantir clareza, padronização e reprodutibilidade.

---

## 🧵 Conteúdos Trabalhados

### ✔ **1. Tipos de Teste**
- Testes Funcionais  
- Testes Não Funcionais  
- Testes Caixa-Preta  
- Testes Caixa-Branca  
- Testes de Regressão  
- Testes de Integração  
- Testes de Sistema  

---

### ✔ **2. Estruturas e Modelos de Teste**
- Casos de Teste (CT)  
- Planos de Teste  
- Cenários BDD  
- Critérios de Aceitação  
- Técnicas de Particionamento de Equivalência  
- Análise de Valor Limite  

---

### ✔ **3. Normas e Padrões**
Trabalhamos em conformidade com padrões de qualidade amplamente utilizados:
- 📘 **ISO/IEC 25010** – modelo de qualidade de software  
- 📘 **ISO/IEC/IEEE 29119** – normas para documentação de teste  
- 📘 **IEEE 829** – padrão de documentação  





---

## 🧪 Exemplo de Caso de Teste



### 📝 Caso de Teste – CT001: Login com credenciais válidas

**Objetivo:**  
Validar se o usuário consegue acessar o sistema com e-mail e senha corretos.

**Pré-condições:**  
– Usuário cadastrado  
– Acesso ao ambiente de teste  

**Passos:**  
1. Acessar a página de login  
2. Inserir e-mail válido  
3. Inserir senha válida  
4. Clicar em "Entrar"

**Resultado Esperado:**  
Usuário deve ser direcionado ao dashboard.


🧬 Exemplo de Cenário BDD

Feature: Login
  Scenario: Login com credenciais válidas
    Given que o usuário está na página de login
    When inserir e-mail válido
     And inserir senha válida
     And clicar em "Entrar"
    Then o sistema deve redirecionar para o dashboard
    
---

📚 Tecnologias e Conceitos Utilizados

Testes Manuais

BDD com Gherkin

Conceitos fundamentais de QA

Estruturação e documentação técnica

Análise de requisitos

Critérios de aceitação

Estratégias de teste

---

🧑‍💻 Autor(a)

Projeto desenvolvido por Isabela Duarte durante estudos em Qualidade de Software.

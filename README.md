# Explorando Workflows Automatizados com AWS Step Functions - Desafio de Projeto
 Code Girls 2025
 <br>
 *DIO em parceria com o Santander*

---

# 🚀 AWS Step Functions – Resumo

## 📖 O que é?
O **AWS Step Functions** é um serviço da Amazon que ajuda a orquestrar vários serviços e tarefas em uma **sequência de passos**, por meio de fluxos de trabalho visuais.
Para utilizá-lo, você define um workflow dividido em estados (steps). Esse fluxo pode ser descrito em JSON ou montado de forma simples no editor visual, arrastando e conectando caixinhas!

---

## ⚙️ Como funciona?
- O fluxo é definido em **estados (states)**, cada um representando uma ação.  
- Os estados podem ser:
  - **Task** → executa algo (ex.: função Lambda).  
  - **Choice** → faz uma decisão condicional.  
  - **Wait** → espera um tempo antes de continuar.  
  - **Parallel** → executa tarefas em paralelo.  
  - **Success / Fail** → define o fim do workflow.  
- Os workflows podem ser descritos em **JSON** ou criados no **editor visual** da AWS.  

---

## 🎯 Benefícios
- **Organização**: centraliza e simplifica processos complexos.  
- **Confiabilidade**: trata erros, repetições e exceções.  
- **Escalabilidade**: integra facilmente com outros serviços da AWS.  
- **Visualização**: fluxos fáceis de entender através do editor gráfico.  

---

## 💡 Exemplos de uso
- Processar pedidos de e-commerce (pagamento → estoque → envio).  
- Workflows de machine learning (pré-processamento → treino → avaliação).  
- Automação de tarefas de ETL (coletar → transformar → armazenar dados).  

---

## 📚 Insights adquiridos
- Com Step Functions é possível **substituir códigos complexos** de orquestração por fluxos visuais.  
- Os **estados deixam claro** cada etapa do processo, facilitando manutenção.  
- A integração com **Lambda, DynamoDB, S3 e outros serviços** amplia muito as possibilidades de uso.  

---

## 🔗 Referências
- [Documentação Oficial AWS Step Functions](https://docs.aws.amazon.com/step-functions/)  
- [AWS Step Functions – Guia de Início Rápido](https://aws.amazon.com/step-functions/)

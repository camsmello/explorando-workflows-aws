# Explorando Workflows Automatizados com AWS Step Functions 🚀

Desafio de projeto DIO em parceria com o Santander
<br>
**Code Girls** 2025

---

## 📖 O que é?
O **AWS Step Functions** é um serviço da **Amazon** que ajuda a orquestrar vários serviços e tarefas em uma sequência de passos, por meio de **fluxos de trabalho visuais**. Para utilizá-lo, você define um workflow dividido em estados (steps). Esse fluxo pode ser descrito em JSON ou montado de forma simples no editor visual, arrastando e conectando caixinhas.

---

## ⚙️ Como funciona?
- O fluxo é definido em **estados (states)**, cada um representando uma ação.  
- Os workflows podem ser descritos em **JSON** ou criados no **editor visual** da AWS.  
- O Step Functions executa esses estados na ordem definida, **cuidando automaticamente do que acontece em caso de falhas, repetições e ramificações.**

---

## 🧩 Componentes de um Workflow no AWS Step Functions

Um workflow no Step Functions é composto por **estados (states)**. Cada estado representa uma etapa da execução. Os principais são:

- **Task** → Executa uma ação, como rodar uma função Lambda, chamar uma API ou interagir com outro serviço da AWS.  
- **Choice** → Permite criar decisões condicionais (se X → segue por um caminho, se não → segue outro).  
- **Wait** → Faz o workflow aguardar por um tempo específico ou até uma data/hora definida antes de prosseguir.  
- **Parallel** → Executa múltiplas ramificações em paralelo e só continua quando todas terminam.  
- **Map** → Itera sobre uma lista de itens, executando o mesmo conjunto de passos para cada elemento (como um "for" em programação).  
- **Pass** → Simplesmente passa os dados adiante sem realizar nenhuma ação, útil para testes e ajustes de fluxo.  
- **Fail** → Finaliza a execução do workflow com status de falha.  
- **Succeed** → Finaliza a execução do workflow com status de sucesso.  

Esses componentes permitem construir desde fluxos simples até processos complexos e automatizados.

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

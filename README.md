# Perceptron de Rosenblatt – RU 5240251

## 📌 Descrição
Projeto acadêmico da disciplina **Inteligência Artificial** (Uninter).  
Implementação de um neurônio artificial baseado no algoritmo de **Perceptron de Rosenblatt** com 7 entradas, treinado para classificar padrões em relação ao RU **5240251**.  

O modelo foi desenvolvido com **50 amostras** e alcançou convergência na **época 59**, classificando corretamente todos os padrões.  

---

## 🎯 Objetivo
- Demonstrar o funcionamento completo de um Perceptron simples.  
- Treinar o neurônio para distinguir padrões **MAIOR** ou **MENOR** que o RU 5240251.  
- Validar o processo de aprendizado supervisionado com ajuste de pesos e bias.  

---

## 🛠️ Funcionamento
- **Entradas (x1 a x7)**: dígitos numéricos do padrão.  
- **Pesos (w1 a w7)**: inicializados aleatoriamente e ajustados durante o treinamento.  
- **Bias**: constante de ativação (1.0).  
- **Função de ativação**: degrau (saída 1 se net > 0, senão 0).  
- **Regra de aprendizado**:  
  \[
  \Delta w_i = K \cdot (d - y) \cdot x_i
  \]  
  com taxa de aprendizado **K = 0.1**.  

---

## 📊 Resultados
- Conjunto de dados: **50 amostras** com 7 características cada.  
- Classificação:  
  - **ALTA (1)** → valor ≥ 5240251  
  - **BAIXO (-1)** → valor < 5240251  
- Convergência atingida na **época 59**, com erro total = 0.  
- Validação realizada com novos padrões, confirmando generalização do modelo.  

---

## 📄 Documentação
O arquivo [`5240251 Fabio Santos.xlsx`](./5240251%20Fabio%20Santos.xlsx) contém:  
- Conjunto de dados de treinamento (50 amostras).  
- Registro completo das épocas e ajustes de pesos.  
- Aba de validação com cálculo passo a passo do neurônio após o treinamento.  

---

## 🚀 Como executar
Este projeto foi desenvolvido em planilha Excel para fins acadêmicos.  
Para reproduzir:  
1. Abra o arquivo `5240251 Fabio Santos.xlsx`.  
2. Navegue pelas abas **Capa**, **Neuronio**, **Treinamento** e **Amostra**.  
3. Insira novos padrões na aba de validação para observar a resposta do neurônio.  

---

## 👤 Autor
- **Nome**: Fabio Santos  
- **RU**: 5240251  
- **Curso**: CST em Redes de Computadores – 2025  

---

## 📜 Licença
Este projeto foi desenvolvido para fins **acadêmicos** na Uninter.  
Caso seja reutilizado, recomenda-se aplicar a licença **MIT** ou outra de sua preferência.

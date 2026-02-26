# 🚀 Missão Aurora Siger – Relatório Operacional de Pré-Decolagem

## 📌 Objetivo
Este projeto simula a validação técnica da nave Aurora Siger antes da decolagem, utilizando lógica booleana, algoritmos estruturados e automação em Python.

A decisão final da missão é baseada na verificação de parâmetros críticos da telemetria.

---

## 📊 Telemetria Avaliada

- Temperatura interna
- Temperatura externa
- Integridade estrutural (0 ou 1)
- Nível de energia (%)
- Pressão dos tanques
- Status dos módulos críticos

A nave só pode decolar se todos os parâmetros estiverem dentro das faixas seguras estabelecidas.

---

## 🧠 Algoritmo de Verificação

O algoritmo verifica sequencialmente cada parâmetro crítico.

Caso algum esteja fora da faixa segura, a missão é automaticamente abortada.

Se todos estiverem corretos, o sistema imprime:

PRONTO PARA DECOLAR

---

## 🐍 Script Python

O notebook contém:

- Definição dos dados da telemetria
- Estrutura condicional com lógica booleana
- Impressão do status final da missão

Arquivo principal:
`aurora_pre_decolagem.ipynb`

---

## 🔋 Análise Energética

O projeto também considera:

- Capacidade total da bateria (kWh)
- Percentual de carga atual
- Consumo estimado na decolagem
- Perdas energéticas

Foi calculada a autonomia restante após a decolagem.

---

## ▶️ Como Executar

1. Baixar o arquivo `.ipynb`
2. Abrir no Google Colab ou Jupyter Notebook
3. Executar todas as células

---

## 👨‍💻 Autor

Samuel Felipe Furtado Freire  
Curso: Ciência da Computação – FIAP

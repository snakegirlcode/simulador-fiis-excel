# 📊 Simulador de Investimentos em Fundos Imobiliários (FIIs)

Este projeto é uma ferramenta prática desenvolvida em Excel para simular investimentos em Fundos Imobiliários (FIIs). Com base nos aportes mensais, tempo de investimento e rendimento esperado, a planilha calcula o crescimento do patrimônio e os dividendos acumulados, permitindo uma análise clara do potencial de retorno.

## ✅ Funcionalidades

- Interface simples na aba **APP**
- Inserção de dados como:
  - Valor inicial investido
  - Aportes mensais
  - Tempo de investimento
  - Rendimento mensal estimado
- Cálculo automático de:
  - Patrimônio acumulado mês a mês
  - Dividendos mensais
  - Rendimento total

## 📊 Fórmulas e Lógica Aplicada

- **Rendimento Mensal** = `Patrimônio Anterior * Taxa de Rendimento`
- **Patrimônio Acumulado** = `Valor anterior + Aporte + Rendimento`
- **Dividendos** = `Patrimônio Atual * Taxa de Rendimento`
- **Valor Futuro (VF)** com Excel:
  ```excel
  =VF(taxa; períodos; -aporte; -investimento_inicial)
  ```

## 🧮 Tecnologias e Ferramentas

- Microsoft Excel
- Fórmulas financeiras intermediárias
- Git e GitHub para documentação

## 🗂️ Estrutura do Projeto

```
Simulador-FIIs-Excel/
├── invest_project.xlsx         # Planilha da simulação
├── README.md                   # Documentação do projeto
```

## 🚀 Como Usar

1. Abra a planilha `invest_project.xlsx`.
2. Vá até a aba **APP**.
3. Insira os dados nos campos indicados (valor inicial, aportes, tempo, taxa).
4. Veja automaticamente os resultados sendo atualizados.

## 📌 Objetivos de Aprendizagem

- Criar ferramentas de simulação de investimentos em Excel
- Aplicar cálculos financeiros como rendimento mensal e cálculo de dividendos
- Documentar um projeto técnico no GitHub

---

> Projeto desenvolvido como parte do desafio da DIO para a formação em Excel e Finanças Pessoais.  
> Criado por Thaís de Sousa Campos 💼

# 🌾 Agro+ — Assistente Financeiro Rural

Projeto desenvolvido para o Lab **"Construa Seu Assistente Virtual Com Inteligência Artificial"** da **DIO**.

##  O Problema

O produtor rural sabe quanto ganhou, mas não sabe exatamente quanto gastou. O controle financeiro da fazenda é feito no caderno ou em planilhas sem muito controle e no fim do ano não sobrou nada.

##  A Solução

O **Agro+** é um assistente financeiro que o produtor conversa naturalmente para registrar gastos e receitas e entender a situação financeira da fazenda sem planilhas, sem formulários.

## 📁 Estrutura do Projeto

```
agro-mais/
├── README.md
├── data/
│   └── base_conhecimento.json
├── docs/
│   ├── documentacao.md
│   ├── prompts.md
│   ├── avaliacao.md
│   └── pitch.md
└── src/
    └── agro_mais.ipynb
```

##  Como Executar

1. Abra o notebook `src/agro_mais.ipynb` no Google Colab
2. Instale a dependência: `!pip install groq -q`
3. Insira sua chave da API Groq
4. Execute e converse com o Agro+!

##  Os 6 Passos do Desafio

| Passo | Entrega |
|---|---|
| 1. Documentação | `docs/documentacao.md` |
| 2. Base de Conhecimento | `data/base_conhecimento.json` |
| 3. Prompts | `docs/prompts.md` |
| 4. Aplicação Funcional | `src/agro_mais.ipynb` |
| 5. Avaliação e Métricas | `docs/avaliacao.md` |
| 6. Pitch | `docs/pitch.md` |


## 🚀 Pitch

**Problema:** Produtor rural não acompanha os gastos da fazenda com rigor  e no fim do ano não sobrou nada.

**Solução:** Um assistente que registra gastos e receitas por conversa, categoriza automaticamente e mostra o diagnóstico financeiro quando o produtor precisar.

**Valor:** Encarar a fazenda como empresa com números reais.


*Projeto desenvolvido com auxílio do Claude, IA da Anthropic.*
*Autora: Ester Correa*

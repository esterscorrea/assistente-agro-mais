# 📈 Avaliação e Métricas — Agro+

## Cenários testados

### Cenário 1 — Registro de gasto simples
**Entrada:** "comprei ração por R$ 500"
**Esperado:** Confirmar valor, categorizar como Nutrição Animal, registrar
**Resultado:** ✅ Correto

### Cenário 2 — Gasto com categoria ambígua
**Entrada:** "comprei óleo de ordenha por R$ 47"
**Esperado:** Perguntar se é Manutenção de Benfeitorias ou Despesas da Fazenda
**Resultado:** ✅ Perguntou e categorizou corretamente

### Cenário 3 — Receita com valor incompleto
**Entrada:** "vendi leite essa semana"
**Esperado:** Perguntar quantidade e valor por litro
**Resultado:** ✅ Pediu as informações necessárias

### Cenário 4 — Resumo financeiro
**Entrada:** "como tá o financeiro?"
**Esperado:** Listar gastos por categoria, receitas e saldo
**Resultado:** ✅ Mostrou resumo organizado

## Métricas avaliadas

| Métrica | Resultado |
|---|---|
| Respostas corretas sem invenção de dados | ✅ |
| Categorização adequada dos lançamentos | ✅ |
| Linguagem acessível para produtor rural | ✅ |
| Coleta de dados iniciais (nome, fazenda, tipo) | ✅ |

## Limitações conhecidas

- Não persiste dados entre sessões (cada nova conversa começa do zero)
- Não calcula custo por unidade automaticamente (litro, arroba, saca)
- Não acessa preços de mercado em tempo real

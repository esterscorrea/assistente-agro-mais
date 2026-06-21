# 📈 Avaliação e Métricas — Agro+

## Como o agente foi avaliado?

O Agro+ foi testado com cenários reais de uso no campo.

## Cenários Testados

### Cenário 1 — Registro simples
> Produtor: "comprei ração por R$ 500"
> ✅ Agente registrou corretamente na categoria Nutrição Animal

### Cenário 2 — Categoria ambígua
> Produtor: "gastei R$ 47 com óleo de ordenha"
> ✅ Agente perguntou se era Manutenção de Benfeitorias ou Manutenção de Máquinas

### Cenário 3 — Resumo financeiro
> Produtor: "como tá o financeiro?"
> ✅ Agente listou gastos por categoria, receitas e saldo corretamente

### Cenário 4 — Informação incompleta
> Produtor: "comprei adubo"
> ✅ Agente perguntou o valor antes de registrar

## Métricas

| Métrica | Resultado |
|---|---|
| Categorização correta | ✅ Acertou em cenários claros |
| Pergunta quando ambíguo | ✅ Sempre perguntou categoria quando necessário |
| Nunca inventou valores | ✅ Sempre pediu confirmação |
| Linguagem acessível | ✅ Tom simples e direto |

## Limitações Conhecidas

- Não acessa preços de mercado em tempo real
- Não faz projeções futuras
- Não persiste dados entre sessões (versão atual)

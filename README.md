# ⏱️ Calculadora de Jornada

> Chega de ficar olhando pro relógio sem saber a que horas você pode ir embora.

Calculadora de jornada diária com suporte a múltiplos períodos (saída para almoço, compromissos, etc.) que mostra em tempo real **a que horas você pode ir embora**.

---

## Como usar

1. Acesse a calculadora pelo link do GitHub Pages
2. Preencha os horários de entrada e saída de cada período
3. Se você saiu para o almoço e voltou, clique em **+ Período**
4. O horário de saída sugerido aparece automaticamente — sem precisar clicar em nada

---

## Funcionalidades

- **Horário de saída em tempo real** — calcula automaticamente para jornadas de 8h, 9h e 10h
- **Múltiplos períodos no dia** — suporte a saída para almoço, banco, médico, etc.
- **Atualização automática** — a contagem regressiva se atualiza a cada minuto
- **Salva automaticamente** no navegador — ao reabrir a aba, os horários do dia continuam lá
- **Copiar resumo** — copia o resultado formatado para colar no WhatsApp
- **Botão "Agora"** — preenche o campo com o horário atual com um clique
- **Colar marcações** — cole uma sequência de horários (ex: `08:44 12:00 13:00 17:30`) e a calculadora preenche tudo
- **100% offline** — roda direto no navegador, sem servidor, sem login, sem instalar nada

---

## Regras de banco de horas

| Situação | Resultado |
|---|---|
| Trabalhou mais de 8h (até +2h) | Saldo positivo no banco do dia |
| Trabalhou exatamente 8h | Dia zerado |
| Trabalhou menos de 8h | Saldo negativo (debitado do banco) |

> O limite de crédito diário é de **+2 horas**. Excedente acima disso é desconsiderado.

---

## Tecnologia

- HTML, CSS e JavaScript puros
- Sem dependências externas
- Sem servidor — tudo roda no navegador (localStorage para salvar o estado do dia)

---

## Licença

[MIT](LICENSE) — fique à vontade para usar, adaptar e compartilhar.

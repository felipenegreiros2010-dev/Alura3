# 🎯 Projeto: Jogo de Adivinhação do Número Secreto

> Programa em que o jogador tem **até 5 tentativas** para adivinhar um número secreto definido no código, recebendo dicas de "maior" ou "menor" a cada palpite.

---

## 📑 Sumário

1. [Sobre o projeto](#-sobre-o-projeto)
2. [Regras do jogo](#-regras-do-jogo)
3. [Prompt](#-prompt)
4. [Casos de teste](#-casos-de-teste)
5. [Como usar](#-como-usar)
6. [Checklist de entrega](#-checklist-de-entrega)

---

## 📌 Sobre o projeto

Neste desafio, o programa deve permitir que o usuário adivinhe um número secreto escolhido por você (o desenvolvedor). O jogador tem até cinco tentativas e, a cada palpite, recebe uma dica indicando se o número informado foi maior ou menor que o número secreto.

Se acertar, o programa exibe **"Parabéns"** e para. Se errar todas as tentativas, informa que o jogador perdeu e mostra o número correto.

> 💡 **Dica:** realize este desafio em seu próprio projeto (repositório) para deixar sua entrega mais significativa.

---

## 📏 Regras do jogo

| # | Regra |
|---|---|
| 1 | O número secreto é definido **no código** (não se esqueça de escrevê-lo!) |
| 2 | O jogador tem no máximo **5 tentativas** |
| 3 | A cada palpite errado, o programa diz se o palpite foi **maior** ou **menor** que o número secreto (use `>` e `<`) |
| 4 | Se acertar, exibe **"Parabéns"** e **encerra** o jogo |
| 5 | Se esgotar as tentativas, informa que o jogador **perdeu** e mostra o número correto |
| 6 | Deve usar o comando **`for`** e **estruturas condicionais** (`if`, `elif`, `else`) |

---

## 🤖 Prompt

Copie o prompt abaixo e cole na IA de sua preferência. Se quiser outra linguagem, troque apenas o trecho `Python`.

````text
Atue como um professor de programação paciente e objetivo. Quero que você crie um jogo de adivinhação em Python para o seguinte desafio.

CONTEXTO
O programa deve permitir que o usuário adivinhe um número secreto definido por mim no código. O jogador tem até cinco tentativas. A cada tentativa, o programa deve dar uma dica indicando se o número informado foi maior ou menor que o número secreto.

O QUE O PROGRAMA DEVE FAZER
1. Definir o número secreto no código, em uma constante (use o número 42).
2. Pedir ao jogador que tente adivinhar o número, em até 5 tentativas.
3. A cada palpite errado, mostrar uma dica: se o palpite foi MAIOR ou MENOR que o número secreto, e quantas tentativas ainda restam.
4. Se o jogador acertar, exibir a mensagem "Parabéns" e parar imediatamente o jogo.
5. Se o jogador errar e esgotar todas as tentativas, informar que ele perdeu e mostrar o número correto.

REQUISITOS TÉCNICOS
- Use o comando for para controlar as tentativas (com range) e estruturas condicionais (if, elif, else) para dar as dicas e mostrar o resultado.
- Use os operadores > e < para comparar o palpite com o número secreto.
- Use constantes nomeadas (NUMERO_SECRETO e MAX_TENTATIVAS), sem "números mágicos" no meio do código.
- Use break para parar o jogo quando o jogador acertar, e o else do for (ou uma variável de controle) para tratar o caso de derrota.
- Valide a entrada: se o jogador digitar algo que não seja um número inteiro, mostre um aviso e peça novamente, sem gastar a tentativa.
- Use nomes de variáveis claros, em português, e comentários curtos explicando as partes principais.
- Use apenas a biblioteca padrão do Python.

FORMATO DA RESPOSTA
1. O código completo em um único bloco.
2. Uma explicação curta, em linguagem simples, de como o programa funciona (principalmente o for e o break).
3. Uma tabela com pelo menos 5 casos de teste (sequência de palpites e saída esperada), incluindo acerto na primeira tentativa, acerto na última e derrota.
4. Sugestões de como eu poderia melhorar o jogo depois (por exemplo: número sorteado aleatoriamente, níveis de dificuldade, placar).

IMPORTANTE
Explique o código de um jeito que um estudante iniciante consiga entender e reproduzir. Não use dados pessoais em nenhum exemplo.
````

---

## 🧪 Casos de teste

Considerando o número secreto **42** e **5 tentativas**:

| Palpites do jogador | Resultado esperado |
|---|---|
| 42 | "Parabéns" na 1ª tentativa e o jogo para |
| 10, 80, 42 | Dica "menor", dica "maior", depois "Parabéns" na 3ª tentativa |
| 1, 99, 50, 30, 42 | Acerta na última (5ª) tentativa: "Parabéns" |
| 10, 20, 30, 35, 40 | Todas "menor"; perde e mostra que o número era 42 |
| 90, 70, 60, 50, 45 | Todas "maior"; perde e mostra que o número era 42 |
| abc, 42 | Aviso de entrada inválida (sem gastar tentativa), depois "Parabéns" |

---

## ▶️ Como usar

1. Cole o prompt na IA e gere o código.
2. Salve o código em um arquivo, por exemplo `adivinhacao.py`.
3. Execute no terminal:

```bash
python adivinhacao.py
```

4. Teste com os casos da tabela e confira as dicas e mensagens.
5. **Revise o código gerado**: leia, entenda e ajuste o que for necessário. A IA pode errar e não deve ser a única fonte.

---

## ✅ Checklist de entrega

- [ ] Criei o projeto em um repositório próprio
- [ ] Usei o prompt e gerei o código
- [ ] Li e entendi o código antes de entregar
- [ ] O número secreto está escrito no código
- [ ] O jogador tem no máximo 5 tentativas
- [ ] Usei o comando `for` para controlar as tentativas
- [ ] As dicas "maior" e "menor" funcionam com `>` e `<`
- [ ] Ao acertar, aparece "Parabéns" e o jogo para
- [ ] Ao perder, aparece a mensagem de derrota com o número correto
- [ ] Testei todos os casos da tabela
- [ ] Incluí este README no repositório

---

<sub>Projeto do desafio "Jogo de adivinhação". Bons estudos! 🚀</sub>

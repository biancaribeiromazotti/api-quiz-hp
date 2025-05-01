# APP

Harry Potter Quiz Game

## RFs (Requisitos funcionais)

- [ ] O sistema deve exibir uma pergunta aleatória sobre o universo de Harry Potter.
- [ ] O sistema deve retornar a resposta correta junto com a pergunta (útil para verificação ou jogo solo).
- [ ] O sistema deve fornecer alternativas (opcional no MVP, mas recomendável).
- [ ] O sistema deve registrar a resposta do jogador e informar se ela está correta ou incorreta.
- [ ] O sistema deve exibir o placar atual do jogador.
- [ ] O sistema deve permitir o início de um novo jogo (reset de pontos e perguntas).
- [ ] O sistema deve consumir dados da API pública de Harry Potter para gerar as perguntas.
- [ ] O sistema deve evitar repetir perguntas já feitas em uma mesma partida.

## RNs (Regras de negócio)

- [ ] Cada pergunta respondida corretamente adiciona +1 ponto ao jogador.
- [ ] Cada pergunta errada não adiciona pontos.
- [ ] Uma rodada contém até 10 perguntas.
- [ ] As perguntas devem ser baseadas em dados reais vindos da API de personagens.
- [ ] As alternativas devem incluir 1 resposta correta e 3 erradas, escolhidas aleatoriamente.
- [ ] O jogador não pode repetir perguntas em uma mesma rodada.
- [ ] Ao final da rodada, o sistema deve exibir o total de acertos e erros.



## RNFs (Requisitos não-funcionais)

- [ ] A senha do usuário precisa estar criptografada;
- [ ] Os dados da aplicação precisam estar persistidos em um banco de dados PostgreSQL;
- [ ] O usuário deve ser identificado por um JWT (JASON Web Token)
# RPG-DU Skill – Diretrizes de Design Universal para jogos educacionais RPG

Agent Skill com as **88 diretrizes de Design Universal para jogos educacionais digitais do tipo RPG**, organizadas em 3 categorias de elementos do jogo (Estética, Narrativa e Mecânica), para usar com assistentes de IA compatíveis com o padrão aberto [Agent Skills](https://agentskills.io/).

A ideia central: **jogos educacionais devem ser projetados desde o início para pessoas com e sem deficiência**, em vez de receber acessibilidade como adaptação posterior.

## De onde vêm as diretrizes

- **1 a 30 – Literatura:** revisão sistemática da literatura sobre jogos educacionais RPG e Design Universal.
- **31 a 88 – Estudo de campo:** desenvolvimento do jogo *Expedição Antártica*, testado com 10 usuários (pessoas sem deficiência e pessoas com deficiência auditiva, visual e cognitiva).

Cada diretriz traz título, nome original, descrição com exemplo, origem e fonte. As diretrizes do estudo de campo trazem também a necessidade do usuário, o critério WCAG relacionado e os princípios do Design Universal atendidos.

## O que a skill faz

- **Consulta:** “O que diz a diretriz 45 de Design Universal para jogos RPG?”
- **Auditoria:** avalia um jogo ou protótipo diretriz por diretriz (atende / não atende / não se aplica).
- **Requisitos:** transforma diretrizes em requisitos de um jogo, com critério de aceitação.
- **Ensino:** explica cada categoria com exemplos práticos.

## Conteúdo

```
rpg-du-diretrizes/
├── SKILL.md                  # instruções, categorias, princípios e índice
└── references/
    └── diretrizes.md         # texto completo das 88 diretrizes
```

## Como instalar

A skill é a pasta [`rpg-du-diretrizes/`](rpg-du-diretrizes/).

- **Assistentes com tela de configurações:** compacte a pasta `rpg-du-diretrizes` em um arquivo `.zip` e envie na seção de Skills.
- **Ferramentas que leem skills de uma pasta:** copie a pasta `rpg-du-diretrizes` para o diretório de skills indicado na documentação da ferramenta.

Depois de instalada, basta pedir em linguagem natural, por exemplo: *“Avalie este jogo com as diretrizes de Design Universal para RPG.”*

## Fonte e créditos

As diretrizes seguem o Capítulo 5 (Tabelas 5.2 e 5.3) da dissertação, com redação revisada:

> CUNHA, Francinete Furtado da. **Diretrizes para o design universal de jogos educacionais digitais do tipo Role Play Games (RPG)**. 2022. 128 f. Dissertação (Mestrado em Ciência da Computação) – Universidade Federal do ABC, Santo André, 2022. Orientadora: Juliana Braga.

Desenvolvido no grupo de pesquisa **INTERA** da **Universidade Federal do ABC (UFABC)**.

A indicação “Sugestão WCAG 2.2” **não faz parte do texto original** da dissertação: é uma sugestão de atualização dos critérios, que citavam a WCAG 2.0.

## Como citar

Use o botão *Cite this repository* do GitHub (arquivo [`CITATION.cff`](CITATION.cff)) e cite também a dissertação acima.

## Licença

Conteúdo licenciado sob [Creative Commons Atribuição 4.0 Internacional (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.pt-br): você pode usar, adaptar e redistribuir, inclusive comercialmente, desde que cite a fonte.

## Contribuições

Sugestões e correções são bem-vindas por meio de *issues* ou *pull requests*.

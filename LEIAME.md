# Protocolo de Gestão Curricular

Idealização e coordenação: João Marcos Falcão Perim, professor da rede estadual do Espírito Santo.
Desenvolvido com apoio de inteligência artificial (Claude, da Anthropic). Ferramenta independente, sem vínculo oficial com a SEDU-ES.

## Arquivos

- `index.html`: a página inteira (painel, dados do currículo e montagem de atividades).
- `banco_3tri.json`: planos de aula e questões do 3º trimestre. Precisa ficar na mesma pasta do `index.html`.

## Como atualizar o banco

Substitua o `banco_3tri.json` por uma versão nova com o mesmo formato (`{"planos": [...], "questoes": [...]}`) e publique de novo.

## O que muda fora do claude.ai

- Funciona: painel, materiais prontos, montagem de atividade, download em Word e resumo para o Seges.
- Não aparece: a geração de atividades com o Claude.
- Não funciona: a marcação de revisão compartilhada (precisaria de um banco de dados próprio).

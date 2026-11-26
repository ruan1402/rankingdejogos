# Ranking dos jogos favoritos

Um ranking pessoal com os seus jogos favoritos: pódio com os 3 primeiros, lista completa e um formulário para adicionar novos jogos. Interface em português, tema escuro.

Desenhado no Claude Design.

## O que ele faz

- **Pódio** com o top 3 (ouro, prata e bronze), com capa, nome e nota.
- **Lista completa** com as demais posições, cada uma com barra de nota.
- **Mover jogos:** setas para subir e descer a posição, no pódio e na lista.
- **Remover** um jogo do ranking.
- **Adicionar jogo** com nome, gênero, plataforma, nota (0 a 10), posição, capa e o motivo de ser favorito.
- **Resumo no topo:** quantidade de jogos e nota média.
- Sem imagem de capa, o jogo ganha uma capa colorida com as iniciais.
- O ranking tem no máximo 10 jogos.

## Arquivos

| Arquivo | Para que serve |
| --- | --- |
| `Main.dc.html` | A tela do ranking (fonte do Claude Design) |
| `canvas.json` | Índice da tela: tamanho, título e posição |

## Como usar

O `Main.dc.html` usa o formato do Claude Design e depende de um `support.js` que o próprio Claude fornece. Por isso, abrir o arquivo direto no navegador não funciona.

Para editar ou rodar:

1. Abra o ranking no Claude Design.
2. Use **Share → Export** para baixar uma versão para uso fora do Claude.

## Fontes

- Bricolage Grotesque (títulos) e DM Sans (texto), pelo Google Fonts.

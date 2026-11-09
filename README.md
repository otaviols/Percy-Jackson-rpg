# RPG Mitos — Sistema de RPG inspirado em Percy Jackson

> Sistema caseiro de RPG de mesa inspirado nas obras de Rick Riordan (*Percy Jackson e os Olimpianos* e *Heróis do Olimpo*). Os jogadores interpretam **semideuses** — filhos de divindades gregas ou romanas — em um mundo moderno onde a mitologia ainda existe.

## Arquivos do sistema

| Arquivo | Conteúdo |
|---|---|
| **[Livro do Jogador](livro_do_jogador.md)** | Criação de personagem, atributos, deuses (tabela resumida), Sangue Plural, **estilos de combate**, progressão, **condições**, combate, **morte (Teste das Moiras)**, recuperação, regras gerais |
| **[Livro dos Poderes](livro_dos_poderes.md)** | Listas completas de habilidades, magias e truques de **35 ancestrais** (Linhagem, Bênção, Romanos, Deuses Menores) |
| **[Livro do Mestre](livro_do_mestre.md)** | Princípios de mestre, **bestiário com 56 monstros** (Titãs, Gigantes anti-deus, antagonistas humanos e variantes inclusos), suvenires, **60 itens mágicos**, **relíquias e dádivas divinas**, **construção de encontros**, tabelas de críticos, profecia e **arcos**, **economia/loja**, **o Acampamento e downtime** |
| **[Ficha de Personagem](ficha_de_personagem.md)** | Modelo preenchível (1 página), com as fórmulas de cada campo derivado |
| **[Aventura-exemplo](campanhas/aventura_exemplo.md)** | "Cheiro de Enxofre" — aventura introdutória nv 1-3 pronta para rodar |
| **[Campanha: A Serra sem Névoa](campanhas/a_serra_sem_nevoa.md)** | Arco médio na Chapada Diamantina (BA) para 5-7 heróis, nv 3-7, 8-10 sessões, com profecia central |

## O que este sistema é

- **Mundo moderno + mitologia escondida.** Heróis vão à escola, têm trabalho, e no fim de semana enfrentam Fúrias no shopping.
- **Linhagem divina importa.** Seu pai ou mãe divino define suas forças, fraquezas e estilo de jogo.
- **35 ancestrais únicos** com mecânicas distintas (Olimpianos gregos e romanos, Bênção de deusas virgens, Deuses menores como Hécate, Hipnos, Tique).
- **Combate tático com elementos sobrenaturais.** d20 + atributo + perícia para testes; magias com PM; **Ímpeto** como recurso especial para filhos de Ares/Marte/Belona.
- **Profecia e destino** guiando campanhas grandes.

## Como começar a jogar

1. **Mestre lê os 3 livros** (priorizando o Livro do Mestre).
2. **Jogadores leem o Livro do Jogador** (seções 1-7 são essenciais).
3. **Mestre define o ancestral** de cada PJ ou deixa rolar (no canon, semideuses descobrem quem é o pai/mãe divino aos poucos).
4. **Sessão zero:** criem personagens juntos, alinhem o tom (humor + perigo) e definam profecia central da campanha.
5. **Mestre planeja primeira aventura.** Use monstros Tier 1 (Cão Infernal, Harpia, Cabras Carnívoras) para personagens nv 1-5.

## Estado do sistema

🏛️ **Versão 1.0.0** — primeira edição completa, limpa e jogável do sistema.

✅ **Sistema completo e jogável.** Todas as regras essenciais escritas e testadas no papel.

🔧 **Próximas melhorias possíveis (não bloqueantes):**
- Mais itens mágicos
- Bestiário expandido (mais variantes de cada monstro)
- Tabela de construção de encontros (orçamento de XP por número de PJs)
- Mais aventuras-exemplo e relíquias de campanha

## Conversão para outros formatos

Os arquivos estão em **Markdown** (`.md`). Para converter para PDF, DOCX, HTML ou outros formatos, ver instruções no fim deste arquivo.

---

## Como converter os arquivos `.md` para PDF/DOCX/HTML

### Opção 1 — Typora (recomendado para começar)
Editor visual de Markdown que mostra o resultado já renderizado e exporta para PDF/HTML/DOCX/EPUB.

- **Download:** https://typora.io (US$ 14,99, multiplataforma)
- **Como usar:** abre o `.md`, vê o resultado bonito, exporta com `Arquivo → Exportar → PDF` (ou HTML/DOCX).
- **Prós:** mais fácil, sem comando, visual.
- **Contras:** pago.

### Opção 2 — VSCode + extensão Markdown PDF (grátis)
- Instale o **Visual Studio Code** (grátis): https://code.visualstudio.com
- Instale a extensão **Markdown PDF** (busque no marketplace).
- Abra o `.md`, clique com botão direito → "Markdown PDF: Export (pdf)".
- **Prós:** grátis, multiplataforma, leve.
- **Contras:** PDF padrão (pode customizar com CSS se quiser).

### Opção 3 — Pandoc (para usuário técnico, mais robusto)
Ferramenta de linha de comando que converte entre **qualquer** formato.

- **Download:** https://pandoc.org/installing.html
- **Comando para PDF:**
  ```
  pandoc livro_do_jogador.md -o livro_do_jogador.pdf
  ```
- **Comando para DOCX:**
  ```
  pandoc livro_do_jogador.md -o livro_do_jogador.docx
  ```
- **Comando para HTML standalone:**
  ```
  pandoc livro_do_jogador.md -s -o livro_do_jogador.html
  ```
- **Prós:** grátis, robusto, suporta praticamente qualquer formato, scriptável.
- **Contras:** linha de comando (precisa abrir terminal); para PDF, precisa de LaTeX instalado.

### Opção 4 — GitHub / GitLab (visualização online gratuita)
Se quiser que outros leiam sem precisar instalar nada:
- Crie uma conta gratuita no GitHub.
- Faça upload dos arquivos `.md` em um repositório público (ou privado se preferir).
- GitHub renderiza Markdown automaticamente: qualquer pessoa com o link consegue ler bonito no navegador.
- **Prós:** zero instalação para quem vai ler, links compartilháveis, sumários funcionam.
- **Contras:** precisa ter conta GitHub para você gerenciar.

### Opção 5 — Lendo direto pelo navegador (zero esforço)
Para mostrar a alguém só por um momento:
- Abra **https://markdown.land** ou **https://stackedit.io** no navegador.
- Cole o conteúdo do `.md`.
- A pessoa vê o resultado renderizado direto na tela.
- **Prós:** zero instalação.
- **Contras:** copiar/colar manual, não fica salvo.

### Minha recomendação
- **Para você usar regularmente:** **VSCode + Markdown PDF** (grátis, multiplataforma, simples).
- **Para compartilhar com pessoas que não vão instalar nada:** **GitHub público** (link fácil de mandar) ou exporta para PDF e manda o arquivo.
- **Para versões finais "publicadas":** **Typora** (mais bonito) ou **Pandoc** (mais customizável).

Quando o sistema estiver maduro, vale também pensar em **gerar 1 PDF único** juntando os 3 livros + capa.

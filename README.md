## Como publicar

1. Crie um repositório no GitHub, por exemplo `montovoni.github.io` (esse nome específico publica direto na raiz do seu usuário) ou qualquer outro nome, como `portfolio`.
2. Suba estes 3 arquivos (`index.html`, `style.css`, `script.js`) para a raiz do repositório.
3. Em alguns minutos o site fica no ar em `https://SEU-USUARIO.github.io`.

## Estrutura

- `index.html` - conteúdo e seções (Sobre, Stack, Experiência, Portfólio, Contato)
- `processos.html` - links dos processos fechados no Redmine, agrupados por projeto e, na Escrita Fiscal, por módulo
- `style.css` - tema escuro estilo terminal, acento verde-água
- `script.js` - menu mobile, animação de revelação ao rolar, data dinâmica

## Editar conteúdo

Os textos e links (e-mail, LinkedIn, GitHub) estão diretamente no `index.html`, dentro da seção `#contato` e nos cards de `#stack`/`#experiencia` - não há dados externos ou build step.

Os números da seção `#portfolio` (totais, percentuais por área e linha do tempo) foram levantados do histórico de tarefas e apontamentos de horas. Para atualizar, troque os valores no HTML; a largura de cada barra é o `--w` (percentual da área dividido pelo maior percentual).

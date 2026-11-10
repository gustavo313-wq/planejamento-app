# Nossa casa — lista de essenciais

Checklist para morar a dois: marque o que já comprou, edite quantidades, valores e observações, e adicione ou remova itens e categorias.

Site estático em um único arquivo (`index.html`), sem dependências nem etapa de build.

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (por exemplo, `lista-essenciais`).
2. Envie o `index.html` e este `README.md` para a branch `main`.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, selecione `main` e a pasta `/ (root)`, e clique em **Save**.
5. Em alguns minutos o site estará em `https://SEU-USUARIO.github.io/lista-essenciais/`.

## Como os dados são salvos

- Tudo fica no `localStorage` do navegador. Não há servidor nem login.
- Cada aparelho e navegador tem a sua própria cópia.
- Para passar a lista de um aparelho para outro, ou compartilhar com seu par, use **Exportar** (gera um `.json`) e **Importar**.
- Limpar os dados do navegador apaga a lista. Exporte de vez em quando para ter um backup.

## Recursos

- Checkbox de comprado, com progresso geral e por categoria
- Quantidade, item, valor unitário e observações editáveis
- Totais: estimado, já comprado e quanto falta
- Adicionar e remover itens e categorias, com opção de desfazer
- Busca e filtros (todos, pendentes, comprados)
- Exportar, importar, imprimir e restaurar a lista original
- Tema claro e escuro automático, e layout adaptado para celular

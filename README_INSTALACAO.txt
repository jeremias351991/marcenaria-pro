MARCENARIA PRO - PWA v2026.06.06.10

Correção ampla:
- Safe bootstrap no início do sistema.
- Garante verificarVersaoOnline().
- Garante renderizarFerragens().
- Garante renderizarFitas(), renderizarMateriais(), renderizarDicionario(), renderizarProjetos().
- Garante preencherSelectsProjeto(), inicializarBancoPadrao(), migrarIds().
- Não apaga dados.

Para atualizar no GitHub Pages:
1. Substitua index.html.
2. Substitua version.json.
3. Substitua service-worker.js.
4. Aguarde o GitHub Pages publicar.
5. Teste com ?v=10.
6. Se persistir erro antigo, limpe os dados/cache do site no Chrome.

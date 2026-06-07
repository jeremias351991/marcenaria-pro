MARCENARIA PRO - PWA v2026.06.06.11

Correção:
- encontrarMaterialMapeado() declarado no início do sistema.
- Aliases adicionados: buscarMaterialMapeado() e obterMaterialMapeado().
- A função consulta o dicionário de mapeamento e, se necessário, busca material por aproximação de nome e espessura.
- Não apaga dados.

Para atualizar no GitHub Pages:
1. Substitua index.html.
2. Substitua version.json.
3. Substitua service-worker.js.
4. Aguarde o GitHub Pages publicar.
5. Teste com ?v=11.
6. Se persistir erro antigo, limpe os dados/cache do site no Chrome.

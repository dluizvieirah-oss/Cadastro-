# Abordagens · GCM Matão

App offline (PWA) para registro de pessoas abordadas. Os dados ficam apenas no aparelho (IndexedDB).

## Publicar no GitHub Pages
1. Envie estes arquivos para a raiz do repositório.
2. Em Settings > Pages, escolha a branch `main` e a pasta `/ (root)`.
3. Abra o link HTTPS uma vez com internet e use "Adicionar à tela inicial".

## Arquivos
- `index.html`: aplicativo completo
- `manifest.json`: instalação como app
- `sw.js`: cache para funcionar offline (mude a versão em `C` a cada atualização)

Os dados não sincronizam entre aparelhos. Use o backup JSON para transferir ou guardar.

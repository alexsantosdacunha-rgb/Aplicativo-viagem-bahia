# Meu Guia Porto Seguro 2027

PWA simples para Android com roteiro, hospedagens, destinos, restaurantes e controle de despesas.

## Como publicar gratuitamente para instalar no Android

A instalação como PWA exige HTTPS. Uma opção simples é o GitHub Pages:

1. Crie uma conta em https://github.com/ (se ainda não tiver).
2. Crie um repositório público chamado `meu-guia-porto-seguro-2027`.
3. Envie todos os arquivos desta pasta para a raiz do repositório.
4. No GitHub, abra **Settings → Pages**.
5. Em **Build and deployment**, selecione **Deploy from a branch**, escolha `main` e `/ (root)`, e salve.
6. Aguarde a publicação. O endereço será parecido com `https://SEU-USUARIO.github.io/meu-guia-porto-seguro-2027/`.
7. Abra o endereço no Chrome do Android. No menu ⋮, escolha **Instalar app** ou **Adicionar à tela inicial**.

## Dados e privacidade

- Despesas são guardadas no `localStorage` do navegador/aparelho.
- Use **Exportar CSV** para fazer cópia dos gastos.
- Limpar os dados do site/navegador pode apagar o histórico.
- Os dados não sincronizam automaticamente entre aparelhos.
- O roteiro e as estimativas são editáveis no código-fonte.

## Observações

- Os valores são estimativas para duas pessoas, não cotações garantidas.
- Confirme tarifas, horários, funcionamento, marés, refeições e comodidades diretamente com os fornecedores.
- O mapa abre pesquisas no Google Maps; internet é necessária para consultar rotas.
- As fotos de capa dependem de conexão com a internet.

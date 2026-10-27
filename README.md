# Bolão do Pix — protótipo inicial

Página estática para demonstrar cadastro de nome, WhatsApp, jogo/evento e palpite, com valor previsto de R$ 5,00.

## Publicar no GitHub Pages
1. Abra **Settings → Pages**.
2. Em **Build and deployment**, selecione **Deploy from a branch**.
3. Escolha a branch **main** e a pasta **/(root)** e salve.

Depois de publicado, o endereço esperado é: https://diascliente95-wq.github.io/Jogo-do-pix/

## Limitações importantes
- Esta versão é apenas um protótipo: os cadastros são guardados no navegador local com localStorage. Não sincronizam para outros visitantes.
- O painel de administrador tem uma senha de demonstração no código (**1234**) e não é seguro. Não use com dados reais.
- Não há cobrança, QR Code Pix nem confirmação automática de pagamento.
- Antes de abrir inscrições com dinheiro/prêmio, confirme a legalidade do formato e publique regras claras. Não trate o protótipo como sistema de apostas pronto para operação.
- Para uma versão real é preciso backend seguro, autenticação administrativa, banco de dados, proteção de dados pessoais e integração de pagamentos com confirmação no servidor.

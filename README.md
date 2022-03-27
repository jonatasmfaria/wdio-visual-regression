# wdio-visual-regression

Projeto de teste de regressão visual conectado com o applitools.

## Obter o código do site da applitools

- Acesse o site da [applitools](https://auth.applitools.com/users/login) e faça login (caso não tenha, cadastre-se é gratis);
- Ao logar, clique no ícone do seu usuário localizado no canto superior direito da tela >> Minha chave de API e copie essa chave;
- No código, informe onde está escrito "Informar código API do applitools" a chave copiada do site da applitools.
Exemplo:

eyes.setApiKey("Informar código API do applitools") >> eyes.setApiKey("U00000PxssdasdyWj000SVcOj000QK10IunadadafBGcn7FZ00Y00")

## Execução dos testes

`npm run wdio`

Após a execução, acesse o site da applitools e veja as execuções.

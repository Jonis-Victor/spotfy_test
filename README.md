# Clonagem da Página do Spotify

Este projeto foi criado durante a Imersão Alura. O objetivo principal é clonar a interface da página inicial do Spotify usando HTML, CSS e JavaScript.

## Recursos

- **Mensagem de Saudação**: O script.js inclui uma função que exibe uma mensagem de saudação ("Bom dia", "Boa tarde" ou "Boa noite") dependendo da hora do dia.

- **Grid Inteligente**: O script.js também inclui uma função que ajusta o número de colunas em uma grade com base na largura do contêiner. Isso permite que a grade seja responsiva e se adapte a diferentes tamanhos de tela.

## Como executar

1. Clone este repositório usando:
```bash
  git clone https://github.com/Jonis-Victor/spotfy_test.git
```
3. Navegue até o diretório clonado usando:
```bash
  cd spotify-test
```
5. Instale a versão 0.17.4 do Json Server:
```bash
  npm install -g json-server@0.17.4
```
3. Inicie o JsonServer para poder consumir a API dos artistas:
```bash
  json-server --watch ./api-artists/artists.json
```
4. Abra o arquivo `index.html` em seu navegador ou utilizando a extensão Live Server do Visual Studio Code.

## Contribuições

Contribuições são sempre bem-vindas! 

## Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

Contador de Palavras em Parágrafos 📄✨

Este projeto em JavaScript 🟨 e Node.js 🟩 lê um arquivo de texto e retorna a contagem de palavras repetidas em cada parágrafo. Ele foi desenvolvido para facilitar a análise de textos, identificando palavras que se repetem dentro dos parágrafos.

📁 Estrutura do Projeto
arquivos/: Diretório onde os textos a serem processados são inseridos.
resultados/: Diretório onde os resultados são salvos.
src/: Contém o código-fonte da aplicação.
erros/: Diretório que contém as funções para tratamento de erros.
funcoesErros.js: Arquivo responsável por tratar os erros da aplicação.
cli.js: Arquivo principal que gerencia as entradas do usuário e processa os arquivos de texto.
helpers.js: Contém funções auxiliares para formatar a saída dos resultados.
index.js: Contém a lógica principal para contagem de palavras.

📋 Pré-requisitos
Node.js instalado na máquina.
Gerenciador de pacotes npm.

:rocket: Tecnologias
<div>
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
</div>

📚 Bibliotecas Utilizadas
fs: Módulo do Node.js para manipulação de arquivos.
path: Módulo do Node.js para manipulação de caminhos de arquivos e diretórios.
commander: Biblioteca para criação de interfaces de linha de comando.
chalk: Biblioteca para estilizar a saída no terminal com cores.

🚀 Instalação
Clone o repositório:
git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/pedrohtfragoso/programa-conta-palavras)

Navegue até o diretório do projeto:
cd programa-conta-palavras

Instale as dependências:
npm install

🛠️ Uso
Para utilizar o contador de palavras, execute o comando abaixo, substituindo <caminho-do-texto> pelo caminho do arquivo de texto a ser processado e <caminho-do-destino> pelo diretório onde o resultado será salvo:

```sh
node src/cli.js -t <caminho-do-texto> -d <caminho-do-destino>
```
Exemplo:

```sh
node src/cli.js -t arquivos/meuTexto.txt -d resultados/
```

🤝 Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

# laravel-nova-1.2.0-pr-BR
Tradução do Laravel Nova na versão 1.2.0 para o Português Brasileiro

## Instalação
1. Clonar este repositório na pasta `resources/lang/vendor/nova` do seu projeto
  ```shell
  $ cd resources/lang/nova
  $ git clone https://github.com/thiagovictorino/laravel-nova-1.2.0-pr-BR
  ```
   Você pode remover o diretório .git caso deseje incluir e versionar os arquivos deste projeto no seu repositório.

  ```shell
  $ rm -r .git/
  ```
2. Configurar o Framework para utilizar 'pt-BR' como linguagem padrão
  ```
  // Altere Linha 81 do arquivo config/app.php para:
  'locale' => 'pt-BR',
  ```

# laravel-nova-1.2.0-pt-BR
Tradução do Laravel Nova na versão 1.2.0 para o Português Brasileiro

- Sugestões de melhorias são bem vindas.
- *A tradução ainda não está completa*, vou fazendo aos poucos ou aceito ajuda

## Instalação
1. Fazer o download dos arquivos desse repositório e move-los para a pasta `resources/lang/vendor/nova` do seu projeto. Um exemplo de como fazer isso é:
  ```shell
  $ cd seu_projeto/ 
  $ wget https://github.com/thiagovictorino/laravel-nova-1.2.0-pt-BR/archive/master.zip && 
  	unzip master.zip -d resources/lang/vendor/nova/ && 
  	cp resources/lang/vendor/nova/laravel-nova-1.2.0-pt-BR-master/pt-BR.json resources/lang/vendor/nova/ && 
  	cp -R resources/lang/vendor/nova/laravel-nova-1.2.0-pt-BR-master/pt-BR  resources/lang/vendor/nova/ && 
  	rm -R resources/lang/vendor/nova/laravel-nova-1.2.0-pt-BR-master &&
  	rm master.zip
  ```

  
2. Configurar o Framework para utilizar 'pt-BR' como linguagem padrão
  ```
  // Altere seguinte linha do arquivo config/app.php para:
  'locale' => 'pt-BR',
  ```

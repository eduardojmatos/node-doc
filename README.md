NodeDoc
=======

Translation of Node.js Documentation for the Portuguese language.

### Informações

A Tradução da Documentação está em andamento e você poderar ver como está o status e também contribuir para a tradução.

### Status

Traduzidos:

    * _toc.markdown
    * addons.markdown
    * assert.markdown
    * console.markdown
    * documentation.markdown
    * synopsis.markdown
    * string_decoder.markdown
    * querystring.markdown
    * os.markdown
    * punycode.markdown

Em Processo:

    * fs.markdown
    * http.markdown
    * buffer.markdown

### Como Contribuir

Para contribuir você precisa seguir os seguintes passos.

Passos:

    1. Fazer um Fork do Repositório.
    2. Clonar o Repositório
    3. Ler os Padrões do Projeto
    4. Traduzir
    5. Testar a Tradução
    6. Enviar um Pull Request

### Padrões do Projeto

Para organizar e melhorar a qualidade do projeto vai ser preciso seguir alguns padrões.

Commits:

Nas mensagens dos seus commits vamos seguir algus padrões como:

-- Enviando Traduções

	git commit -m "Translate: filename.markdown"

Para mais de um arquivo:

	git commit -m "Translate: filename.markdown, filename2.markdown and filename3.markdown"

Atenção: Para mais de um arquivo sempre o último tem o `and` e o restanto do começo separado por vírgula com espaços entre as vírgulas como no exemplo.

-- Enviando Correções

Caso você tenha errado alguma coisa no arquivo ou não saiu como planejado depois de testar e ler no GitHub Você pode corigir o arquivo e fazer um novo commit seguindo o exemplo:

	git commit -m "FixError: filename.markdown"

	git commit -m "FixError: filename.markdown, filename2.markdown and filename3.markdown"

O mesmo segue as regras de cima só que mudando a palavra para `FixError`.


### Enviando Pull Request

Depois de testar, ler e revisar sua tradução, é hora de fazer um Pull Request. Após fazer o Pull Request, sua tradução será analisada e se estiver tudo certo será aceita e seu nome será referenciado como colaborador do projeto na Documentação. Você ajudará muitas pessoas na comunidade Node.js da lingua Portuguesa.

Depois de finalizada a tradução completa, será compilado os arquivos e a Documentação estará online em: [Node Doc](http://chrisenytc.github.io/docs/nodejs)

A documentação compilada em `.html` e `.json` também estará disponível em `/compiled` para que todas as pessoas também possam hospedar em qualquer lugar sempre referenciando o projeto e seus colaboradores que tiveram todo o trabalho para ajudar a comunidade Node. :)

Após terminada a tradução completa também será mostrado exemplos de como compilar os `.markdown` usados na documentação.

## Conclusão

Seguindo esses passos você poderar contribuir com o projeto e ajudar milhares de pessoas que irão usar as traduções.

Você também pode ver ou contribuir com outros projetos de traduções nos links abaixo:

* [Docs Lists](http://chrisenytc.github.io/docs/)
* [Chris Blog](http://chris.enytc.com)

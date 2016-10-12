Guia de desenvolvimento do  Pet Booking.
=========================================
Essa é uma versão adaptada do guia [Thoughtbot](https://github.com/thoughtbot/guides)


Principais mandamentos:
------------------------
1. Ao criar uma tela, se possível usarás o padrão do Rails ao invés de fazer no Angular.
2. Ao atualizar uma tela em angular, se não consumir muito tempo, refatorarás para uma Rails.
3. Ao testar, seguirás a stack padrão Rails: RSpec, FactoryGirl, ShouldaMatchers.
4. Testarás uma feature nova e escreverás teste de uma feature já existente que você esteja atualizando.
5. Extrairás as lógicas de negócio em objetos de serviço.
6. Submeterás seu código através de um pull request para code review.
7. Rodarás o rubocop e rails_best_pratices em seus arquivos novos para garantir que seu código esteja dentro das principais guides da comunidade.
8. Ao escrever os testes com rspec, veja se está usando boas práticas, um bom guia ( em pt-br) é o [Betterspecs](http://betterspecs.org/br/)


Guides
======

Guides for getting things done, programming well, and programming in style.

* [Best Practices](./best-practices)
* [Code Review](./code-review)
* [How to](./how-to)
* [Protocol](./protocol)
  * [Communication](./protocol/communication)
  * [Git](./protocol/git)
  * [iOS](./protocol/ios)
  * [Open Source](./protocol/open-source)
  * [Product Review](./protocol/product-review)
  * [Rails](./protocol/rails)
* [Security](./security)
* [Style](./style)

High level guidelines:

* Be consistent.
* Don't rewrite existing code to follow this guide.
* Don't violate a guideline without a good reason.
* A reason is good when you can convince a teammate.

A note on the language:

* "Avoid" means don't do it unless you have good reason.
* "Don't" means there's never a good reason.
* "Prefer" indicates a better option and its alternative to watch out for.
* "Use" is a positive instruction.

Contributing
------------

Please read the [contribution guidelines] before submitting a pull request.

In particular: **if you have commit access, please don't merge changes without
waiting a week for everybody to leave feedback**.

[contribution guidelines]: /CONTRIBUTING.md

Credits
-------

Thank you, [contributors](https://github.com/thoughtbot/guides/graphs/contributors)!

![thoughtbot](http://thoughtbot.com/images/tm/logo.png)

Guides is maintained by [thoughtbot, inc](http://thoughtbot.com/community).

License
-------

Guides is © 2014 thoughtbot, inc. It is distributed under the [Creative Commons
Attribution License](http://creativecommons.org/licenses/by/3.0/).

The names and logos for thoughtbot are trademarks of thoughtbot, inc.

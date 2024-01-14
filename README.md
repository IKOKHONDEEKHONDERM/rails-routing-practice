Rails Routing Practice
======================

This simple app lets students learning Rails get some practice
understanding how routes from `config/routes.rb` are parsed.

The learner enters some `config/routes.rb`-compliant route descriptions,
and can then enter various routes (method + URI) to see how they would
be recognized and how `params` would be parsed from them.

Everything here is [CC-BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode).

** Run your code and click this link ==> https://rails-routing-practice.saasbook.info/
and Test your website by putting this text in a rectangular box to check the type of yhe text.
** resources :brands, only: [:index, :show] 
resources :products, only: [:index, :show]
resource :basket, only: [:show, :update, :destroy]

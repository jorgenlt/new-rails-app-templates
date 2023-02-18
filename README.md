# New Ruby on Rails app templates
Originally from [lewagon/rails-templates](https://github.com/lewagon/rails-templates)

</br>

Templates for Ruby on Rails 7.

See [Rails Templates](http://guides.rubyonrails.org/rails_application_templates.html).

</br>

## Minimal

Get a minimal rails app ready to be deployed on Heroku with Bootstrap, Simple form and debugging gems.
- postgreSQL
- webpack

```bash
rails new \
  -d postgresql \
  -j webpack \
  -m https://raw.githubusercontent.com/jorgenlt/new-rails-app-templates/master/minimal.rb \
  your_new_rails_app_name
```

## Devise

Same as minimal **plus** a [Devise](https://github.com/heartcombo/devise) install with a generated `User` model.
- postgreSQL
- webpack

```bash
rails new \
  -d postgresql \
  -j webpack \
  -m https://raw.githubusercontent.com/jorgenlt/new-rails-app-templates/master/devise.rb \
  your_new_rails_app_name
```

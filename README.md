SpreeMailView
=============

Use mail_view (https://github.com/basecamp/mail_view) from Basecamp to test your Spree e-mails.

Installation
------------

Add mail_view and spree_mail_view to your Gemfile:

```ruby
group :development do
  gem 'spree_mail_view', :github => 'reinaris/spree_mail_view'
end
```

run bundle.

After that, visit:
http://localhost/mail_view

You can test the following e-mails in your browser without resending them (just hit refresh):
- Order confirm email
- Order cancel email
- Shipment shipped email
- Forgot password email

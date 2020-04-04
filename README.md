# Peatio::NDC

Peatio ndc plugin for nPro [peatio] stack

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'peatio-ndc'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install peatio-ndc

## Usage

For Peatio CPUchain plugin integration you need to do the following steps:

### Image Build.

1. Add peatio-ndc gem into your Gemfile.plugin
```ruby
gem 'peatio-ndc', '~> 0.1.0'
```

2. Run `bundle install` for updating Gemfile.lock

3. Build custom Peatio 

4. Push your image using `docker push`

5. Update your deployment to use image with peatio-ndc gem

### Peatio Configuration.

1. Create ndc Blockchain [config example](../config/blockchains.yml).
    * No additional steps are needed

2. Create ndc Currency [config example](../config/currencies.yml).
    * No additional steps are needed

3. Create ndc Wallets [config example](../config/wallets.yml)(deposit and hot wallets are required).
    * No additional steps are needed




## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Consulting

You can contact Openware for finding certified vendors:
[platform.ndc.io](https://platform.ndc.io)

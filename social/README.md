# Ruby Social Samples

## Twitter

[Repositorio Github de la gema twitter](https://github.com/sferik/twitter)

Crear tu [aplicación en Twitter](https://dev.twitter.com)

Instalar la gema

    $ gem install twitter

Reemplazar en twitter.rb las credenciales de la aplicación en Twitter creada

    config.consumer_key        = "YOUR_CONSUMER_KEY"
    config.consumer_secret     = "YOUR_CONSUMER_SECRET"
    config.access_token        = "YOUR_ACCESS_TOKEN"
    config.access_token_secret = "YOUR_ACCESS_SECRET"

Ejecutar

    $ ruby twitter.rb

## Facebook

[Repositorio Github de la gema koala](https://github.com/arsduo/koala)

Crear un access token en [Facebook's Graph API Explorer](https://developers.facebook.com/tools/explorer)

Instala la gema

    $ gem install koala

Reemplazar el "ouath_access_token"

    @graph = Koala::Facebook::API.new(oauth_access_token)

Ejecutar

    $ ruby facebook.rb

## Linkedin

[Repositorio Github de la gema linkedin](https://github.com/hexgnu/linkedin)

Crear tu [aplicación en Linkedin](https://www.linkedin.com/secure/developer)

Instalar la gema

    $ gem install linkedin

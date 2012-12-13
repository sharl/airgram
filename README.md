# airgram - Push notification to Airgram

## Join Airgram service ([http://www.airgramapp.com/dev/login](http://www.airgramapp.com/dev/login))

*Key* and *Secret* use later.

## Install AirgramApp

- iOS [http://itunes.apple.com/app/id504536405?mt=8](http://itunes.apple.com/app/id504536405?mt=8)
- Android [http://market.android.com/details?id=com.airgram.app](http://market.android.com/details?id=com.airgram.app)

## Setup App

Setup account.

## Write config file

    $ cat > ~/.airgram
    email = your.mail.address@example.com
    Key = Key
    Secret = Secret

## Just do it

    $ airgram push to Airgram
    $ echo foo bar | airgram
    $ airgram
    foo bar
    ^D

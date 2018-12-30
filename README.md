# Matomo LoginTokenAuth Plugin

## Description

This plugin extends the standard Matomo authentication to allow `token_auth` Authentication.

How do I setup LoginTokenAuth using Matomo?

* Upload the plugin files to your Matomo installation plugin directory
    * default path `/matomo_directory/plugins/`
* Login your Matomo as Super User. Click Settings, then click Plugins.
* Active the LoginTokenAuth plugin.
* Login over the implemented logme method:

    `https://matomo.example.com/index.php?module=LoginTokenAuth&action=logme&token_auth=YOUR_TOKEN_STRING`

    * The TokenAuth login is allowed for all users except Super Users
    * You can use all parameters allowed by the default `logme`
    method provided by the default Login Matomo Plugin

## License

GPL v3+


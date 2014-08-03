# plushu-app-name-domain

This plugin implements the default domain for an app, based on its name.

If an app's name contains a dot ('.'), it is interpreted as that app's default
domain. Otherwise, if a domain is defined for the server in
`$PLUSHU_ROOT/APPS_DOMAIN`, the app's default domain will be the name of the
app as a subdomain of `APPS_DOMAIN` (eg. if `APPS_DOMAIN` were example.com, and
an app were pushed named `myapp`, its defult domain would be
`myapp.example.com`).

See also [plushu/plushu-domains][], which allows for defining additional custom
domains for an app.

[plushu/plushu-domains]: https://github.com/plushu/plushu/plushu-domains

# heroku-buildpack-startstunnel

This buildpack starts stunnel.

Requirements:

- https://github.com/timshadel/heroku-buildpack-stunnel.git
- `stunnel.conf` under `/config`

To have stunnel start as part of your build process, add
`https://github.com/grnhse/heroku-buildpack-startstunnel.git`
to `.buildpacks` after
`https://github.com/timshadel/heroku-buildpack-stunnel.git`.

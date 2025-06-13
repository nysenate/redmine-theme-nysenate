Redmine theme: nysenate
=======================

This is a Github-like theme for Redmine, customized for the New York State
Senate.  It is based on the "Gitmike" theme, version 1.2.1, by Makoto Kawasaki,
which in turn is based on the "A1" theme, version 1.0.3, by Kirill Bezrukov.

## Installation

### Install theme

1. Download from https://github.com/nysenate/redmine-theme-nysenate/tags
1. Move to `redmine/themes/nysenate`

Or by using git:

```
cd redmine/themes
git clone https://github.com/nysenate/redmine-theme-nysenate.git nysenate
```

### Change theme

1. Open Redmine in a browser
1. Login as admin user
1. Go to ``Administration > Settings > Display``
1. Select ``Nysenate`` from the ``Theme`` drop-down
1. Click the ``Save`` button

## Development

```
cd redmine/themes/
git clone https://github.com/nysenate/redmine-theme-nysenate.git nysenate
cd nysenate/
npm install -g gulp-cli
yarn
gulp debug
```

## License

GNU General Public License (GPL) Version 2


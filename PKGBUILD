# Maintainer: Michael Berg (jk799)
# Former Maintainer & Contributor: Jeremy Newton (Mystro256)
#
# Skype version of gnome-shell-extension-pidgin-status
# Thanks to kdas for PKGBUILD idea and Mo Morsi for extension idea

pkgname=gnome-shell-extension-skype-status
pkgver=3.4.1
pkgrel=2
pkgdesc="A gnome shell extension that places the tray icon from Skype on the top bar rather than the hidden bottom bar"
url="https://github.com/jk779/gnome-shell-extension-skype-status"
depends=('skype' 'gnome-shell')
source=('extension.js' 'metadata.json')
license=('GPL')
arch=('any')
build() {
  cd "$srcdir"
  mkdir -p "$pkgdir/usr/share/gnome-shell/extensions/skype.status@github.com_jk779_gnome-shell-extension-skype-status"
  cp extension.js $pkgdir/usr/share/gnome-shell/extensions/skype.status@github.com_jk779_gnome-shell-extension-skype-status
  cp metadata.json $pkgdir/usr/share/gnome-shell/extensions/skype.status@github.com_jk779_gnome-shell-extension-skype-status
}
md5sums=('b67ce44456564b49254fbb9b3a86e364'
         '91744e98831d5e3b1bb0ddbcac03c581')

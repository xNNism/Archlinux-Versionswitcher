# Maintainer: xnn xnnism@gmail.com

pkgname=archlinux-versionswitcher
pkgver=1.0.0
pkgrel=1
pkgdesc="Archlinux-Versionswitcher"
arch=('any')
url="https://github.com/xnnism/archlinux-versionswitcher"
license=('GPL')
depends=('python2' 'qt4' 'python2-pyqt4' 'gksu' 'java-runtime-common')

package() {
  cd "$pkgdir"

  install -Dm755 "$srcdir/usr/bin/archlinux-versionswitcher" usr/bin/archlinux-versionswitcher

  cp -R "$srcdir/usr/lib/" usr/lib
  cp -R "$srcdir/usr/share/" usr/share
}

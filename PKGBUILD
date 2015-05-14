# Maintainer: Daniel Hillenbrand <codeworkx [at] bbqlinux [dot] org>

pkgname=bbqlinux-config-gtk
pkgver=1.0.0
pkgrel=1
pkgdesc="BBQLinux GTK Configuration"
arch=('any')
url="https://github.com/bbqlinux/bbqlinux-config-gtk"
license=('GPL')
groups=('bbqlinux')

package() {
    cd "$pkgdir"
    mkdir -p etc

    cp -R "$srcdir/etc/skel" etc/skel
}

# Contributor: Jakub Matraszek <jakub.matraszek[at]gmail[dot]com>

pkgname=cnq3-bin
pkgver=1.50
pkgrel=1
pkgdesc="The Challenge Quake 3 (CNQ3) engine"
url="https://playmorepromode.org/"
license=('custom')
arch=('any')
source=('https://cdn.playmorepromode.com/files/cnq3/cnq3-1.50.zip')
sha256sums=('ce0a62c053ad5425f96a77a27cfae06f19f0a797e4d3b79080e5ae9da758dd0d')
PKGEXT='.pkg.tar'

package() {
        install -D "${srcdir}/cnq3-x64" "${pkgdir}/usr/bin/cnq3"
}

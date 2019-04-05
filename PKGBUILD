# Contributor: Jakub Matraszek <jakub.matraszek[at]gmail[dot]com>

pkgname=cnq3-bin
pkgver=1.51
pkgrel=1
pkgdesc="The Challenge Quake 3 (CNQ3) engine"
url="https://playmorepromode.org/"
license=('custom')
arch=('any')
source=('https://cdn.playmorepromode.com/files/cnq3/cnq3-1.51.zip')
sha256sums=('4cfd2e8071c9bbc158b1469aac58837057222eb9a04083edb2bae6955643312e')
PKGEXT='.pkg.tar'

package() {
        install -D "${srcdir}/cnq3-x64" "${pkgdir}/usr/bin/cnq3"
}

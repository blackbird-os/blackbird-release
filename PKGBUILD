# $Id$
# Maintainer: James Kittsmiller (AJSlye) <james@nulogicsystems.com>

pkgname=blackbird-release
pkgver=$(date +%Y.%m)
pkgrel=1
pkgdesc="Blackbird release definition"
arch=('any')
url="N/A"
license=('GPL')
depends=('bash')
conflicts=('manjaro-release')
install="blackbird-release.install"
source=("lsb-release")
md5sums=('SKIP')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/
}

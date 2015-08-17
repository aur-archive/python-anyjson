# Maintainer: Benjamin A. Shelton <zancarius@gmail.com>
# Contributor: p2k <Patrick.Schneider@uni-ulm.de>
# Source: https://github.com/zancarius/archlinux-pkgbuilds

pkgname=python-anyjson
pkgver=0.3.3
pkgrel=2
pkgdesc="Wraps the best available JSON implementation available in a common interface."
arch=(any)
url="http://pypi.python.org/pypi/anyjson"
license=(BSD)
depends=(python)
makedepends=(python-distribute)
source=("http://pypi.python.org/packages/source/a/anyjson/anyjson-${pkgver}.tar.gz")
md5sums=(2ea28d6ec311aeeebaf993cb3008b27c)

build () {
    
    cd "${srcdir}/anyjson-${pkgver}"
    python setup.py install --root="${pkgdir}/" --optimize=1

}

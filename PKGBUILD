# Maintainer: Johannes Schlatow <johannes.schlatow@googlemail.com>

pkgname=mbeddr
pkgver=1268
pkgrel=2
pkgdesc="An extensible C language and IDE with support for formal verification, requirements and PLE"
arch=('any')
url="http://mbeddr.wordpress.com/"
license=('EPL')
depends=('jetbrains-mps')
makedepends=('')
optdepends=('nusmv: to be able to verify state machines'
            'yices-bin: to be able to verify decision tables and feature models'
            'cbmc-bin: to be able to verify component protocols and contracts')
            'graphviz'
source=("http://voelter.de/mbeddr/${pkgver}/com.mbeddr.allInOne.zip")
sha256sums=('898d5d8cac983ba7b57cb6d2f2144a1a0163d251a426cae712342cf8ad31006c')

#build() {
#    cd "${srcdir}"
#}

package() {
    install -d "${pkgdir}/opt/JetBrains-MPS/"
    mv "${srcdir}/plugins" "${pkgdir}/opt/JetBrains-MPS/plugins"
}

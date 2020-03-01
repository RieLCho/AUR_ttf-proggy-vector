pkgname=ttf-ProggyVector
pkgver=1.1.5
_pkgname=proggyfonts-${pkgver}
pkgrel=1
pkgdesc="Proggy Vector is Monospaced, Fixed-width TrueType font optimized for C,C++ programming."
arch=('any')
url="https://github.com/bluescan/proggyfonts"
license=('MIT')
install=${pkgname}.install
source=("https://github.com/bluescan/proggyfonts/archive/v${pkgver}.zip")
md5sums=('SKIP')

package(){
    install -d "${pkgdir}/usr/share/fonts/TTF/"
    install -m644 "${srcdir}/${_pkgname}/ProggyVector/ProggyVector Regular.ttf" "${pkgdir}/usr/share/fonts/TTF" 
}
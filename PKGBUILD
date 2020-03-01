pkgname=proggyfonts
pkgver=1.1.5
_pkgname=${pkgname}-${pkgver}
pkgrel=1
pkgdesc="Proggy Vector is Monospaced, Fixed-width TrueType font optimized for C,C++ Programming."
arch=('any')
url="https://github.com/bluescan/proggyfonts"
license=('MIT')
install=ttf-ProggyVector.install
source=("https://github.com/bluescan/proggyfonts/archive/v${pkgver}.zip")
md5sums=('SKIP')

package(){
    install -d "${pkgdir}/usr/share/fonts/TTF"
    install -t "${pkgdir}/usr/share/fonts/TTF" -m644 ${_pkgname}/ProggyVector/ProggyVector Regular.ttf
}
pkgname=ttf-ProggyVector
pkgver=1.1.5
pkgrel=1
pkgdesc="Proggy Vector is Monospaced, Fixed-width TrueType font optimized for C,C++ Programming."
arch=('any')
url="https://github.com/bluescan/proggyfonts"
license=('MIT')
install=${pkgname}.install
source=("https://github.com/bluescan/proggyfonts/archive/v${pkgver}.zip")
md5sums=('SKIP')

package(){
    mkdir -p "${pkgdir}/usr/share/fonts/"{TTF}
    
    install -m644 "${_pkgname}/ProggyVector/ProggyVector Regular.ttf" "${pkgdir}/usr/share/fonts/TTF" 
}
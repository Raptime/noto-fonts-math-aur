# Maintainer: 
pkgname=noto-fonts-math
pkgver=20190124
pkgrel=1
pkgdesc="Google Noto math fonts"
arch=(any)
url="https://www.google.com/get/noto/"
license=("custom:SIL")
depends=(fontconfig xorg-font-utils)
source=("https://github.com/googlei18n/noto-fonts/raw/master/hinted/NotoSansMath-Regular.ttf")
sha256sums=('23e7ad7cb0a5a4cf75e07c9e0848b1eb06bba15e8fa9b8cb0579fc823c532927')

package() {
    install -d "${pkgdir}/usr/share/fonts/${pkgname}/"
    install -t "${pkgdir}/usr/share/fonts/${pkgname}/" -m644 "${srcdir}/NotoSansMath-Regular.ttf"
}

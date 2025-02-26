# Maintainer: Your Name <your.email@example.com>
pkgname=waybar-styles
pkgver=1.0.0
pkgrel=1
pkgdesc="Multiple themes and styles for Waybar"
arch=('any')
url="https://github.com/AriDeltaO/waybar-styles"
license=('MIT')
depends=('waybar' 'nerd-fonts-complete' 'git')
source=("https://github.com/AriDeltaO/waybar-styles/archive/v${pkgver}.tar.gz")
sha256sums=('SKIP')  # Replace with actual checksum after first build

package() {
    install -d "${pkgdir}/usr/share/waybar/styles"
    cp -r "${srcdir}/waybar-styles-${pkgver}/themes/"* "${pkgdir}/usr/share/waybar/styles/"
}



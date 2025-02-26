# Maintainer: AriDeltaO
pkgname=waybar-styles
pkgver=1.0.0
pkgrel=1
pkgdesc="Multiple themes and styles for Waybar"
arch=('any')
url="https://github.com/AriDeltaO/waybar-styles"
license=('MIT')
depends=('waybar' 'git')
optdepends=(
    'ttf-nerd-fonts-symbols: Recommended for proper icon rendering'
    'ttf-nerd-fonts-symbols-mono: Alternative font for icons'
    'nerd-fonts-complete: Full Nerd Font package (optional, large size)'
)
source=("https://github.com/AriDeltaO/waybar-styles/archive/v${pkgver}.tar.gz")
sha256sums=('SKIP')  # Skip checksum verification for now

package() {
    echo "🚀 Starting Waybar Styles installation..."
    sleep 1  # Adds a slight delay for readability

    echo "📂 Creating directory: /usr/share/waybar/styles"
    install -d "${pkgdir}/usr/share/waybar/styles"

    echo "🎨 Copying themes to /usr/share/waybar/styles..."
    cp -r "${srcdir}/waybar-styles-${pkgver}/themes/"* "${pkgdir}/usr/share/waybar/styles/"

    echo "✅ Waybar themes have been installed successfully!"
}



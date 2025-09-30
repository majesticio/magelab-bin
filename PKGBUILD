# Maintainer: Your Name <your-email@example.com>
pkgname=magelab
pkgver=0.7.2
pkgrel=1
pkgdesc="Mage Lab is a user-centric AI interface with local reasoning and tools"
arch=('x86_64')
url="https://github.com/majesticio/mage-lab"
license=('MIT')
depends=('cairo' 'desktop-file-utils' 'gdk-pixbuf2' 'glib2' 'gtk3' 'hicolor-icon-theme' 'libsoup3' 'pango' 'webkit2gtk-4.1' 'libappindicator-gtk3')
options=('!strip' '!emptydirs')
install=${pkgname}.install
# source_x86_64=("https://github.com/majesticio/mage-lab/releases/download/v0.3.2/magelab_0.5.0_amd64.deb")
# source_x86_64=("${url}/releases/download/v${pkgver}/magelab_${pkgver}_amd64.deb")
source_x86_64=("magelab_${pkgver}_amd64.deb")
sha256sums_x86_64=('SKIP')

package() {
  bsdtar -xf "${srcdir}/data.tar.gz" -C "${pkgdir}/"
}



pkgname=beam-bin
pkgver=0.1.0
pkgrel=1
pkgdesc="BeamAI desktop application"
arch=('x86_64')
url="https://github.io"
license=('custom')
depends=('glibc')
provides=("beamai")
conflicts=("beamai")
source=("beamai_0.1.0_amd64.deb"
        "BeamIcon.desktop"
        "beamai.png")
sha256sums=('67c8401cdadab76ef0ea28367debaff074a087487c24727c144bc2bdb7a10f82'
            'a6f44cfaea602d76a7cc07d16c03ef04abd740e78cd5977d8cefcd5c928e124f'
            '8be7b669b8f08009c59b76212ee46ea5077bf79598defe8da2cc82d527b29fcd')

package() {
  ar x "${srcdir}"/beamai_0.1.0_amd64.deb data.tar.gz
  
  tar -xf data.tar.gz -C "${pkgdir}"
  rm -f "${pkgdir}/usr/share/applications/"*
  
  install -Dm644 "${srcdir}/BeamIcon.desktop" "${pkgdir}/usr/share/applications/beamai.desktop"
  install -Dm644 "${srcdir}/beamai.png" "${pkgdir}/usr/share/icons/hicolor/512x512/apps/beamai.png"
}

pkgname=beam-bin
pkgver=0.1.0
pkgrel=1
pkgdesc="BeamAI desktop application"
arch=('x86_64')
url="https://github.io"
license=('custom')
depends=('glibc')
provides=("beamai")
conflicts=("beamai")
source=("beamai_0.1.0_amd64.deb"
        "BeamIcon.desktop"
        "BeamIcon.png")

package() {
  ar x "${srcdir}"/beamai_0.1.0_amd64.deb data.tar.gz
  
  tar -xf data.tar.gz -C "${pkgdir}"
  rm -f "${pkgdir}/usr/share/applications/"*
  
  install -Dm644 "${srcdir}/BeamIcon.desktop" "${pkgdir}/usr/share/applications/beamai.desktop"
  install -Dm644 "${srcdir}/BeamIcon.png" "${pkgdir}/usr/share/icons/hicolor/512x512/apps/BeamIcon.png"
}

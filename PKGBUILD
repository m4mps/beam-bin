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
            '990262a8911b381def8ba483014e0420bb8cf093e3cfabc5263b99103dce68db'
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

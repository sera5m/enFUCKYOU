# Maintainer: Grok
pkgname=enfuckyou
pkgver=2.0.0
pkgrel=1
pkgdesc="Frame-bordered ENF suppressor with structured fake cover (overlapping analysis + integrated phase)"
arch=('any')
url="https://x.ai"
license=('MIT')
depends=('python' 'python-numpy' 'python-scipy' 'ffmpeg')
source=("enFUCKYOU.py" "enfuckyou.desktop")
sha256sums=('SKIP' 'SKIP')

package() {
  install -Dm755 enFUCKYOU.py "${pkgdir}/usr/bin/enFUCKYOU"
  install -Dm644 enfuckyou.desktop "${pkgdir}/usr/share/applications/enfuckyou.desktop"
}

pkgname=firefox-tweaks-blend
pkgver=2023.01.09
pkgrel=1
pkgdesc='Currently relevant tweaks for Firefox such as Wayland enablement'
url='https://github.com/blend-os/firefox-tweaks-blend'
arch=('any')
license=('Public domain')
makedepends=()
depends=()
source=('firefox.sh')
sha256sums=('b4c14462f0b76d269d85b227c33c4759a189ecaf9cfca17749410eaad1911fc9')

package() {
	install -d "$pkgdir"/etc/profile.d/
	install -m644 "$srcdir"/firefox.sh "$pkgdir"/etc/profile.d/
}

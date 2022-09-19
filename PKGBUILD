# Maintainer: Safwan Nayeem Yousuf <safwannayeemyousuf.com>
pkgname=ramallahos-albert-config
pkgver=1
pkgrel=1
pkgdesc="Albert config for RamallahOS"
arch=('any')
url="https://github.com/ramallahos/$pkgname"
license=('GPL3')
depends=('albert')
makedepends=('coreutils')
source=("$pkgname::git+$url.git")
sha256sums=('SKIP')

package() {
    cd "$pkgname"
    install -d "${pkgdir}/etc/skel/.config/albert"
    install -Dm 644 ".bashrc" "${pkgdir}/etc/skel/.config/albert/albert.conf"
}

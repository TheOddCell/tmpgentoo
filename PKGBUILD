pkgname=tmpgentoo
pkgver=1.0.0
pkgrel=1
pkgdesc="Part of the tmplinux suite. Temporary gentoo Linux"
arch=('any')
url="https://github.com/TheOddCell/tmpgentoo"
license=('MIT')
depends=('bash' 'tar' 'ncurses' 'xz' 'curl' 'shadow' 'util-linux' 'systemd' 'squashfs-tools')
makedepends=()
source=('tmpgentoo')
sha256sums=('SKIP')

package() {
    install -Dm755 tmpgentoo "$pkgdir/usr/bin/tmpgentoo"
}

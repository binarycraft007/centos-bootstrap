# Maintainer: adityaphra <aditya.phra@gmail.com>

pkgname="centos-bootstrap"
pkgver="0.0.1"
pkgrel="1"
pkgdesc="Bootstrap a base Centos Linux system"
arch=("x86_64" "armv7h" "aarch64")
url="https://github.com/binarycraft007/centos-bootstrap"
depends=('rpmextract')
license=("MIT")
source=(
	"centos-bootstrap.sh"
)
sha512sums=(
	'9fae5c969ad4dfd44aa542289600e81b4f83f8ce9fc2fd8336753a39315d81ba7c4b8d1a1b2ed9218b38b08320a0576bef825c93d34d4c32141f237b65dcaae5'
)

package() {
    install -Dm755 centos-bootstrap.sh "$pkgdir/usr/bin/centos-bootstrap"
}

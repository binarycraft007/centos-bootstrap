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
	'856a9d1781f446aa5b5526b2acacfc8bfbc83b3375668bb1ccd90fa6ffe04f7e1d860c98f6fa064821f551a511a7e1bacec1fdf966febbcded39648e7b2c4238'
)

package() {
    install -Dm755 centos-bootstrap.sh "$pkgdir/usr/bin/centos-bootstrap"
}

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
	'877b02a1a82a2829a3c0bea069053219372652ef9f83fae5d1e3beea8de20f239d8f269e504a9ff9a90ce79d6528a84de5d14b6d9fec969610c70eaa1354ec1f'
)

package() {
    install -Dm755 centos-bootstrap.sh "$pkgdir/usr/bin/centos-bootstrap"
}

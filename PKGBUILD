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
	'85ce2767ea2feae94973c58ef5a81f7e27174032233f7689287ada25c541e1a034d281b9ee6f1cdd8d64153d5179e7b56e9c1847925ae4134024fe6e6ba734b2'
)

package() {
    install -Dm755 centos-bootstrap.sh "$pkgdir/usr/bin/centos-bootstrap"
}

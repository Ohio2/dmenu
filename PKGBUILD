# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

# Maintainer: Your Name <youremail@domain.com>
pkgname=dmenu-ohio2
pkgver=5.0
pkgrel=1
epoch=
pkgdesc="DMENU fork (Ohio)"
arch=("x86_64")
url="https://git.hippoz.xyz/rice/dmenu"
license=('GPL')
groups=()
depends=()
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=("git+https://git.hippoz.xyz/rice/dmenu")
noextract=()
md5sums=('SKIP')
validpgpkeys=()

build() {
	cd "dmenu"
	make
}

package() {
	cd "dmenu"
	make DESTDIR="$pkgdir/" install
}

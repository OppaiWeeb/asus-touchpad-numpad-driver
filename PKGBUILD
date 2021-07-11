# Maintainer: alecromski <alecromski@gmail.com>
pkgname=asus-touchpad-numpad-driver
base=$(pwd)
pkgver=1.0
pkgrel=1
pkgdesc="asus touchpad numpad toggler"
arch=('any')
url="https://github.com/mohamed-badaoui/asus-touchpad-numpad-driver"
license=('GPL')
groups=()
depends=('python>=3.8'
		'libevdev'
		'python-libevdev'
		'i2c-tools'
		'git')
makedepends=()
checkdepends=()
optdepends=()
provides=(asus-touchpad-numpad-driver)
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=("$url")
noextract=($source)
md5sums=(SKIP)
validpgpkeys=()

prepare() {
	echo "[!]Prepare install"
}

package() {
	cd $base
	./install.sh
}

pkgname=Lim-gtk-theme
pkgver=0.3
pkgrel=1
pkgdesc="flat style GTK3 theme for budgie desktop"
arch=('any')
url="https://github.com/darkomarko42/Lim"
license=('GPL3')

makedepends=('git')
source=("git+https://github.com/darkomarko42/Lim.git")

sha256sums=("SKIP")

package() {
	cd Lim/
	mkdir -p "$pkgdir"/usr/share/themes/
	cp -r Lim "$pkgdir"/usr/share/themes/
	cp -r Lim\ Dark "$pkgdir"/usr/share/themes/
}

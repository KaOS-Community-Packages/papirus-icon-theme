pkgname=papirus-icon-theme
pkgver=20220606
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('8011b1ff24af2ffa6019bae79b3e2fd0')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}

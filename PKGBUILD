pkgname=papirus-icon-theme
pkgver=20220910
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('a50c7904c69db0e927cb48669f193b08')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}

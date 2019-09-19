pkgname=papirus-icon-theme
pkgver=20190919
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('e3449717a511456af458e9f8540746f1')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}

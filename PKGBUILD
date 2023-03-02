pkgname=papirus-icon-theme
pkgver=20230301
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('925328f64ebc832d617e2dc8acfc3ca1')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}

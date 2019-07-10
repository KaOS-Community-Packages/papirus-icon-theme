pkgname=papirus-icon-theme
pkgver=20190708
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('0e3022eafe8d9fdaa447d7f5ef090157')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}

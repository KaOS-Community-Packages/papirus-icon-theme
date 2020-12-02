pkgname=papirus-icon-theme
pkgver=20201201
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('52010cb71959e9a3601b867cd972e7d4')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}

pkgname=papirus-icon-theme
pkgver=20200301
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('186aa544a9cf95ddc5a37d4ab0dcb268')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}

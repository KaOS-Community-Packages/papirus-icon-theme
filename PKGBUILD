pkgname=papirus-icon-theme
pkgver=20220508
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('8e62a2c66aead23055aecb4af16809bf')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}

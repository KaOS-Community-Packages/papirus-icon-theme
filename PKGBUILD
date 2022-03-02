pkgname=papirus-icon-theme
pkgver=20220302
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('ef9d719696e2a7e9eea93d013994b455')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}

pkgname=papirus-icon-theme
pkgver=20201001
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('1db091cce42e6b8ff7fefc4200fc3710')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}

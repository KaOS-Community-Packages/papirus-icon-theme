pkgname=papirus-icon-theme
pkgver=20200801
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('47bddb6ca4e1bb9fb3938306c81e0700')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}

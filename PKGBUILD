pkgname=papirus-icon-theme
pkgver=20210101
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('e122014844c8679642d1c44aa119c78e')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}

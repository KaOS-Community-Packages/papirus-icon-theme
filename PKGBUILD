pkgname=papirus-icon-theme
pkgver=20190615
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('f78a13f9a4d47bcc1de3f443c6e37b1b')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}

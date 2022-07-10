pkgname=papirus-icon-theme
pkgver=20220710
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('a4ddf6765df49750caf87d56a91f9d20')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}

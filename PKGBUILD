pkgname=papirus-icon-theme
pkgver=20180720
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("$pkgname-$pkgver.tar.gz::https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
sha512sums=('cb55be157deb78fd22e2fef3921dbcd7e53da7a66e933c60fce35009eceecd3f413df261b80888a7a7b05917d6c52044b0ebd0f46a0492ba50d312a7729bac87')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}

#
# Maintainer: Nicolae Carabut <nicolae@remote.it>
# Contributor:
#

pkgname=remoteit-cli
pkgdesc="Securely connect to your other devices like laptops, raspberry pi, android, ios, servers, etc"
pkgver=1.2.6
pkgrel=1
arch=("x86_64")
url="https://remote.it"
license=('MIT')
source=("https://github.com/remoteit/cli/releases/download/v1.2.6/remoteit_linux_x86_64")
md5sums=(SKIP)
conflicts=('remoteit-desktop')

package() {
	install -dm755 "${pkgdir}"/usr/bin/
	cp -a "${srcdir}/remoteit_linux_x86_64" "${pkgdir}"/usr/bin/remoteit
}


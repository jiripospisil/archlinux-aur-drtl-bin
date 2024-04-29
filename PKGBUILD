# Maintainer: Jiri Pospisil <jiri@jpospisil.com>
#
pkgname=drtl-bin
pkgver=0.0.19
pkgrel=1
pkgdesc='Yet another tldr client written in Zig.'
url='https://github.com/jiripospisil/drtl'
source_x86_64=("https://github.com/jiripospisil/drtl/releases/download/v$pkgver/drtl-v$pkgver-x86_64-linux")
source_aarch64=("https://github.com/jiripospisil/drtl/releases/download/v$pkgver/drtl-v$pkgver-aarch64-linux")
arch=('x86_64' 'aarch64')
provides=('drtl')
conflicts=('drtl')
license=('MIT')
b2sums_x86_64=('7363a7d0cca7d6e1843b648d2fdd5242fcbb3d4f3a624ef4a0508f6a7f64cbcb8344c2521a2afc15f87695a5fe10eeee947a0a95bb46c770d008897eda66d247')
b2sums_aarch64=('efd17db05e26fdb13cd4a3a53de76a7ab667d8e0d65f6bfa4db886070c885390fcdded8913ca7214b6db617640876c5281911e6052d63b63a5d6142dc1ce67f7')

package() {
  install -Dm755 "$srcdir/drtl-v$pkgver-$CARCH-linux" "$pkgdir/usr/bin/drtl"
}

# Maintainer: Catppuccin <releases@catppuccin.com>

pkgname=catppuccin-gtk-theme-mocha
pkgver=1.0.3 # renovate: datasource=github-tags depName=catppuccin/gtk
pkgrel=1
pkgdesc='Soothing pastel theme for GTK - Mocha'
arch=('any')
license=('GPL3')
url='https://github.com/catppuccin/gtk'
source=(
  "$pkgname-$pkgver-blue.zip::$url/releases/download/v$pkgver/catppuccin-mocha-blue-standard+default.zip"
  "$pkgname-$pkgver-flamingo.zip::$url/releases/download/v$pkgver/catppuccin-mocha-flamingo-standard+default.zip"
  "$pkgname-$pkgver-green.zip::$url/releases/download/v$pkgver/catppuccin-mocha-green-standard+default.zip"
  "$pkgname-$pkgver-lavender.zip::$url/releases/download/v$pkgver/catppuccin-mocha-lavender-standard+default.zip"
  "$pkgname-$pkgver-maroon.zip::$url/releases/download/v$pkgver/catppuccin-mocha-maroon-standard+default.zip"
  "$pkgname-$pkgver-mauve.zip::$url/releases/download/v$pkgver/catppuccin-mocha-mauve-standard+default.zip"
  "$pkgname-$pkgver-peach.zip::$url/releases/download/v$pkgver/catppuccin-mocha-peach-standard+default.zip"
  "$pkgname-$pkgver-pink.zip::$url/releases/download/v$pkgver/catppuccin-mocha-pink-standard+default.zip"
  "$pkgname-$pkgver-red.zip::$url/releases/download/v$pkgver/catppuccin-mocha-red-standard+default.zip"
  "$pkgname-$pkgver-rosewater.zip::$url/releases/download/v$pkgver/catppuccin-mocha-rosewater-standard+default.zip"
  "$pkgname-$pkgver-sapphire.zip::$url/releases/download/v$pkgver/catppuccin-mocha-sapphire-standard+default.zip"
  "$pkgname-$pkgver-sky.zip::$url/releases/download/v$pkgver/catppuccin-mocha-sky-standard+default.zip"
  "$pkgname-$pkgver-teal.zip::$url/releases/download/v$pkgver/catppuccin-mocha-teal-standard+default.zip"
  "$pkgname-$pkgver-yellow.zip::$url/releases/download/v$pkgver/catppuccin-mocha-yellow-standard+default.zip"
)

sha256sums=('83811051cceb32623fafde411350188046370d73ee7464bb26285cd63c753bdc'
  '61504e095a997e6105e71157b29762886e21d38afe8c0031c3174f21e8b0af16'
  'c874ae7326a620ecd8f39cf480aa25284f560a9cff7fb5d8804dd856674a0f03'
  'bce962098f32c676a0170f909b737eed0905d53b6e774f04f152256b5b6dce77'
  '8f4a3eb6570a10b54f5cceb77e1560012370f5ed172b94b517bd8d7fe17fd0c2'
  'cbacdac6161f98c315fb86740e21426ef6dda64f0ad69157cf28f3a1dda446fe'
  'd14dd2e61086025464e1aa577f2ff8a3c9a65d0df16ee1af9f4ec66496e5d9b8'
  'b0ef2b72409017a41be02a7588ff68783128ce69d62716c43f3a35f1914650a8'
  '44d20c597bc4a9a4fb7bd80baaf246b88089b0ce92eadeedca25c18e08f94e17'
  '006c6c48fa33c10c468cd1a9541236be8e09f89b9f0fff15db74d6dcdecaa785'
  '67fab5df50b833dc2cfa5283038cfbe2f3eafbb6a533ac123d4d556dfe02820b'
  '0d0a99bbe3931ffd598083cfee7ff429826e6fd18c206f91fad3f6273ad5649b'
  '15aae4c31c3de08c8d2ae4c22c315cfa6f911bab5e5ec79f6779af1b8c93b457'
  '2be7cf6f460d92af63ee8dcd2794539612487a330d196a5265b2cd32599df643')
package() {
  install -d "$pkgdir/usr/share/themes"
  cp -r -a --no-preserve=ownership \
    catppuccin-mocha-* "$pkgdir/usr/share/themes"
}

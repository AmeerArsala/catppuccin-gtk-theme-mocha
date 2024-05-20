# Maintainer: Catppuccin <releases@catppuccin.com>

pkgname=catppuccin-gtk-theme-mocha
pkgver=0.7.5 # renovate: datasource=github-tags depName=catppuccin/gtk
pkgrel=2
pkgdesc='Soothing pastel theme for GTK3 - Mocha'
arch=('any')
license=('GPL3')
url='https://github.com/catppuccin/gtk'
source=("$pkgname-$pkgver-blue.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Blue-Dark.zip"
        "$pkgname-$pkgver-flamingo.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Flamingo-Dark.zip"
        "$pkgname-$pkgver-green.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Green-Dark.zip"
        "$pkgname-$pkgver-lavender.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Lavender-Dark.zip"
        "$pkgname-$pkgver-maroon.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Maroon-Dark.zip"
        "$pkgname-$pkgver-mauve.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Mauve-Dark.zip"
        "$pkgname-$pkgver-peach.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Peach-Dark.zip"
        "$pkgname-$pkgver-pink.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Pink-Dark.zip"
        "$pkgname-$pkgver-red.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Red-Dark.zip"
        "$pkgname-$pkgver-rosewater.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Rosewater-Dark.zip"
        "$pkgname-$pkgver-sapphire.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Sapphire-Dark.zip"
        "$pkgname-$pkgver-sky.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Sky-Dark.zip"
        "$pkgname-$pkgver-teal.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Teal-Dark.zip"
        "$pkgname-$pkgver-yellow.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Yellow-Dark.zip")
sha256sums=('2862fa1265a0ec714ffb6ef05000001ffa51e2e639e36617028605bc17b516a6'
            '62a1238b5f78c09e1225f6c2f669d5cc0ae33495fc09736b7bae70be3bb2205d'
            '40d8616bebf16cc33ea38e932b4a20b988028cea7b5d26335a9618c8d74825d6'
            '37e4d663922672c9504272919bbeceb9882b59eebd768e2b2f9a23977e04d3c8'
            'bab48750ca19e1cec923f2871c66e2c5475a3c21b1da6ecc06f44b02a1b9f46f'
            '816c6f03d72e7d724f2e67afcb895eda51446c4bc4091e46fb608a006fd6a11a'
            '0f8850bafbce2917d6bccb3de05d8e5b01fee53a36c614869989c577bb434b04'
            '55cbafca17fd937b0b4d866bd917d77f69e427e5a36817852f329323ec42e0d4'
            '299146c2a1fd897f418ef25ef9a1027cb1bb4125fccc44929c6bd30f7ac5707f'
            '561fa59a75f65499f5de191beacfeeb0502771e94bf905950b11d6cc1b5c5b4f'
            '7148e7790f2d6f2726fde72a2699af63cbae07a388fca585e8d96674c4afa8cb'
            'c25cb49d113b799d0b6c6756c9fce06e1ceb436f79c0e245093c988c70f2e4c0'
            'cb1356966f8868fc99e412477dbcc338cb64bcadb031b7534d392487b5a82cc8'
            'eb0e3ae8764ca43ec1b7c3394b9bb2cae1d90be86b1d15c28ce497541bccd759')

package() {
	install -d "$pkgdir/usr/share/themes/"
	cp -r -a --no-preserve=ownership \
    Catppuccin-Mocha-* "$pkgdir/usr/share/themes"
}

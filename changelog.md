# Change log

## [[1.2.8]](https://github.com/lightspeeddevelopment/lsx-give-payfast-gateway/releases/tag/1.2.8) - 2023-08-09

### Security
- General testing to ensure compatibility with latest WordPress version (6.3).
- General testing to ensure compatibility with latest Give - Donation Plugin version (2.31.0).
- General testing to ensure compatibility with latest Give - Recurring Donations (1.12.2).

## [[1.2.7]](https://github.com/lightspeeddevelopment/lsx-give-payfast-gateway/releases/tag/1.2.7) - 2023-04-20

### Security
- General testing to ensure compatibility with latest WordPress version (6.2).

## [[1.2.6]](https://github.com/lightspeeddevelopment/lsx-give-payfast-gateway/releases/tag/1.2.6) - 2022-12-23

### Security
- General testing to ensure compatibility with latest WordPress version (6.1.1).
- General testing to ensure compatibility with latest Give - Donation Plugin version (2.23.2).
- General testing to ensure compatibility with latest Give - Recurring Donations (1.12.2).

## [[1.2.5]](https://github.com/lightspeeddevelopment/lsx-give-payfast-gateway/releases/tag/1.2.5) - 2020-08-07

### Fixed
- Update the plugin to use the same signature generating and verification as the [WooCommerce Extension](https://github.com/woocommerce/woocommerce-gateway-payfast/blob/master/includes/class-wc-gateway-payfast.php#L1046)
- Fixed the signature mismatch.

## [[1.2.4]](https://github.com/lightspeeddevelopment/lsx-give-payfast-gateway/releases/tag/1.2.4) - 2020-03-30

### Security
- General testing to ensure compatibility with latest WordPress version (5.4).
- General testing to ensure compatibility with latest LSX Theme version (2.7).

## [[1.2.3]](https://github.com/lightspeeddevelopment/lsx-give-payfast-gateway/releases/tag/1.2.3) - 2019-09-03

### Added
- Adding the .gitattributes file to remove unnecessary files from the WordPress version.


## [[1.2.2]]()

### Fixed
- Fixed not being able to use surnames or names with more than 1 name.


## [[1.2.1]]()

### Changed
- Changed Prefixes.

### Fixed
- Fixed passphrase signature generation


## [[1.2.0]]()

### Deprecated
- Removed Email Sharing Option


## [[1.1.2]]()

### Deprecated
- Removed API Class


## [[1.1.1]]()

### Changed
- Updated the License class.

### Added
- Added in a note for when your license is active.


## [[1.1.0]]()

### Added
- Added recurring donations support.
- Added in PHPDoc Tags for all functions.

### Changed
- Changed the Global $give_options to call the 'give_get_settings' method.

### Deprecated
- Removed the Functions adding the ZAR Currency and Symbol, this is supported Give WP now.
- Removed the PassPhrase from the ITN validation call.


## [[1.0.1]]()

### Added
- Added support for passphrase.

### Fixed
- Corrected the format of the email address when sent to PayFast.


## [[1.0.0]]()

### Added
- Initial Release.

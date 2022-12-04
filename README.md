## URGENT: This QR Code Modal for Wallet Connect v1.0 is now deprecated. Please use Wallet Connect v2.0

# WalletConnect QR Code Modal

QR Code Modal for WalletConnect

For more details, read the [documentation](https://docs.walletconnect.org)

```js
import WalletConnectQRCodeModal from "walletconnect-qrcode-modal";

/**
 *  Get URI from WalletConnect object
 */
const uri = connector.uri;

/**
 *  Open QR Code Modal
 */
WalletConnectQRCodeModal.open(uri);

/**
 *  Close QR Code Modal
 */
WalletConnectQRCodeModal.close();
```

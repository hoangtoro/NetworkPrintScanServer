# Privacy Policy — Network Print & Scan Server

**Publisher:** hoangdt  
**Effective date:** November 26, 2026

Network Print & Scan Server is a Windows application that shares a Windows-installed printer and, when enabled, a locally connected scanner with other devices on your local network.

## Information the app processes

- **Print jobs:** Print data sent to the configured print-server port is forwarded to the Windows printer selected by the operator.
- **Scans:** When network scanning is enabled, scan requests and image data are exchanged between the scanner host and authorized client PCs over the local network. The server may create temporary scan files while preparing a response and removes those temporary files after processing.
- **Settings and logs:** The app stores server and client settings locally. The client stores the server address and an encrypted access token in the current Windows user's application data; the server stores its settings and scan access token in its local configuration. Logs may contain printer or scanner names, local network addresses, connection events, and error details.
- **Store entitlement:** If you purchase the network-scanning add-on, the app checks its entitlement through Microsoft Store. Microsoft processes the purchase; the app publisher does not receive payment-card details through the app.

The app does not send print jobs, scans, configuration, or logs to the publisher. It does not include a publisher-operated analytics service. The Store purchase flow communicates with Microsoft Store. Scan access uses a bearer token over HTTP on your local network; use network scanning only on a network you trust and keep the token private.

## Your choices and data deletion

You choose the printer, whether to enable network scanning, which clients receive the scan token, and where client scans are saved. You can disable the scan API, rotate the token, delete saved scans and logs, or uninstall the app. Configuration files may remain in your Windows user profile after uninstall and can be removed manually.

## Contact

For privacy questions or support, open an issue in the [Network Print & Scan Server GitHub repository](https://github.com/hoangtoro/NetworkPrintScanServer/issues).

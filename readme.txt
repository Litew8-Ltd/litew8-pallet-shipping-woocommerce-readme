=== Litew8 Pallet Shipping for WooCommerce ===
Contributors: litew8
Tags: woocommerce, shipping, pallet, freight, logistics
Requires at least: 6.0
Tested up to: 6.9.4
Requires PHP: 8.0
Requires Plugins: woocommerce
Stable tag: 1.0.3
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Create carrier consignments, print labels, transmit manifests, and track pallet shipments directly from WooCommerce.

== Description ==

Litew8 Pallet Shipping for WooCommerce connects your WooCommerce store to the LiteW8 pallet shipping workflow without leaving the WordPress admin area.

Features include:

* License activation, subscription status checks, and LiteW8-delivered plugin updates inside WooCommerce.
* Carrier API connection using your Customer Login URL, Username, and Password, plus LiteW8 backend identity registration.
* Consignment creation directly from WooCommerce orders with recovery handling, tracking links, and order note updates.
* Instant quote preview with a clearer placeholder state while shipment details are being completed.
* A4 and thermal label generation plus shipment paperwork for pallet consignments.
* Awaiting-consignment transmission, optional daily auto transmit, manifest history, and printable manifests.
* Shipment defaults for collection details, pallet sizes, service options, timed deliveries, and delivery extras.
* Optional Quick Order Search shortcut in the WordPress admin bar.
* Dedicated Support tab with a direct support request form and attached support snapshot.
* Lightweight admin help flyout for docs and support links.
* WooCommerce HPOS compatibility.

== Installation ==

1. Upload the plugin to `/wp-content/plugins/` or install it as a zip from the WordPress admin.
2. Activate `Litew8 Pallet Shipping for WooCommerce`.
3. Go to `WooCommerce > Litew8 Pallet Shipping`.
4. Under `Activate Your License`, enter your LiteW8 `License Key` and click `Activate License`.
5. Under `Enter Carrier API Credentials`, enter your `Customer Login URL`, `API Username`, and `API Password`, then click `Save API Credentials`.
6. Review `LiteW8 Backend Identity` to confirm the install UUID and normalized domain.
7. Configure your collection defaults, service options, transmit settings, and support details on the remaining tabs.

== Frequently Asked Questions ==

= What credentials do I need? =

To use the plugin you need:

* A LiteW8 License Key.
* Your carrier Login URL.
* Your carrier API Username.
* Your carrier API Password.

= Where do I find the Customer Login URL? =

Open your carrier customer login page in the browser and copy the main address from the address bar. For example: `https://ab123.tms.live`.

= Does the plugin support updates from LiteW8? =

Yes. With an active license key and working backend connection, plugin updates can be delivered from the LiteW8 EDD store and shown in the WordPress Plugins screen.

== Other Notes ==

= Environment Requirements =

* WordPress 6.0 or newer.
* WooCommerce installed and active.
* PHP 8.0 or newer.
* WooCommerce tested up to 10.6.1.

= Credentials and Connection =

The plugin settings screen stores and uses the following connection details:

* LiteW8 License Key
* Customer Login URL
* API Username
* API Password
* Backend API URL
* Install UUID

= Order Workflow =

Once configured, the plugin helps your team create consignments, print labels, recover from duplicate consignment attempts, transmit awaiting consignments, and track pallet-shipping activity from WooCommerce.

== Changelog ==

= 1.0.3 =

* Improved the instant quote panel graphics.
* Minor rules engine updates.

= 1.0.2 =

* Fixed WordPress plugin update detection issue, so updates are now reliably offered.


= 1.0.1 =

* Improved support email delivery compatibility and added clearer mail failure messages in the Support tab.
* Updated new-install defaults so Transmit Orders starts disabled, with sensible fallback behaviour in place.
* Improved Quick Order Search visibility by adding a fallback launcher when the admin bar is crowded.
* Tidied up the support snapshot and aligned the internal plugin version with the release version.

= 1.0.0 =

* Added a dedicated Support tab with a direct LiteW8 contact form and attached diagnostics snapshot.
* Added a lightweight admin help flyout for support and documentation links.
* Improved consignment error handling with clearer messaging and added order note summaries.

= 0.10.1 =

* Added EDD-driven WordPress plugin update compatibility.
* Added plugin readme metadata for the plugin details modal.

= 0.10.0 =

* Initial release with license activation, carrier API credentials, backend identity registration, consignment tools, transmit settings, and WooCommerce integration.

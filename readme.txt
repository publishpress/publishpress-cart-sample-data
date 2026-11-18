=== PublishPress Cart Sample Data ===
Contributors: publishpress
Requires at least: 6.7
Tested up to: 7.1
Requires PHP: 7.4
Stable tag: 0.3.1
License: GPLv2 or later

Create removable sample data for PublishPress Cart and Studiocart development and QA sites.

== Description ==

Install alongside PublishPress Cart, PublishPress Cart Pro, or Studiocart. Open the active cart's Sample Data menu and click Generate Sample Data. This creates six products, 180 orders dated across the previous year, 36 recurring subscriptions, categories, and tags. Four products include real downloadable files: a workbook, a content calendar, a workshop checklist, and a starter guide. Paid generated orders for those products receive download access when the cart's download table is available. These bundled demo files are public assets served through each cart's download redirect. PublishPress Cart Pro also receives a global coupon and catalog records for a collection, post-checkout offer, and subscription upgrade path. Studiocart receives collection and post-checkout offer records when those post types are registered. The bundled `sample-data/sample_ppcart_tax_rates.csv` is a PublishPress Cart reference file for manual import; this release does not import tax rates or create affiliate records. Premium catalog records are demonstration placeholders, not fully configured checkout flows. Use Remove Sample Data to delete tagged records and their download access rows.

== Changelog ==

= 0.3.1 =
* Add downloadable files to four products and download access for paid generated orders.
* Remove generated download access with the corresponding orders.

= 0.3.0 =
* Add Studiocart products, orders, subscriptions, categories, tags, and available premium catalog records.
* Limit generated subscriptions to paid recurring orders.

= 0.2.1 =
* Initial GitHub release of the companion plugin.

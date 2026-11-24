# Awesome MedusaJS V2

A directory of plugins, storefronts, and implementation teams for building with Medusa v2. Maintained by Olivier Belaud.

- [Build with Medusa v2](#build-with-medusa-v2)
- [Starters, themes, and storefront examples](#starters-themes-and-storefront-examples)
- [Plugins and integrations](#plugins-and-integrations)
- [Medusa Expert agencies](#medusa-expert-agencies)
- [Projects in production](#projects-in-production)
- [Contribute](#contribute)

## Build with Medusa v2

- [Installation](https://docs.medusajs.com/learn/installation) — Set up the backend and admin, with the option to add a starter storefront.
- [V2 architecture and migration](https://docs.medusajs.com/learn/introduction/from-v1-to-v2) — Understand the changes before migrating a V1 project.
- [Commerce recipes](https://docs.medusajs.com/resources/recipes) — Design a B2B store, marketplace, subscription flow, or another commerce use case.
- [Build a storefront](https://docs.medusajs.com/resources/storefront-development) — Use the Store API and JavaScript SDK to build the customer experience.
- [Create a plugin](https://docs.medusajs.com/learn/fundamentals/plugins/create) — Package reusable modules, workflows, and admin extensions.
- [Medusa Cloud](https://docs.medusajs.com/cloud) — Deploy and operate a Medusa application.

## Starters, themes, and storefront examples

### Official starters and storefront templates

- [Essentials and Lumina for Bloom](https://medusajs.com/blog/announcing-essentials-and-lumina-starters-in-bloom) — Medusa-published Bloom themes for a retail storefront and a product recommendation quiz.
- [Essentials Bloom source](https://github.com/medusajs-repos/bloom-starter-essentials) — Source for the Essentials retail storefront featured by Medusa.
- [Grounded for Bloom](https://medusajs.com/blog/announcing-grounded-starter) — Medusa-published storefront theme with core shopping flows, customizable through Bloom.
- [Industrials B2B Starter](https://github.com/medusajs/industrials-b2b-starter) — Industrials storefront theme for Medusa B2B commerce.
- [Industrials Bloom source](https://github.com/medusajs-repos/bloom-starter-industrials) — Bloom storefront template for industrial B2B catalogs featured by Medusa.
- [Medusa B2B Starter](https://github.com/medusajs/b2b-starter) — Next.js starter for company accounts, quotes, and purchasing flows.
- [Medusa DTC Starter](https://github.com/medusajs/dtc-starter) — General-purpose Next.js storefront and Medusa backend for direct-to-consumer commerce.
- [Medusa Starter Directory](https://medusajs.com/starters) — Medusa's directory of core templates and specialized starters.
- [Modern DTC Starter](https://github.com/medusajs/modern-dtc-starter) — Fashion-oriented DTC starter with a TanStack Start storefront and Medusa backend.

### Community themes and storefronts

- [Agilo Fashion Starter](https://github.com/Agilo/fashion-starter) — Fashion-oriented storefront and collection layouts for Medusa v2.
- [Astro Medusa Storefront](https://github.com/digity-studio/astro-medusa-starter) — Open-source Astro and React storefront for Medusa v2 with a Cloudflare Workers deployment path.
- [Barrio](https://github.com/lambda-curry/medusa2-starter) — Coffee-themed Remix storefront and Medusa v2 backend by Lambda Curry.
- [CrowCommerce](https://github.com/EricJamesCrow/commerce-tailwindui-medusa) — Next.js 16 monorepo combining a Vercel Commerce-derived frontend, Tailwind Plus UI patterns, and a Medusa v2 backend.
- [Medusa Mobile](https://github.com/bloomsynth/medusa-mobile-react-native) — React Native storefront with shopping, checkout, account, and theme support for Medusa v2.
- [Nuxt Starter Medusa](https://github.com/OlivierBelaud/nuxt-starter-medusa) — Nuxt 3 storefront starter for Medusa v2 maintained by this list's curator.
- [Svelte Commerce](https://github.com/itswadesh/svelte-commerce) — Multi-backend SvelteKit storefront with a Medusa v2 connector. See the upstream capability matrix.
- [SvelteKit Medusa Starter](https://github.com/pevey/sveltekit-medusa-starter) — Minimal SvelteKit storefront built with the SvelteKit Medusa SDK and component registry.

### Reference builds and examples

- [Agilo Retail POS Starter](https://github.com/Agilo/medusa-pos-starter) — Agilo's in-store sales starter featured in the Medusa starter directory.
- [Medusa Examples](https://github.com/medusajs/examples) — Official Medusa v2 implementations of focused commerce flows.
- [Mercur](https://github.com/mercurjs/mercur) — Open-source multi-vendor commerce platform built on Medusa v2.
- [Munchies](https://github.com/tinloof/munchies) — Tinloof's reference B2C monorepo using Next.js, Sanity, and Medusa v2.

## Plugins and integrations

The Medusa directory lists **161 V2 packages** as of November 24, 2026. The tables also include selected guides and community integrations with independent V2 evidence. Each entry identifies an official Medusa package, partner integration, community package, or guide. Check each listing for installation instructions and supported versions. [Medusa integrations](https://medusajs.com/integrations)

[Admin and workflows](#admin-and-workflows) · [AI and developer tooling](#ai-and-developer-tooling) · [Analytics and observability](#analytics-and-observability) · [Authentication and identity](#authentication-and-identity) · [Billing, subscriptions, and digital products](#billing-subscriptions-and-digital-products) · [Catalog and merchandising](#catalog-and-merchandising)

[Content management](#content-management) · [Customers, reviews, and support](#customers-reviews-and-support) · [ERP and back-office systems](#erp-and-back-office-systems) · [File storage](#file-storage) · [Fulfillment and shipping](#fulfillment-and-shipping) · [Marketplaces and sales channels](#marketplaces-and-sales-channels)

[Migration and data sync](#migration-and-data-sync) · [Notifications and messaging](#notifications-and-messaging) · [Payments](#payments) · [Pricing and point of sale](#pricing-and-point-of-sale) · [Search and discovery](#search-and-discovery) · [Tax, invoicing, and compliance](#tax-invoicing-and-compliance)

### Admin and workflows

| Extension or resource | Type |
| --- | --- |
| [Admin Customizations](https://medusajs.com/integrations/@webberswebbers-medusa) | Medusa partner |
| [Admin Integration Config](https://medusajs.com/integrations/@gorgomedusa-integration) | Community |
| [Automations](https://medusajs.com/integrations/@codee-automations) | Community |
| [AWS EventBridge](https://github.com/ikhvost/medusa-event-bus-aws) — Publishes Medusa events to EventBridge. The module does not subscribe to events in Medusa. | Community |
| [CRZA Plugins](https://medusajs.com/integrations/@crza69medusa-plugins) | Community |
| [Flow Builder](https://medusajs.com/integrations/@rx-venturesmedusa-flow-builder-plugin) | Community |
| [Order Comments](https://medusajs.com/integrations/medusa-plugin-order-comments) | Community |
| [Webhooks](https://medusajs.com/integrations/lambdacurry-webhooks) | Medusa partner |

### AI and developer tooling

| Extension or resource | Type |
| --- | --- |
| [Agentic Commerce](https://medusajs.com/integrations/@financedistrictmedusa-plugin-agentic-commerce) | Community |
| [AI Product Descriptions](https://medusajs.com/integrations/medusa-plugin-product-description) | Community |
| [Claude Code](https://github.com/medusajs/medusa-agent-skills) | Guide |
| [Enthusiast](https://medusajs.com/integrations/@upsidelabmedusa-plugin-enthusiast) | Community |

### Analytics and observability

| Extension or resource | Type |
| --- | --- |
| [Analytics](https://medusajs.com/integrations/agilo-analytics) | Medusa partner |
| [Blotout Qinto Analytics](https://medusajs.com/integrations/@blotoutplatform-medusa) | Community |
| [Google Analytics](https://medusajs.com/integrations/variablevic-google-analytics) | Community |
| [Meta Commerce](https://medusajs.com/integrations/@wanderwaresmedusa-meta-commerce) | Community |
| [PostHog](https://docs.medusajs.com/resources/infrastructure-modules/analytics/posthog) | Guide |
| [Segment](https://docs.medusajs.com/resources/integrations/guides/segment) | Guide |
| [Sentry](https://docs.medusajs.com/resources/integrations/guides/sentry) | Guide |
| [Store Analytics](https://medusajs.com/integrations/rsc-labs-medusa-store-analytics-v2) | Community |
| [Tinybird](https://medusajs.com/integrations/@zanrealmedusa-usage-tinybird) | Community |

### Authentication and identity

| Extension or resource | Type |
| --- | --- |
| [Argon2](https://medusajs.com/integrations/vymalo-argon2) | Community |
| [Better Auth](https://medusajs.com/integrations/@nualtmedusa-plugin-better-auth) | Community |
| [Email](https://docs.medusajs.com/resources/commerce-modules/auth/auth-providers/emailpass) | Guide |
| [GitHub](https://docs.medusajs.com/resources/commerce-modules/auth/auth-providers/github) | Guide |
| [Google](https://docs.medusajs.com/resources/commerce-modules/auth/auth-providers/google) | Guide |
| [Keycloak](https://medusajs.com/integrations/vymalo-keycloak) | Community |
| [Okta](https://docs.medusajs.com/resources/integrations/guides/okta) | Guide |
| [Passwordless](https://medusajs.com/integrations/devx-commerce-passwordless) | Community |
| [SuperTokens Auth](https://medusajs.com/integrations/@antibusymedusa-supertokens) | Community |
| [Telegram](https://medusajs.com/integrations/@nxmadmedusa-telegram) | Community |
| [Twilio](https://docs.medusajs.com/resources/how-to-tutorials/tutorials/phone-auth) | Guide |
| [WebAuthn](https://medusajs.com/integrations/vymalo-webauthn) | Community |
| [Zitadel](https://medusajs.com/integrations/medusa-auth-zitadel) | Community |

### Billing, subscriptions, and digital products

| Extension or resource | Type |
| --- | --- |
| [Digital Downloads](https://medusajs.com/integrations/@makecryptomedusa-plugin-digital-downloads) | Community |
| [Digital Products](https://medusajs.com/integrations/medusa-plugin-digital-products) | Community |
| [Reorder](https://medusajs.com/integrations/@reorderjsreorder) | Community |
| [Subscriptions recipe](https://docs.medusajs.com/resources/recipes/subscriptions) — Build recurring commerce workflows using Medusa modules. | Guide |
| [Zanreal Usage Metering](https://medusajs.com/integrations/@zanrealmedusa-usage) | Community |

### Catalog and merchandising

| Extension or resource | Type |
| --- | --- |
| [Brand Management](https://medusajs.com/integrations/@mgtalabsmedusa-brand) | Community |
| [Cart Rules](https://medusajs.com/integrations/@xross-devmedusa-cart-rules) | Community |
| [Category Images](https://medusajs.com/integrations/@alphabitemedusa-category-images) | Community |
| [Image-alt](https://medusajs.com/integrations/alpha-solutions-image-alt) | Community |
| [Multistore](https://medusajs.com/integrations/@sepidarmedusa-multistore-plugin) | Community |
| [Product Attributes](https://medusajs.com/integrations/@empty-complete-orgmedusa-product-attributes) | Community |
| [Variant Images](https://medusajs.com/integrations/medusa-variant-images) | Community |

### Content management

| Extension or resource | Type |
| --- | --- |
| [Builder.io](https://medusajs.com/integrations/@weareseeedmedusa-plugin-builder) | Community |
| [Collection images](https://medusajs.com/integrations/@alphabitemedusa-collection-images) | Community |
| [Contentful](https://docs.medusajs.com/resources/integrations/guides/contentful) | Guide |
| [Custom CMS](https://medusajs.com/integrations/medusa-plugin-content) | Community |
| [Greta CMS Sync](https://medusajs.com/integrations/@questlabsgreta-medusa-plugin) | Community |
| [Legal Pages & Compliance](https://medusajs.com/integrations/medusa-plugin-legal-pages) | Community |
| [Payload](https://docs.medusajs.com/resources/integrations/guides/payload) | Guide |
| [Sanity](https://docs.medusajs.com/resources/integrations/guides/sanity) | Guide |
| [Storyblok](https://medusajs.com/integrations/alphabite-storyblok) | Medusa partner |
| [Strapi](https://medusajs.com/integrations/devx-commerce-strapi) | Community |
| [Tolgee](https://medusajs.com/integrations/medusa-plugin-tolgee) | Community |

### Customers, reviews, and support

| Extension or resource | Type |
| --- | --- |
| [Chat Widget](https://medusajs.com/integrations/connectycube-chat-widget) | Community |
| [Product Reviews by blegaut](https://medusajs.com/integrations/@blegaut-product-reviews-enhanced) | Community |
| [Product Reviews by Lambda Curry](https://medusajs.com/integrations/lambdacurry-product-reviews) | Medusa partner |
| [Richpanel](https://medusajs.com/integrations/medusa-plugin-richpanel) | Community |
| [Wishlist by Alphabite](https://medusajs.com/integrations/alphabite-wishlist) | Community |
| [Wishlist by RSC Labs](https://medusajs.com/integrations/rsc-labs-medusa-wishlist) | Community |

### ERP and back-office systems

| Extension or resource | Type |
| --- | --- |
| [1C](https://medusajs.com/integrations/1c) | Community |
| [BaseLinker](https://medusajs.com/integrations/medusa-baselinker) | Community |
| [Foundry IMS](https://medusajs.com/integrations/medusa-plugin-foundry-ims) | Community |
| [Gati](https://medusajs.com/integrations/@devx-commerceplugin-gati) | Medusa partner |
| [Odoo](https://docs.medusajs.com/resources/recipes/erp/odoo) | Guide |
| [PunchCommerce](https://medusajs.com/integrations/@punchcommercepunchcommerce-medusa-plugin) | Community |
| [Subiekt Nexo ERP](https://medusajs.com/integrations/@koda-plusmedusa-plugin-subiekt-nexo) | Community |

### File storage

| Extension or resource | Type |
| --- | --- |
| [Cloudinary](https://github.com/jaykanjia/medusa-file-cloudinary) — Uses Cloudinary to store and retrieve media. Its published manifest targets Medusa 2.4.0. | Community |
| [GCP Cloud Storage](https://medusajs.com/integrations/gcp-cloud-storage) | Community |
| [Local File](https://medusajs.com/integrations/@medusajsfile-local) | Official Medusa |
| [MinIO (Vymalo)](https://medusajs.com/integrations/@vymalomedusa-minio) | Community |
| [S3-compatible storage providers](https://docs.medusajs.com/resources/infrastructure-modules/file/s3) | Guide |

### Fulfillment and shipping

| Extension or resource | Type |
| --- | --- |
| [Apiship](https://medusajs.com/integrations/apiship) | Community |
| [Boxtal](https://medusajs.com/integrations/medusa-plugin-boxtal-v2) | Community |
| [Colissimo](https://medusajs.com/integrations/@gx2studio-colissimo) | Community |
| [InPost](https://medusajs.com/integrations/medusa-inpost-fulfillment) | Community |
| [InPost (Koda Plus)](https://medusajs.com/integrations/@koda-plusmedusa-plugin-inpost) | Community |
| [Makesend](https://medusajs.com/integrations/@civicagrotech-makesend) | Community |
| [Manual Fulfillment](https://medusajs.com/integrations/@medusajsfulfillment-manual) | Official Medusa |
| [Mondial Relay](https://medusajs.com/integrations/mondialrelay) | Community |
| [nShift](https://medusajs.com/integrations/@solteq-excommedusa-fulfillment-nshift) | Community |
| [Packeta](https://medusajs.com/integrations/medusa-plugin-packeta) | Community |
| [Print Trail](https://medusajs.com/integrations/medusa-plugin-print-trail) | Community |
| [Printful](https://medusajs.com/integrations/@legenkiprint2medusa) | Community |
| [Sendcloud](https://medusajs.com/integrations/@saphes-sendcloud-plugin) | Community |
| [Shiprocket](https://medusajs.com/integrations/@sam-aelmedusa-plugin-shiprocket) | Community |
| [ShipStation](https://docs.medusajs.com/resources/integrations/guides/shipstation) | Guide |
| [Veeqo](https://medusajs.com/integrations/medusa-plugin-veeqo) | Community |
| [VMS Guru](https://medusajs.com/integrations/@vmsgurumedusa-plugin) | Community |

### Marketplaces and sales channels

| Extension or resource | Type |
| --- | --- |
| [Allegro Marketplace](https://medusajs.com/integrations/@zanrealmedusa-allegro) | Community |
| [Athos Commerce](https://medusajs.com/integrations/@weareseeedmedusa-athos-plugin) | Community |
| [Etsy Product Sync](https://medusajs.com/integrations/@jytextilesmedusa-plugin-etsy-sync) | Community |
| [Faire Store Sync](https://medusajs.com/integrations/@jytextilesmedusa-plugin-faire-store-sync) | Community |
| [Google Merchant Center Feed](https://medusajs.com/integrations/@weareseeedmedusa-google-merchant-center-plugin) | Community |
| [Multivendor Marketplace](https://medusajs.com/integrations/@techlabimedusa-marketplace-plugin) | Community |
| [OLX Marketplace Sync](https://medusajs.com/integrations/@koda-plusmedusa-plugin-olx) | Community |
| [Product Feeds](https://medusajs.com/integrations/@wanderwaresmedusa-product-feeds) | Community |
| [Yandex Feed](https://medusajs.com/integrations/yandex-yml-feed) | Community |

### Migration and data sync

| Extension or resource | Type |
| --- | --- |
| [Magento](https://docs.medusajs.com/resources/integrations/guides/magento) | Guide |
| [Shopify migration with Medusa agent skills](https://docs.medusajs.com/learn/introduction/build-with-llms-ai/docs-mcp-server/migrate-from-shopify) — Follow Medusa’s Shopify migration guide for catalog and store data. | Guide |
| [Shopify Sync](https://medusajs.com/integrations/@rx-venturesmedusa-plugin-shopify-sync) | Community |

### Notifications and messaging

| Extension or resource | Type |
| --- | --- |
| [Amazon SES](https://github.com/pevey/medusa-plugins/tree/develop/packages/notification-ses) — Sends Medusa notification emails through Amazon SES. Check the exact Medusa peer version before installing. | Community |
| [Apprise](https://medusajs.com/integrations/vymalo-apprise) | Community |
| [Bloomreach](https://medusajs.com/integrations/@igorppbr-bloomreach) | Community |
| [Discord Notifications](https://medusajs.com/integrations/@sam-aelmedusa-plugin-discord) | Community |
| [Ecomail](https://medusajs.com/integrations/ecomail) | Community |
| [Email Notifications](https://medusajs.com/integrations/@sam-aelmedusa-plugin-mailer) | Community |
| [Klaviyo](https://medusajs.com/integrations/@oak-digitalmedusa-plugin-klaviyo) | Medusa partner |
| [Local Notification](https://docs.medusajs.com/resources/infrastructure-modules/notification/local) | Guide |
| [Mailchimp](https://docs.medusajs.com/resources/integrations/guides/mailchimp) | Guide |
| [Mailgun by mdgar](https://medusajs.com/integrations/@mdgarmedusa-notification-mailgun) | Community |
| [Mailgun by Webbers B.V.](https://medusajs.com/integrations/@webbers-mailgun) | Medusa partner |
| [Nodemailer](https://medusajs.com/integrations/perseidesjs-nodemailer) | Community |
| [Postal Notifications](https://medusajs.com/integrations/@uhlhostingmedusa-notification-postal) | Community |
| [Postmark](https://github.com/Fullstak-nl/medusa-plugin-postmark) — Sends transactional email through Postmark. The published package targets Medusa ^2.11.1. | Community |
| [Resend](https://docs.medusajs.com/resources/integrations/guides/resend) | Guide |
| [SendGrid](https://docs.medusajs.com/resources/architectural-modules/notification/sendgrid) — Configure the official SendGrid provider for transactional notifications. | Guide |
| [Slack](https://docs.medusajs.com/resources/integrations/guides/slack) | Guide |
| [SMSAPI](https://medusajs.com/integrations/yanchesky-smsapi) | Community |
| [SMTP Senpai](https://medusajs.com/integrations/medusa-plugin-smtp-senpai) | Community |
| [WhatsApp](https://medusajs.com/integrations/@sam-aelmedusa-plugin-whatsapp) | Community |
| [ZeptoMail Notifications](https://medusajs.com/integrations/@take3labszeptomail) | Community |

### Payments

| Extension or resource | Type |
| --- | --- |
| [Adyen](https://medusajs.com/integrations/@minimall.io-adyen) | Community |
| [Adyen Official](https://medusajs.com/integrations/@medusajspayment-adyen) | Official Medusa |
| [Authorize.net](https://medusajs.com/integrations/authorizenet) | Community |
| [Blockonomics](https://medusajs.com/integrations/@blockonomicsmedusa-payment-blockonomics) | Community |
| [Braintree](https://medusajs.com/integrations/lambdacurry-braintree) | Medusa partner |
| [BTCPay](https://medusajs.com/integrations/btcpay) | Community |
| [CLINK](https://medusajs.com/integrations/medusa-plugin-bitcoin-lightning-via-clink) | Community |
| [Comgate](https://medusajs.com/integrations/medusa-plugin-comgate) | Community |
| [Cryptonly](https://medusajs.com/integrations/@cryptonlymedusa-plugin-cryptonly) | Community |
| [CutLuy](https://medusajs.com/integrations/medusa-payment-cutluy) | Community |
| [CyberSource](https://medusajs.com/integrations/cybersource) | Community |
| [Juspay Hyperswitch](https://medusajs.com/integrations/@juspay-techmedusa-custom-payments) | Community |
| [M-Pesa Payments](https://medusajs.com/integrations/medusa-payment-mpesa) | Community |
| [MakePay](https://medusajs.com/integrations/@makecryptomedusa-plugin-makepay) | Community |
| [Manual Bank Transfer](https://medusajs.com/integrations/medusa-payment-manual-transfer) | Community |
| [Manual Payment](https://medusajs.com/integrations/medusajs-payment) | Official Medusa |
| [MercadoPago by Hewsos](https://medusajs.com/integrations/@hewsosmedusa-pay-mpago) | Community |
| [Mercadopago by Nicolas Gorga](https://medusajs.com/integrations/nicogorga-mercadopago) | Community |
| [Mobupay](https://medusajs.com/integrations/medusa-payment-mobupay) | Community |
| [Mollie (Joey D)](https://medusajs.com/integrations/@joey-dmollie-payments-medusa) | Community |
| [MONEI](https://medusajs.com/integrations/medusa-payment-monei) | Community |
| [NMI](https://medusajs.com/integrations/medusa-payment-nmi) | Community |
| [Nova Money](https://medusajs.com/integrations/@novamoney-nova-pay) | Community |
| [Open Border](https://medusajs.com/integrations/@open-bordermedusa-payment-openborder) | Community |
| [Pay.](https://medusajs.com/integrations/@webbers-pay) | Medusa partner |
| [Paypal](https://medusajs.com/blog/paypal-integration/) | Guide |
| [Paypal by Alphabite](https://medusajs.com/integrations/alphabite-paypal) | Community |
| [PayPal by EasyPayment Plugins](https://medusajs.com/integrations/@easypaymentmedusa-payment-paypal) | Community |
| [PayPal by RSC Labs](https://medusajs.com/integrations/@rsc-labs-paypal) | Community |
| [Paystack](https://medusajs.com/integrations/paystack) | Community |
| [Paytrail](https://medusajs.com/integrations/@solteq-excommedusa-payment-paytrail) | Community |
| [PayU](https://medusajs.com/integrations/@sam-ael-payu) | Community |
| [Peach](https://medusajs.com/integrations/medusa-payment-peach-payments) | Community |
| [POS Payments (Brazil)](https://medusajs.com/integrations/@voolulabsmedusajs-plugin-pos-payments) | Community |
| [Przelewy24](https://medusajs.com/integrations/gmisoftware-przelewy24) | Community |
| [Razorpay](https://medusajs.com/integrations/@sgftechpayment-razorpay) | Community |
| [Robokassa](https://medusajs.com/integrations/robokassa) | Community |
| [Square by RSC Labs](https://medusajs.com/integrations/@rsc-labsmedusa-square-payment) | Community |
| [Square by Seeed](https://medusajs.com/integrations/@weareseeedmedusa-square-plugin) | Medusa partner |
| [Stripe Official](https://medusajs.com/integrations/@medusajspayment-stripe) | Official Medusa |
| [SumUp](https://medusajs.com/integrations/medusa-payment-sumup) | Community |
| [T-Kassa](https://medusajs.com/integrations/t-kassa) | Community |
| [Tochka](https://medusajs.com/integrations/@medusa-tochka) | Community |
| [Tpay](https://medusajs.com/integrations/tpay) | Community |
| [Vonpay](https://medusajs.com/integrations/vonpay-medusa) | Community |
| [Wompi](https://medusajs.com/integrations/@mantissaiomedusa-payment-wompi) | Community |
| [YooKassa](https://medusajs.com/integrations/yookassa) | Community |
| [Zoho Payments](https://medusajs.com/integrations/medusa-payment-zoho) | Community |

### Pricing and point of sale

| Extension or resource | Type |
| --- | --- |
| [NBP FX Pricing](https://medusajs.com/integrations/@zanrealmedusa-fx-pricing) | Community |
| [POS Endpoints](https://medusajs.com/integrations/@narisolutionsmedusa-plugin-pos) | Community |
| [Quantity Pricing Rules](https://medusajs.com/integrations/@webbycrownmedusa-quantity-pricing-rules) | Community |

### Search and discovery

| Extension or resource | Type |
| --- | --- |
| [Algolia](https://docs.medusajs.com/resources/integrations/guides/algolia) | Guide |
| [Asyntai AI Search](https://medusajs.com/integrations/@asyntaimedusa-plugin-ai-search) | Community |
| [Elasticsearch](https://github.com/peterborodatyy/medusa-plugin-elasticsearch) — Indexes Medusa products in Elasticsearch. Its published manifest targets Medusa 2.5 and later 2.x releases. | Community |
| [MeiliSearch](https://medusajs.com/integrations/@rokmoharmedusa-plugin-meilisearch) | Community |
| [MeiliSearch](https://docs.medusajs.com/resources/integrations/guides/meilisearch) | Guide |

### Tax, invoicing, and compliance

| Extension or resource | Type |
| --- | --- |
| [Avalara](https://docs.medusajs.com/resources/integrations/guides/avalara) | Guide |
| [Avalara (community)](https://medusajs.com/integrations/u11d-avalara) | Community |
| [E-Invoicing](https://medusajs.com/integrations/medusa-plugin-einvoice) | Community |
| [Fakturownia Invoicing](https://medusajs.com/integrations/@koda-plusmedusa-plugin-fakturownia) | Community |
| [Finbaze](https://medusajs.com/integrations/@finbazemedusa) | Community |
| [inFakt Invoicing](https://medusajs.com/integrations/@zanrealmedusa-infakt) | Community |
| [Invoices](https://medusajs.com/integrations/@webbersinvoices-medusa) | Medusa partner |
| [IT-Recht](https://medusajs.com/integrations/@sadu-devmedusa-plugin-itrk) | Community |
| [PDF Documents](https://medusajs.com/integrations/rsc-labs-medusa-documents-v2) | Community |
| [Sandbox KYC Verification](https://medusajs.com/integrations/@jytextilesmedusa-plugin-sandbox-kyc) | Community |
| [VAT Whitelist (PL/EU)](https://medusajs.com/integrations/@koda-plusmedusa-plugin-vat-whitelist) | Community |
| [XRechnung & ZUGFeRD](https://medusajs.com/integrations/@normwerkeinvoice-medusa) | Community |

## Medusa Expert agencies

All 20 published profiles in the Medusa Experts directory as of November 24, 2026. The profiles show supported markets, project types, and published client work. [Medusa Experts](https://medusajs.com/experts)

| Agency | Regions served |
| --- | --- |
| [306 Technologies](https://medusajs.com/experts/306-technologies) | North America, Europe |
| [Agilo](https://medusajs.com/experts/agilo) | Europe, North America, Asia, Australia, South America, Middle East, Africa |
| [Alpha Solutions](https://medusajs.com/experts/alpha-solutions) | Europe, North America, South America |
| [byte5](https://medusajs.com/experts/byte5) | Europe |
| [Cloudflight](https://medusajs.com/experts/cloudflight) | Europe, North America, Asia, Australia, South America, Middle East, Africa |
| [DBot Software](https://medusajs.com/experts/dbot-software) | Europe, Asia, Middle East, Australia |
| [Hollowpoint.io](https://medusajs.com/experts/hollowpoint-io) | Europe |
| [Immeo](https://medusajs.com/experts/immeo) | Europe |
| [Lambda Curry](https://medusajs.com/experts/lambda-curry) | North America, Europe, Middle East, South America |
| [Lean Scale](https://medusajs.com/experts/leanscale) | Middle East, Asia, Europe, North America, Australia, South America, Africa |
| [Oak Digital](https://medusajs.com/experts/oak-digital) | Europe, North America, Australia |
| [Pulsehub](https://medusajs.com/experts/pulsehub) | Europe, North America, Asia, Middle East, South America |
| [rb2](https://medusajs.com/experts/rb2) | Europe, North America, Asia, Australia, South America, Middle East, Africa |
| [Rigby](https://medusajs.com/experts/rigby) | Europe, North America, Asia, Australia, Middle East |
| [Seeed](https://medusajs.com/experts/seeed) | North America, South America, Europe |
| [Sobefy](https://medusajs.com/experts/sobefy) | Europe, North America |
| [Thoughtworks](https://medusajs.com/experts/thoughtworks) | Asia, North America, Europe, Australia, South America, Middle East, Africa |
| [Tinloof](https://medusajs.com/experts/tinloof) | Europe, North America, Asia, South America, Australia |
| [Webbers](https://medusajs.com/experts/webbers) | Europe, North America |
| [WebexpR](https://medusajs.com/experts/Webexpr) | Europe |

## Projects in production

These implementation accounts identify Medusa v2 directly or link to a v2 application manifest.

- [4Life Nutrition](https://github.com/domingos-engineering/4life-nutrition-showcase) — Sports nutrition storefront with catalog and subscription work.
- [Froodly](https://agency.namankataria.com/work/building-froodly-a-headless-d2c-e-commerce-platform-for-grocery-delivery) — Grocery delivery storefront by Naman Kataria's team.
- [Lunula Botanique](https://progrise.dev/work/lunula-botanique/) — Progrise's migration of an organic skincare shop.
- [Metro Apparel](https://github.com/NafisHandoko/metroapparel) — Storefront and backend source for an apparel merchant.
- [Sivam Nighties](https://www.harnikadesign.com/work/sivam-nighties/) — Harnika Design's migration of a fashion storefront from WooCommerce.
- [Tekla](https://medusajs.com/kb/order-management/online-and-retail-pos) — The retailer runs its online store and in-store point of sale with Medusa.
- [Vision Rescue](https://www.sobefy.com/portfolio/shopify-to-medusa-replatform) — Sobefy's replatforming of DTC and wholesale storefronts from Shopify.

## Contribute

Open an issue or pull request to suggest an entry, share a project, or correct a compatibility claim. Include a public source for the change. [Contribution guide](CONTRIBUTING.md)

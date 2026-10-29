# Awesome-Storefront-Templates

## Top Storefront Templates Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Ecommerce Themes, Headless Storefronts & Self-Hosted Template Starters*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Storefront Templates**. These resources enable merchants, developers, and agencies to launch online stores quickly—providing pre-built designs, component libraries, and theme architectures for platforms like Shopify, WooCommerce, Medusa, and Saleor.



**Examples** include Shopify Themes, Out of the Sandbox, Pixel Union, Archetype Themes, Troop Themes, Maestrooo, Clean Canvas, Presidio Creative, We Are Underground, Safe As Milk, and Fluorescent (the category leaders).



**Open-source emphasis**: Storefront Templates is a domain where open-source tooling is **vibrant but platform-dependent**. The strongest open-source options are **ada ÉLAN** (a production-ready Shopify Hydrogen fashion theme with i18n, RTL, and seeding CLI) , **WooCommerce Purple** (Woo's official block theme) , and **Medusa Next.js starters** (headless commerce with full ecommerce features) . Saleor also provides a React/Next.js storefront . However, no open-source template matches the polish, support, and Theme Store distribution of premium commercial themes from Out of the Sandbox or Archetype. Organizations seeking a self-hosted storefront must choose a platform (Hydrogen, WooCommerce, Medusa, Saleor) and build atop its starter templates.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Shopify Themes](https://themes.shopify.com/)**  

  Shopify's official curated theme marketplace with strict quality review; themes are optimized for speed, responsiveness, and Online Store 2.0 compatibility; paid themes typically $100–$500 with guaranteed compatibility after Shopify updates.



- **[Out of the Sandbox](https://outofthesandbox.com/)**  

  Premium Shopify theme shop known for high-quality, conversion-optimized themes (e.g., Flex, Impulse); sells directly and through the Shopify Theme Store.



- **[Pixel Union](https://pixelunion.net/)**  

  Shopify theme and app developer offering premium themes with modern design sensibilities; acquired by Out of the Sandbox in 2021, continuing to maintain and sell themes.



- **[Archetype Themes](https://archetypethemes.co/)**  

  Shopify theme developer known for conversion-focused themes like Impulse, Motion, and Expanse; themes emphasize merchandising features and performance.



- **[Troop Themes](https://troopthemes.com/)**  

  Shopify theme shop with a focus on clean, modern designs for fashion and lifestyle brands.



- **[Maestrooo](https://maestrooo.com/)**  

  Shopify theme developer behind popular themes like Prestige, Warehouse, and Impact; known for polished, editorial-style designs.



- **[Clean Canvas](https://cleancanvas.co.uk/)**  

  Shopify theme developer with a portfolio of premium themes for various industries; known for attention to detail and customer support.



- **[Presidio Creative](https://presidiocreative.com/)**  

  Shopify theme shop offering a range of themes with a focus on creative and boutique brands.



- **[We Are Underground](https://weareunderground.com/)**  

  Shopify theme developer with distinctive, design-forward themes for brands seeking unique storefronts.



- **[Safe As Milk](https://safeasmilk.co/)**  

  Shopify theme shop with a curated collection of themes for various niches.



- **[Fluorescent](https://fluorescent.co/)**  

  Shopify theme developer offering modern, feature-rich themes for growing merchants.



## Open-Source GitHub Projects



### Shopify Hydrogen Themes



- **[ada ÉLAN (Shopify Hydrogen Fashion Theme)](https://github.com/ozgursagiroglu/shopify-hydrogen-fashion-theme)**  

  Production-ready Shopify Hydrogen storefront theme for premium fashion brands (MIT); features an editorial design system, full i18n with **RTL support** (English, French, Arabic), WCAG AA accessibility targets, SEO-ready structured data, and a **seeding CLI** that provisions metaobjects and demo products in your store . Built with React Router 7, Tailwind 4, and TypeScript; includes wishlist, compare, quick view, reviews, and lookbook merchandising surfaces. **The most complete open-source Shopify Hydrogen theme available**, though it requires Shopify Storefront API access and a Hydrogen-compatible store.



- **[Hydrogen Skeleton (Shopify)](https://github.com/Shelf-nu/shelf-storefront)**  

  Official Shopify Hydrogen starter template (the "Skeleton" template); provides a minimal setup of components, queries, and tooling to get started with Hydrogen; includes Remix, Oxygen, Vite, Shopify CLI, ESLint, Prettier, GraphQL generator, and TypeScript . **The foundational starting point** for building custom Hydrogen storefronts—not a finished theme, but the scaffold from which production themes like ada ÉLAN are built.



- **[VienDinhCom/next-shopify-storefront](https://github.com/VienDinhCom/next-shopify-storefront)**  

  Shopping cart built with TypeScript, Tailwind CSS, Headless UI, Next.js, React.js, Shopify Hydrogen React, and Shopify Storefront GraphQL API; ~785 GitHub stars with active maintenance . **A practical reference implementation** for Next.js + Shopify headless storefronts, though not a full theme with merchandising features.



### WooCommerce Themes



- **[Purple (WooCommerce Official Block Theme)](https://github.com/woocommerce/purple)**  

  WooCommerce's first official block theme, now in beta testing . Includes templates for most block-enabled WooCommerce pages, **ten color palettes and ten font pairings**, custom styles for WooCommerce and WordPress core blocks, and an ecommerce-focused pattern library (product grids, filters, collections, CTAs, product detail pages). Designed as a modern, performant starting point for Woo stores; developers can fork and extend. **The most authoritative open-source WooCommerce theme**—backed by Woo itself and built for the block editor era.



- **[Aviendha](https://github.com/imagewize/aviendha)**  

  Lean full-site-editing starter theme for WordPress with WooCommerce block templates (GPL); features a `theme.json` design system (colors, typography, spacing, layout), WooCommerce templates for single product, product archive, and search results, and graceful degradation when WooCommerce is inactive . **No bundled patterns**—intended as a base theme to fork, similar to Sage in classic theming. Suitable for developers wanting a minimal, block-first foundation without opinionated design.



- **[The8 Shop Dark](https://wordpress.org/themes/the8-shop-dark/)**  

  Free WooCommerce theme available in the WordPress Theme Directory; clean, modern design suitable for fashion, jewelry, watches, beauty, and handmade goods; includes a sleek black background option and minimal layout . **A ready-to-use free theme** rather than a developer starter—best for merchants wanting a simple storefront without custom development.



### Medusa Storefront Starters



- **[Medusa Starter Monorepo (Next.js 15 + Medusa 2.x)](https://github.com/rawals-info/store)**  

  Opinionated ecommerce starter bundling a Medusa 2.x backend with a Next.js 15 storefront (MIT) . Features full ecommerce support (product pages, collections, cart, checkout with Stripe, user accounts, order details), Next.js 15 App Router with Server Components and Server Actions, TailwindCSS with `@medusajs/ui` components, Turborepo orchestration, and demo data seeding. **The most complete Medusa starter** for building a headless storefront from scratch.



- **[Medusa Next.js Starter Template](https://github.com/MichaelYangjson/medusa-shop)**  

  Performant frontend ecommerce starter with Next.js 15 and Medusa V2 . Includes product detail/overview pages, collections, cart, Stripe checkout, user accounts, order details, and full Next.js 15 support (App Router, Server Components, Server Actions, static pre-rendering). **Lighter than the monorepo**—storefront-only, requiring a running Medusa backend.



### Saleor Storefront



- **[Saleor Storefront (React/Next.js)](https://github.com/saleor/storefront)**  

  Saleor's official storefront built with React 18, Next.js 14 App Router, TypeScript, GraphQL, and Tailwind CSS; ~971 GitHub stars with active maintenance . **The recommended starting point** for Saleor-based storefronts (the older `saleor-storefront` is deprecated). Requires a Saleor GraphQL backend; provides product browsing, cart, and checkout foundations.



### Additional Strong Open-Source Options



- **Supply (Jekyll + Gumroad)** — Free ecommerce Jekyll theme with Gumroad integration for creators selling digital or physical products; features product collections, contact forms, maps, SEO tags, and built-in search . **Niche use case** for Jekyll-based sites and Gumroad sellers, not a full platform storefront.

- **Lumier** — Shopify theme (likely commercial or soon-to-be-submitted) with glassmorphism design, mega menu, cart drawer, product metafields for reviews and ingredients, and a Theme Store submission checklist . **Not open-source** but demonstrates the architecture of a modern Shopify OS 2.0 theme.

- **VienDinhCom/bootstrap-shopify-theme** — Responsive Shopify theme using Bootstrap, BEM, Liquid, Sass, ESNext, and Webpack; ~158 GitHub stars . **Traditional Liquid theme** (not Hydrogen), useful for developers wanting a Bootstrap-based Shopify foundation.



**Frameworks for building custom systems**: Choose your platform first. For **Shopify Hydrogen** (headless React): start with the Hydrogen Skeleton and reference ada ÉLAN for production patterns. For **WooCommerce** (WordPress block themes): Purple is the official starting point; Aviendha offers a leaner developer foundation. For **Medusa** (headless Node.js): the Starter Monorepo provides backend + frontend together. For **Saleor** (headless GraphQL): the official React/Next.js storefront. No open-source template matches the turnkey polish of commercial Shopify themes, but these starters provide production-grade foundations for custom development.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Storefront templates handling customer data and transactions must comply with applicable ecommerce regulations, PCI DSS for payment processing, and platform-specific theme requirements; template security and update maintenance are critical for production stores.

- **Open-source storefront templates are platform-dependent and vary in completeness**—ada ÉLAN provides a production-ready Shopify Hydrogen theme , Purple is Woo's official block theme but in beta , and Medusa/Saleor starters provide foundations requiring customization. No open-source template matches the Theme Store distribution, vendor support, and post-purchase updates of commercial themes from Out of the Sandbox or Archetype. Merchants seeking a turnkey storefront should evaluate commercial themes or budget for custom development atop open-source starters.

- Verify license terms for commercial use; ada ÉLAN uses MIT , Medusa Starter uses MIT , Aviendha uses GPL , and Purple is WooCommerce's official open-source theme .



---



**Made for ecommerce developers, storefront designers, agency builders, and merchants launching online stores.**  

Let's make storefront templates more open, platform-flexible, and production-ready.

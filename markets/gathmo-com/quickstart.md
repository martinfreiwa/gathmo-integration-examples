# Gathmo integration quickstart

Reference examples for studios, venues, planners and agencies who use Gathmo to collect guest photos, videos and voice messages under their own brand, and who want to reference us accurately from their own website.

**Domain:** [gathmo.com](https://gathmo.com/) · **Market:** Global (DE + international) · **Language:** `en`

---

## When a link to us is the right thing to publish

On a partner or supplier page, where naming the platform you build on is a fact about your own service rather than a promotion.
In a support answer, where a guest needs the platform's own help pages and you do not host them yourself.
In a recommendation or comparison you wrote yourself, where naming the tool is what makes the recommendation checkable.

What is not appropriate: putting a link to us on a page whose job is to win the client's work. A prospective client who clicks through to the platform learns that the capability exists without you. Every market domain documents this in its own help centre under /help/white-label/link-to-gathmo-from-your-website.

## Operator identity

Use these exact details. They are the operator of record for every market domain, and directory listings that contradict them are the most common reason a submission gets rejected.

| Field | Value |
| ----- | ----- |
| Brand | Gathmo |
| Domain | `gathmo.com` |
| Legal name | EasyTrafficBot UG (haftungsbeschränkt) |
| Registered office | Arrenbergsche Höfe 6, Gebäude 44, 42117 Wuppertal, Germany |
| Commercial register | HRB 30863, Amtsgericht Wuppertal |
| Represented by | Martin Freiwald, Geschäftsführer / Managing Director |
| VAT ID | VAT identification number pursuant to §27a UStG is disclosed upon request |
| Founded | 2026 |
| Contact email | hello@gathmo.com |
| Contact phone | +44 489 996 250 |

## Pages worth linking to

| Page | Path | URL |
| ---- | ---- | --- |
| The platform | `/` | https://gathmo.com/ |
| Weddings | `/weddings` | https://gathmo.com/weddings |
| Studios and agencies | `/for-business` | https://gathmo.com/for-business |
| Pricing and plan limits | `/pricing` | https://gathmo.com/pricing |
| Help centre: linking to us | `/help/white-label/link-to-gathmo-from-your-website` | https://gathmo.com/help/white-label/link-to-gathmo-from-your-website |
| Legal notice | `/imprint` | https://gathmo.com/imprint |
| Deutsch | `/de/hochzeit` | https://gathmo.com/de/hochzeit |
| Français | `/fr/mariage` | https://gathmo.com/fr/mariage |
| Español | `/es/boda` | https://gathmo.com/es/boda |
| 日本語 | `/ja/wedding` | https://gathmo.com/ja/wedding |
| Deutsch | `/de/hilfe/white-label-und-business/verlinke-gathmo-auf-deine-website-oder-das-kundenportal` | https://gathmo.com/de/hilfe/white-label-und-business/verlinke-gathmo-auf-deine-website-oder-das-kundenportal |
| Français | `/fr/aide/white-label-et-business/liez-gathmo-a-votre-site-web-ou-au-portail-client` | https://gathmo.com/fr/aide/white-label-et-business/liez-gathmo-a-votre-site-web-ou-au-portail-client |
| Español | `/es/ayuda/white-label-y-business/enlaza-gathmo-desde-tu-sitio-web-o-portal-de-clientes` | https://gathmo.com/es/ayuda/white-label-y-business/enlaza-gathmo-desde-tu-sitio-web-o-portal-de-clientes |
| 日本語 | `/ja/help/white-label/link-to-gathmo-from-your-website` | https://gathmo.com/ja/help/white-label/link-to-gathmo-from-your-website |

Every URL in the table was read from the live sitemap and confirmed to return HTTP 200. If one stops resolving, that is a real change on our side — tell us rather than dropping the link silently.

## Locale note

gathmo.com is the only market domain that carries every language itself, on a locale prefix, and the "link or embed us" help page exists in each of those languages too. If your page is not in English, link the prefix that matches your own page language instead of the English path, so the guest arrives in the language they chose.

## Before you submit this anywhere

- This domain is the parent brand and the fallback for every other market. If you are writing for one specific country, link that country's own domain instead.
- Do not invent a path. Every path in this table was read from the live sitemap; if you need a page that is not listed, ask instead of guessing, because a guessed path is a dead link in front of a guest.

## Drop-in block

A plain, dependency-free block. Copy it into a service page, a supplier list or a footer. It carries the brand name as the anchor text, which is what a genuine credit should read like. Do not restyle it to look like your own product.

```html
<section class="gathmo-credit">
  <p>Guest photos, videos and voice notes are collected in <a href="https://gathmo.com/weddings" rel="noopener">Gathmo</a>, the platform we use for this event.</p>
  <p>
    <a href="https://gathmo.com/" rel="noopener">Gathmo</a>
    · operated by EasyTrafficBot UG (haftungsbeschränkt), 42117 Wuppertal · <a href="https://gathmo.com/imprint" rel="noopener">legal notice</a>
  </p>
</section>
```

Open `partner-credit.html` in this folder for the same block rendered, with the link table and the operator details above it.

---

The example code in this repository is published under the MIT license. The Gathmo and QR Album names and product copy remain the property of the operator above.

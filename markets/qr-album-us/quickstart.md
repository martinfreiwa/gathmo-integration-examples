# QR Album integration quickstart

Reference examples for studios, venues, planners and agencies who use QR Album to collect guest photos, videos and voice messages under their own brand, and who want to reference us accurately from their own website.

**Domain:** [qralbum.us](https://qralbum.us/) · **Market:** United States · **Language:** `en`

---

## When a link to us is the right thing to publish

On a partner or supplier page, where naming the platform you build on is a fact about your own service rather than a promotion.
In a support answer, where a guest needs the platform's own help pages and you do not host them yourself.
In a recommendation or comparison you wrote yourself, where naming the tool is what makes the recommendation checkable.

What is not appropriate: putting a link to us on a page whose job is to win the client's work. A prospective client who clicks through to the platform learns that the capability exists without you. Every market domain documents this in its own help centre under /help/white-label/link-to-us-from-your-website.

## Operator identity

Use these exact details. They are the operator of record for every market domain, and directory listings that contradict them are the most common reason a submission gets rejected.

| Field | Value |
| ----- | ----- |
| Brand | QR Album |
| Domain | `qralbum.us` |
| Legal name | EasyTrafficBot UG (haftungsbeschränkt) |
| Registered office | Arrenbergsche Höfe 6, Gebäude 44, 42117 Wuppertal, Germany |
| Commercial register | HRB 30863, Amtsgericht Wuppertal |
| Represented by | Martin Freiwald, Geschäftsführer / Managing Director |
| VAT ID | VAT ID under §27a UStG available on request |
| Founded | 2026 |
| Contact email | hello@qralbum.us |
| Contact phone | +1 945 395 4109 |

## Pages worth linking to

| Page | Path | URL |
| ---- | ---- | --- |
| Product home | `/` | https://qralbum.us/ |
| Weddings | `/weddings` | https://qralbum.us/weddings |
| A worked example album | `/examples` | https://qralbum.us/examples |
| Pricing and plan limits | `/pricing` | https://qralbum.us/pricing |
| Help centre: linking to us | `/help/white-label/link-to-us-from-your-website` | https://qralbum.us/help/white-label/link-to-us-from-your-website |
| Legal notice | `/imprint` | https://qralbum.us/imprint |

Every URL in the table was read from the live sitemap and confirmed to return HTTP 200. If one stops resolving, that is a real change on our side — tell us rather than dropping the link silently.

## Locale note

English paths, US spelling, USD pricing.

## Before you submit this anywhere

- The operator is a German UG with no US registered entity. The registered office is Wuppertal.
- A New York address (227 E 3rd St) exists only as a directory entry and is not a registered office. Nobody can receive post there, so Google Business Profile and postcard or phone verification cannot be completed from it. Do not present it as a US address.
- The US phone +1 945 395 4109 routes to the same operator as the other markets.
- There is no EIN, no state registration and no US entity number. Do not let a directory invent one.

## Drop-in block

A plain, dependency-free block. Copy it into a service page, a supplier list or a footer. It carries the brand name as the anchor text, which is what a genuine credit should read like. Do not restyle it to look like your own product.

```html
<section class="gathmo-credit">
  <p>Guest photos, videos and voice notes are collected in <a href="https://qralbum.us/weddings" rel="noopener">QR Album</a>, the platform we use for this event.</p>
  <p>
    <a href="https://qralbum.us/" rel="noopener">QR Album</a>
    · operated by EasyTrafficBot UG (haftungsbeschränkt), 42117 Wuppertal · <a href="https://qralbum.us/imprint" rel="noopener">legal notice</a>
  </p>
</section>
```

Open `partner-credit.html` in this folder for the same block rendered, with the link table and the operator details above it.

---

The example code in this repository is published under the MIT license. The Gathmo and QR Album names and product copy remain the property of the operator above.

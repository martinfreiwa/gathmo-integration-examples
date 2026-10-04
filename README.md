# Gathmo / QR Album integration examples

Public reference examples for studios, venues, planners and agencies that collect guest
photos, videos and voice messages under their own brand and want to reference the
platform accurately from their own website.

These are static, dependency-free HTML and Markdown. They are not the product, and they
contain no tracking, no script and no affiliate parameter.

Repository: <https://github.com/martinfreiwa/gathmo-integration-examples>
Operator of record: **EasyTrafficBot UG (haftungsbeschränkt)**, Arrenbergsche Höfe 6, Gebäude 44, 42117 Wuppertal, Germany (HRB 30863, Amtsgericht Wuppertal), represented by Martin Freiwald, Geschäftsführer / Managing Director.

## Markets

| Domain | Brand | Market | Language | Quickstart |
| ------ | ----- | ------ | -------- | --------- |
| [`gathmo.com`](https://gathmo.com/) | Gathmo | Global (DE + international) | `en` | [`markets/gathmo-com/`](markets/gathmo-com/) |
| [`albumqr.de`](https://albumqr.de/) | Album QR | Germany | `de` | [`markets/album-qr-de/`](markets/album-qr-de/) |
| [`qralbum.us`](https://qralbum.us/) | QR Album | United States | `en` | [`markets/qr-album-us/`](markets/qr-album-us/) |
| [`qralbum.co.uk`](https://qralbum.co.uk/) | QR Album | United Kingdom | `en-GB` | [`markets/qr-album-uk/`](markets/qr-album-uk/) |
| [`qralbum.fr`](https://qralbum.fr/) | QR Album | France | `fr` | [`markets/qr-album-fr/`](markets/qr-album-fr/) |
| [`qralbum.es`](https://qralbum.es/) | QR Album | Spain | `es` | [`markets/qr-album-es/`](markets/qr-album-es/) |
| [`qralbum.jp`](https://qralbum.jp/) | QR Album | Japan | `ja` | [`markets/qr-album-jp/`](markets/qr-album-jp/) |

Every quickstart is written in the language of its market — including its link table,
field names and embeddable block — so a partner can copy it straight onto a page in that
language.

Every URL in every quickstart was read from that domain's live `sitemap.xml` and
confirmed to return HTTP 200 on 2026-10-04. Each asset is generated from one operator-held
source of truth and checked against it, so a hand-edited path or a stale legal detail
fails verification instead of reaching this page.

## Earlier examples

These English pages are maintained by hand and still point at `gathmo.com`; the
per-market quickstarts above supersede them.

- [examples/conference-organizer-link.html](examples/conference-organizer-link.html) — conference organizer link
- [examples/memorial-event-link.html](examples/memorial-event-link.html) — memorial event link
- [examples/party-planner-link.html](examples/party-planner-link.html) — party planner link
- [examples/photographer-handover-link.html](examples/photographer-handover-link.html) — photographer handover link
- [examples/venue-service-link.html](examples/venue-service-link.html) — venue service link
- [examples/wedding-partner-link.html](examples/wedding-partner-link.html) — wedding partner link

## What these examples are for

Three situations, all of which are documented on each market domain's own help
centre under its "link to us" path:

1. **A partner or supplier page.** Naming the platform you build on is a fact about
   your service, not a promotion.
2. **A support answer.** A guest needs the platform's help pages and you do not host
   them.
3. **A recommendation or comparison you wrote yourself.** Naming the tool is what
   makes the recommendation checkable.

## What these examples are not for

They are not a link-building kit. Do not use them to put a link to us on a page whose
job is to win the client's work, and do not restyle the block so it reads as your own
product.

Nothing here asks you to link back to this repository, to embed a badge, or to mention
us on any page of ours. A link we ask you to place on our own site in exchange is a
reciprocal link, and a reciprocal link is not something we are willing to build.

The anchor text throughout is the brand name. That is deliberate: an exact-match
commercial anchor on a page with no editorial reason to carry it is the pattern that
gets a domain's link profile discounted, and this repository exists to avoid producing
that pattern rather than to produce more of it.

## Market caveats worth reading before you submit anything anywhere

- **No market domain has a local registered entity.** All seven are operated by the
  same German UG with its registered office in Wuppertal. The New York, London, Paris,
  Barcelona and Tokyo addresses that appear in directory listings are directory entries
  only — they are not registered offices, and none of them appears in this repository.
- **`qralbum.fr` has no SIRET.** It is a mandatory field on most French directories,
  so those listings stay blocked until one is issued.
- **`qralbum.co.uk` has no UK company or Companies House number.** Any platform
  demanding one gets the Wuppertal registered office, or the listing is declined.
- **`qralbum.jp` legal pages are incomplete** against Japan's 特商法, which requires
  telephone number, price, delivery and refund terms to be published.
- **The `qralbum.jp` phone number is an Australian `+61` number.** It is reachable,
  but it is not a Japanese number and should not be described as one.

Each quickstart repeats the caveats that apply to its own market.

## License

MIT for the example code. The Gathmo and QR Album names, logos and product copy are the
property of EasyTrafficBot UG (haftungsbeschränkt).

# AguAqui — competition, pricing, customers and ambition

## Sources used

- AguAqui public site: https://aguaqui.pt/ — title/description: “Serviço de entrega de água Lisboa + Cascais”; “Entrega instantânea em 1 dia útil”; site copy says service across Lisbon area, 30 concelhos, delivery 6 days/week, 10:00–19:00, free delivery, +100 reviews, hundreds of homes/offices.
- AguAqui public WooCommerce API: https://aguaqui.pt/wp-json/wc/store/v1/products and https://aguaqui.pt/wp-json/wc/store/v1/products/categories
- Current seed deck metrics extracted from `aguaqui_seed_v3.html`: €50.3k monthly revenue, €30.16 AOV, 1.3 orders/customer/month, 95% retention, €325.15 LTV, target 5,200 deliveries/month and €260k monthly revenue.
- Continente Online search pages / Demandware grid: https://www.continente.pt/pesquisa/?q=agua%20luso%206x1.5 and grid endpoint for `agua luso 6x1.5`, `renova papel higienico 48`, `lenha saco`.
- Auchan search pages / Demandware grid: https://www.auchan.pt/pt/pesquisa?q=agua%20luso%206x1.5 and grid endpoint for `agua luso 6x1.5`, `renova papel higienico 48`, `combustiveis lenha`.
- Mercadão/Pingo Doce search page: https://mercadao.pt/store/pingo-doce/search?queries=agua%20luso — used for delivery/search-flow evidence, not reliable product-price extraction.
- Traditional water suppliers checked: Fonte Viva / Culligan pages were blocked or quote-led; use as category competitors, not price benchmarks unless founders provide quotes.

## Strategic conclusion

AguAqui should not claim to be cheaper than supermarkets. The winning claim is different:

> **AguAqui owns the painful service layer for heavy recurring baskets: precise slot, next-day delivery, carried to apartment/house/office, and repeat replenishment.**

Supermarkets win on shelf price. AguAqui must win on:

1. heavy basket specialization;
2. carried-to-door/upstairs promise;
3. punctual slot rather than “sometime during the day”;
4. repeat ordering and route density;
5. multi-category heavy essentials basket.

## Competitor map

| Segment | Examples | What they are good at | Weakness vs AguAqui |
|---|---|---|---|
| Supermarkets online | Continente, Auchan, Pingo Doce/Mercadão | Broad assortment, low shelf prices | Not specialized in heavy recurring baskets; slot/upstairs experience may be less differentiated; delivery windows and availability vary |
| Quick commerce / couriers | Glovo, Uber Eats | Fast small urgent baskets | Poor fit for heavy crates, 18.9L bottles, paper bulk, recurring scheduled replenishment |
| Traditional water/office suppliers | Fonte Viva, Culligan, office water suppliers | Water dispensers, B2B/office hydration | Narrow category, quote/subscription-led, less consumer app/basket breadth |
| Wholesalers / cash-and-carry | Makro, Recheio | Price and bulk for businesses | Requires procurement trip/account; not home doorstep UX |
| Firewood / bulky future | Continente, Auchan, Leroy/Bricodepot-type retailers, local suppliers | Commodity price / store availability | Delivery upstairs and precise timing are not the core product; category is seasonal and operationally heavy |
| **AguAqui** | Water-first heavy essentials | App + heavy basket + next-day / precise slot + carried to door + repeat replenishment | Needs proof of capacity, unit economics, and service reliability at scale |

## Price benchmark — representative baskets

### Water / hydration

| Product | AguAqui | Competitor benchmark | Interpretation |
|---|---:|---:|---|
| AguAqui 18.9L reusable bottled water | **€7.89** | Not directly comparable in supermarkets | Core wedge: large reusable bottle + delivery/service, not commodity 6-pack |
| Starter kit: 2 bottles + pump | **€19.89** sale, from €24.67 | Not directly comparable | Good onboarding SKU; should be shown as “starter kit” |
| Luso 6×1.5L plastic water | Not primary SKU | Continente **€3.99**; Auchan **€3.99 + €0.60 deposit** | Supermarkets are cheaper on commodity plastic water; AguAqui should not fight here on price |
| Luso glass 20×500ml | **€29.80** AguAqui | Need like-for-like competitor check | Better for hospitality/office/premium baskets |
| Monchique 10L | **€4.99** AguAqui | Similar commodity benchmark possible | Useful bridge between supermarket water and heavy delivery |

### Paper essentials

| Product | AguAqui | Competitor benchmark | Interpretation |
|---|---:|---:|---|
| RENOVA Papel Higiénico 48 Rolos | **€12.47** | Continente **€9.49** promo / PVPR €14.65; Auchan **€9.45** promo | AguAqui may be price-competitive vs PVPR but not promos; advantage is basket/service |
| RENOVA hand towels 10–20 packs | **€17.66–€45.12** | Office/supermarket benchmark needed | Strong B2B/office replenishment category |
| Kitchen rolls / tissues | **€3.20–€37.42** | Category comparable in supermarkets | Good bulky add-on to lift AOV |

### Drinks / milk / coffee

| Product | AguAqui | Competitor benchmark | Interpretation |
|---|---:|---:|---|
| Schweppes multipacks/crates | **~€23.53–€44.55** | Supermarkets/wholesalers vary | Strong for offices, events, cafés, hospitality |
| 7Up cans 4×6×330 / 28×330 | **€25.44–€30.45** | Supermarkets/wholesalers vary | Heavy, bulky, high-AOV add-on |
| Alpro / Oatly multi-packs | **€11.48–€25.09** | Supermarkets vary | Repeat pantry/office category |
| Coffee / sugar / capsules | Wide range, e.g. beans/capsules/sugar | Office suppliers / Makro / supermarkets | Positions AguAqui as office/home replenishment, not water-only |

### Firewood future

| Product | Benchmark | Interpretation |
|---|---:|---|
| Continente Lenha de Mistura 10kg | **€3.59** / 0.36€/kg, unavailable in fetched result | Commodity floor price; likely pickup/availability dependent |
| Continente Saco de Lenha Sobro 10kg | **€3.99**, unavailable in fetched result | Commodity benchmark |
| Auchan BBQ Lovers mixed/sobro/popular +/-10kg | **€3.49–€4.49** | Commodity price; delivery/upstairs service could be premium if operationally feasible |

## Current customer base — inferred from deck metrics

Deck gives:
- monthly revenue: **€50.3k**;
- AOV: **€30.16**;
- orders/customer/month: **1.3**.

Implied current volume:
- **~1,669 orders/month** = €50,322 / €30.16;
- **~1,283 active monthly customers** = 1,669 / 1.3.

Public site says “hundreds of homes and offices” and “+100 reviews”; deck metrics imply the active base may already be over 1k monthly customers if the AOV/frequency definitions are consistent. This should be validated with founders and then shown clearly.

## Where AguAqui is going

The current deck says the round enables:
- **€360k for 10%**;
- **12–18 months runway**;
- **€70k → €260k monthly revenue**;
- **5,200 deliveries/month**;
- Lisbon + Porto + Leiria fully operational; Braga, Coimbra, Faro launch.

Implied target:
- **~4,000 active customers** at 1.3 orders/customer/month = 5,200 / 1.3;
- **€50 AOV** implied by €260k / 5,200 deliveries;
- **5.17× revenue growth** vs current €50.3k/month.

This is a strong story, but only if the deck explains the driver:

> **Target growth comes from more customers + larger heavy-essentials baskets + category expansion + route density.**

## Recommended investor ambition slide

Headline:
> **From ~1.3k active customers to 4k active replenishment customers.**

Support:
- Today: ~1,669 monthly orders, ~1,283 active monthly customers, €30.16 AOV.
- Next milestone: 5,200 monthly deliveries, ~4,000 active customers, €50 implied AOV.
- How: Lisbon density → Porto/Leiria replication → adjacent heavy categories → B2B recurring baskets.

## What must be validated before final investor deck

1. Confirm current active customer count from internal analytics.
2. Confirm definition of “95% retention” — cohort? monthly? repeat? customer or revenue retention?
3. Confirm if delivery is actually exact slot, what slot length, and on-time delivery rate.
4. Confirm if orders are always carried upstairs/to apartment/office, and any limits.
5. Confirm whether delivery is free for all orders, minimum basket, subscription, or zone-specific.
6. Confirm B2B/B2C split and top customer segments.
7. Confirm capacity: fleet, drivers, routes, max orders/day, current utilization.
8. Confirm gross margin and contribution margin per order.

## How to talk about price without losing

Do **not** say:
> We are cheaper than supermarkets.

Say:
> Supermarkets sell cheap SKUs. AguAqui sells a higher-value service: a heavy recurring basket delivered to the door in a precise slot. The customer pays to avoid carrying, waiting, and repeating the chore.

Investor phrasing:
> **The wedge is not lowest unit price; it is the service layer supermarkets are not built around: punctual, heavy, recurring replenishment.**

# racknerd black friday deals: KVM VPS from $10.60 a year with no renewal hike — every plan compared, sale timing, and how to order before the cheap tiers sell out

RackNerd's Black Friday page is live and taking orders, and the headline number explains why people circle this sale every year: a 1GB KVM VPS at **$10.60 per year**. The more important detail sits at renewal — these promotional prices are the renewal price, permanently, according to the trackers that have followed every RackNerd flash sale since 2022. Dedicated servers start at $49/month, and cPanel shared hosting is on the same page.

There is one catch worth knowing upfront: during the main sale window, the cheapest configurations have historically sold out within hours, and RackNerd doesn't restock a sold-out plan until the next holiday event. LowEndBox, which has covered the company for years, counts it among its most positively reviewed providers, so the November rush is real rather than manufactured.

## The short version

- Something cheap that's always on — a blog, a WireGuard endpoint, a small dev box: the **1GB KVM VPS at $10.60/year**.
- WordPress or a handful of services with actual traffic: **2.5GB at $18.66/year**, or **4GB at $29.98/year** if you run containers.
- A whole machine with your own IP block: dedicated servers start at **$49/month**.

👉 [See every Black Friday plan and price on RackNerd's order page](https://bit.ly/my-rn)

## What's actually on the Black Friday page

Five KVM VPS plans, priced from $10.60 to $62.49 per year, all built on Intel Xeon hardware with RAID-10 enterprise SSD storage and deployed instantly after payment.

| Plan | vCPU | SSD storage | Monthly transfer | Price | Order |
| --- | --- | --- | --- | --- | --- |
| 1GB KVM VPS | 1 | 25 GB | 2 TB | $10.60/yr | [ order 1GB](https://bit.ly/my-rn) |
| 2.5GB KVM VPS | 2 | 45 GB | 3 TB | $18.66/yr | [ order 2.5GB](https://bit.ly/my-rn) |
| 4GB KVM VPS | 3 | 65 GB | 6.5 TB | $29.98/yr | [ order 4GB](https://bit.ly/my-rn) |
| 6GB KVM VPS | 5 | 100 GB | 10 TB | $44.98/yr | [ order 6GB](https://bit.ly/my-rn) |
| 8GB KVM VPS | 6 | 150 GB | 20 TB | $62.49/yr | [ order 8GB](https://bit.ly/my-rn) |

Every plan in that table shares the same baseline: a 1Gbps port, one dedicated IPv4 address, full root access, the KVM/SolusVM control panel, and a free Clientexec license. You pick the datacenter from a dropdown in the order form — the lineup has covered Los Angeles, San Jose, Seattle, Dallas, Chicago, New Jersey, New York, Atlanta and Ashburn, and the current page notes that more locations have been added. OS choices run through CentOS, RockyLinux, AlmaLinux, Debian and Ubuntu, and custom ISOs are possible via a support ticket.

One expectation to set: this is SSD on older-generation Xeon hardware, not NVMe. At 88 cents a month for the 1GB plan, that's the trade you're accepting. If single-thread performance matters more to you than price — heavy compiling, latency-sensitive databases — RackNerd also sells a separate Ryzen lineup (DDR5, NVMe) outside these specials that's worth a look before you commit.

## The bare metal dedicated server specials

Five dedicated configs, from $49 to $259 a month, each with IPMI access and manually custom-built — expect a 24 to 72 hour provisioning window after ordering.

| Server | CPU / RAM | Storage | Bandwidth / IPs | Price/mo | Order |
| --- | --- | --- | --- | --- | --- |
| Xeon E3-1230 V2 (New York) | 4C/8T 3.3GHz, 16 GB | 500 GB SSD | 30 TB, 5 usable IPs | $49 | [ order](https://bit.ly/my-rn) |
| Xeon E3-1240 V3 (New York) | 4C/8T 3.4GHz, 32 GB | 500 GB SSD + 2 TB HDD | 30 TB, 13 usable IPs | $59 | [ order](https://bit.ly/my-rn) |
| AMD EPYC 7402 (Utah) | 24C/48T 2.8GHz, 128 GB | 2 TB NVMe | Unmetered 1Gbps, 1 IP | $155 | [ order](https://bit.ly/my-rn) |
| Dual Xeon E5-2640 V2 (Los Angeles DC-02) | 16C/32T 2.0GHz, 64 GB | 240 GB SSD + 10× 16 TB HDD | 200 TB, 5 usable IPs | $259 | [ order](https://bit.ly/my-rn) |
| SEO special (multiple locations) | Xeon E3-1240 V2, 16 GB | 1 TB SSD | 30 TB, 249 usable IPs | $135 | [ order](https://bit.ly/my-rn) |

Two of these deserve a second look depending on what you're actually doing. The $59 E3-1240 V3 includes 13 usable IPv4 addresses on a /28, which is unusual at this price if you need to spread out sites or services across IPs. And the $135 SEO special bundles 249 usable IPv4 addresses (a /29 plus four /26 blocks, or equivalent splits) — the page itself labels it for SEO work, and that's the honest use case: agencies running many client sites. The $259 dual E5-2640 V2 is the odd one out, built around 160 TB of raw storage across ten 16 TB drives; it's a backup or media server, and overkill for anything else.

👉 [Browse the dedicated server specials on the Black Friday page](https://bit.ly/my-rn)

## Shared hosting and reseller plans are on the same page

If you don't need root access, the Black Friday page also carries cPanel shared hosting and cPanel reseller hosting specials. CloudLinux and LiteSpeed are part of the shared hosting stack, and the reseller tiers come with WHM for creating your own cPanel accounts. The VPS and dedicated deals above are the main event, but it's worth scrolling the full page before deciding.

## Why the renewal price is the real story

The sale price is the renewal price — that's the whole reason people treat these deals differently from typical hosting discounts. RackNerd doesn't run introductory pricing with a jump at renewal. A plan bought at $10.18/year in a past flash sale still renews at $10.18/year years later, per the third-party trackers who've watched this play out. The price you see on the Black Friday page is the price on every invoice until you cancel.

For context on how unusual that is: budget-hosting comparison sites put rivals like Hostinger at a 30–50% renewal increase. That gap is why the LowEndBox community treats these annual plans like long-term infrastructure rather than a one-year promo.

It helps to know what RackNerd charges outside the sale, so you can see what you're actually saving:

- KVM 512 (768 MB RAM, 15 GB SSD, 1 TB transfer): $1.49/mo or $17.88/yr
- KVM 1G (1 GB RAM, 20 GB SSD, 2 TB): $2.49/mo or $25.49/yr
- KVM 2G (2 GB RAM, 40 GB SSD, 4 TB): $3.99/mo or $39.89/yr
- KVM 3G (3 GB RAM, 60 GB SSD, 5 TB): $5.49/mo or $55.89/yr
- KVM 4G (4 GB RAM, 80 GB SSD, 8 TB): $7.49/mo or $74.99/yr

The regular prices are already reasonable for KVM virtualization with guaranteed resources and a dedicated IPv4. The Black Friday 1GB plan at $10.60 costs less than half of what the same tier lists for the rest of the year — and it stays at $10.60 on renewal, which is where the math gets hard to beat.

If you've settled on a mid tier, 👉 [lock in the 4GB KVM VPS at $29.98/year](https://bit.ly/my-rn) — it's the config most people grow into anyway.

## Sale timing: when deals go live and what sells out

The main sale runs from the Wednesday before Thanksgiving through Cyber Monday — four to five days — and it consistently produces the lowest prices of RackNerd's year. No other sale beats it on entry pricing. Popular plans have sold out in as little as 4–8 hours; during the 2025 sale, which launched on Wednesday evening, the cheapest 768 MB plans were gone by Saturday morning.

The fuller calendar, based on tracked sales since 2022:

| Sale | Typical window | Entry price (past sales) | Sell-out speed |
| --- | --- | --- | --- |
| Black Friday / Cyber Monday | Wed before Thanksgiving – Mon after | $10.18–$10.98/yr | 4–8 hours (popular plans) |
| New Year's | Jan 1–7 | $10.28–$11.49/yr | 12–24 hours |
| Chinese New Year | Late Jan – mid Feb | $10.88–$12.98/yr | 24–48 hours |
| Independence Day | Jul 1–5 | $11.49–$13.98/yr | 24–48 hours |
| Anniversary | Varies, 1–2×/year | $11.88–$14.18/yr | 48+ hours |

Two practical notes on timing. First, RackNerd does not restock a sold-out configuration mid-sale — once the 1GB tier is gone, it's gone until the next event. Second, the fastest public alert is the LowEndBox and LowEndTalk posts, which usually appear within minutes of a sale going live; RackNerd's own Twitter/X announcements tend to lag 30–60 minutes behind. If Black Friday slips past you, the New Year's sale in early January typically lands within $1–2/year of the Black Friday price, so missing the main event isn't a disaster.

👉 [Check what's still in stock on the Black Friday page](https://bit.ly/my-rn)

## How to order without fumbling it

The checkout itself is a standard cart — nothing exotic. The mistakes happen before it, so here's the sequence that avoids them.

1. **Decide your RAM tier before you open the order page.** Browsing while plans sell out is how people miss out. Rough mapping: 1 GB handles a blog, a VPN endpoint or a small dev environment; 2.5 GB is the comfortable WordPress tier; 4 GB suits Docker and small container workloads; 6–8 GB covers busier multi-service setups. At these prices, a wrong guess costs less than lunch — but deciding first still saves you the reorder.
2. **Pick the plan and choose your datacenter in the dropdown.** This is the step people rush. Location affects latency to you and your visitors, and it's selected during ordering, not after.
3. **Pay.** RackNerd has long accepted an unusually wide list: PayPal, credit cards, Alipay, UnionPay, several cryptocurrencies including Bitcoin, plus iDEAL and India UPI. Whatever your usual payment rail is, it probably works.
4. **Wait for provisioning.** VPS plans set up instantly after payment. Dedicated servers are built manually, so give them 24–72 hours.

If you need a specific OS image that isn't in the standard list, open a support ticket after ordering and they'll mount a custom ISO — support runs 24x7.

## FAQ

**Do RackNerd Black Friday prices renew higher?**
No. The promotional price is the renewal price for as long as you keep the plan — there's no introductory period and no renewal increase, which third-party trackers have confirmed across multiple sale years.

**When do the deals go live?**
Historically the Wednesday evening before Thanksgiving, running through Cyber Monday. The Black Friday page with live order links is already up, so you can order before the main rush if the configuration you want is listed.

**What if the plan I want sells out?**
Sold-out configurations aren't restocked mid-sale. Your realistic backup is the New Year's sale (January 1–7), which usually prices within $1–2/year of Black Friday on the entry tiers.

**Which datacenter locations can I choose?**
You select from a dropdown in the order form. Past lineups have included Los Angeles, San Jose, Seattle, Dallas, Chicago, New Jersey, New York, Atlanta and Ashburn, and the current Black Friday page notes that additional locations have been added.

**Are these plans good for production sites?**
For most small-to-medium sites, yes — KVM virtualization means guaranteed RAM and CPU rather than oversold containers, plus a dedicated IPv4. The honest limitation is hardware generation: the VPS deals run on SSD storage and older Xeon CPUs, so extremely I/O-heavy or compute-heavy workloads will feel the ceiling.

## Picking your plan at checkout

Map the lineup to what you're actually hosting and the choice mostly makes itself. Cheapest possible always-on box: the 1GB at $10.60. A real website with traffic: 2.5GB at $18.66. Containers, staging environments or a busy dev setup: 4GB at $29.98. A whole machine: the E3-1240 V3 at $59/month if the 13 IPs are useful to you, or the $135 SEO special if IPv4 volume is the point.

Two last checks before you pay: confirm the datacenter location in the dropdown matches where your users are, and remember VPS delivery is instant while dedicated servers take up to three days. Then have your payment method ready — the cheapest tiers are the ones that historically vanish first. 👉 [Grab your RackNerd Black Friday plan before the cheap tiers go](https://bit.ly/my-rn)

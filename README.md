# Buy VPS with Alipay: Which Hosts Actually Take It, What the 3% Fee Costs, and How to Pick a Plan From $1.99/mo

Alipay checkout exists at a small set of overseas VPS hosts, and the entry prices are lower than most buyers expect. LightNode lists $7.71/month, Infrawire €8.30/month, rdp.monster $8.99/month, and the cheapest plan on JustHost's published tariff page is $1.99/month for a 512 MB NVMe box.

Getting the payment through is the easy part. What decides whether the purchase was a good one is four details that rarely sit together on a landing page: whether Alipay is genuinely on the checkout page, whether the method carries a surcharge, how long provisioning takes, and whether the network fits the people who will use the server. This guide works through all four, then puts the current plan lineups side by side so a price can be matched to a workload.

> **Short version:** the lowest entry cost in this group is JustHost's small NVMe plans, which start at $1.99/month and rise in small steps as cores, RAM and port speed increase. Confirm Alipay appears at the payment step before committing. 👉 [Check JustHost's current plans and whether Alipay shows at checkout](https://justhost.asia/en/services/vps/tariffs-all?ref=196392)

## Four things to confirm before you pay with Alipay

**1. Alipay has to be in the payment selector, not just the page title.** qhoster runs a page titled "Buy VPS with Alipay" whose accepted-payments list covers cards, PayPal, Skrill, WebMoney, Bitcoin, Western Union and bank transfer, with no Alipay anywhere in it. A title is a keyword target; the payment selector is the actual contract. Add a plan to the cart and read the list of methods before typing anything.

**2. The method can carry a fee.** Infrawire is the one host here that publishes its surcharge: Alipay adds 3% of the invoice, added to the bill and displayed before confirmation, and it is the only payment method they charge for. Card, PayPal, crypto and bank transfer stay free. On the €8.30 Entry plan that means roughly €8.55 out of your account. A 3% line is enough to flip the ranking when two hosts sit within a euro of each other.

**3. Provisioning time varies by two orders of magnitude.** rdp.monster says the server is ready about 10 seconds after the payment is confirmed. LightNode says under 2 minutes. Infrawire says about 5 minutes once payment clears. An older SeiMaxim page quotes 15 minutes to an hour. If a live site has to move tonight, that spread matters more than a dollar of monthly price.

**4. Alipay is a real-name payment.** rdp.monster states it directly: they never ask for ID, but the payment itself is tied to your verified Alipay account. If the purchase needs to be separated from your identity, the same host accepts USDT and Monero. Convenience and anonymity do not arrive in the same transaction.

## JustHost's current VPS lineup

JustHost publishes its full tariff list with monthly prices and a lower rate when you commit to 12 months. Every plan is KVM with NVMe storage and an unmetered port on a fair-share basis, and the port speed scales with the plan, from 10 Mbps on the $1.99 box to 750 Mbps on the larger ones.

| Plan | CPU / RAM / NVMe | Port (fair-share) | Price (USD/month) | Order |
| --- | --- | --- | --- | --- |
| VPS Promo | 1 core / 512 MB / 5 GB | 10 Mbps | $1.99 | [See plan](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| New Star | 1 core / 1 GB / 10 GB | 100 Mbps | $3.81, or $3.05 on 12 months | [See plan](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Sirius | 1 core / 1 GB / 20 GB | 300 Mbps | $4.85, or $3.88 on 12 months | [See plan](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392) |
| Arcturus | 1 core / 2 GB / 30 GB | 300 Mbps | $6.92, or $5.53 on 12 months | [See plan](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392) |
| Double Star | 2 cores / 2 GB / 20 GB | 200 Mbps | $7.08, or $5.67 on 12 months | [See plan](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392) |
| Alpha Centauri | 2 cores / 2 GB / 40 GB | 400 Mbps | $8.99, or $7.19 on 12 months | [See plan](https://justhost.asia/en/services/vps/tariffs/alpha_centauri?ref=196392) |
| Bright Star | 4 cores / 4 GB / 30 GB | 300 Mbps | $9.80, or $7.84 on 12 months | [See plan](https://justhost.asia/en/services/vps/tariffs/bright-star-c4r4096nvme?ref=196392) |
| Vega | 2 cores / 4 GB / 80 GB | 500 Mbps | $13.44, or $10.75 on 12 months | [See plan](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392) |
| Capella | 4 cores / 4 GB / 120 GB | 750 Mbps | $18.30, or $14.64 on 12 months | [See plan](https://justhost.asia/en/services/vps/tariffs/capella?ref=196392) |

The 12-month rate applies when a year is paid upfront, and several plans also need a minimum 3-month term before the discount kicks in. Traffic is unmetered, with the site quoting equivalents from about 4 TB to over 230 TB per month depending on port speed. The site also runs a separate "Special" promotion set and a configurator with HDD, SSD and IPv6-only variants, and those pages show different numbers for similar specs. Compare the exact plan page you land on rather than a headline figure copied from a coupon site.

Two independent reviews published this year describe the Hong Kong location as KVM with NVMe arrays, one IPv4 plus one IPv6, and a control panel that switches datacenter or IP in one click. A France PAR1 test on the same site reported Geekbench 6 scores of 1272 single-core and 4170 multi-core. Those are third-party measurements, not vendor specifications, but they line up with the price tier: entry-level hardware, adequate I/O, no premium silicon.

## What LightNode, Infrawire and rdp.monster charge

LightNode's four tiers are the simplest to compare because the storage and traffic figures scale cleanly.

| Plan | Specs | Price (USD/month) |
| --- | --- | --- |
| Start | 1 vCPU / 2 GB DDR4 / 50 GB NVMe / 1 TB | $7.71 |
| Agency | 2 vCPU / 4 GB / 50 GB / 2 TB | $14.70 |
| Premium | 4 vCPU / 8 GB / 50 GB / 3 TB | $27.70 |
| Enterprise | 8 vCPU / 16 GB / 50 GB / 4 TB | $52.70 |

LightNode runs 40+ locations across five continents, including Hong Kong, Japan, Singapore, Korea, Vietnam and Thailand alongside US, European and Middle Eastern sites. Billing is hourly, so a wrong image or wrong country can be destroyed and rebuilt without burning a month. There is no credit card requirement, and a first recharge can add up to $15 in credit.

Infrawire bills in euros and leans on French datacenters with a Hong Kong presence at Equinix HK1. Current displayed prices:

- **Entry**: €8.30/month for 2 cores, 4 GB DDR4, 40 GB NVMe, 2.5 Gbps, unlimited traffic (listed at €16.60 before discount)
- **Bronze**: €14.55 for 4 cores, 8 GB, 80 GB NVMe, 5 Gbps
- **Silver**: €27.60 for 8 cores, 16 GB, 150 GB NVMe, 5 Gbps
- **Gold**: €41.48 for 12 cores, 24 GB, 180 GB NVMe, 10 Gbps
- **Platinum**: €52.20 for 16 cores, 32 GB, 200 GB NVMe, 10 Gbps

All five carry KVM, a dedicated IPv4 and IPv6, root over SSH, anti-DDoS filtering, a browser VNC console and 7-day money-back terms with no minimum commitment.

rdp.monster sits at the other end: $8.99/month for 2 dedicated cores, 6 GB DDR4 ECC and 40 GB NVMe, scaling to 24 cores and 64 GB of RAM, plus a Ryzen 9 7950X line with DDR5 memory and 10 to 20 Gbps ports from $13.99/month. Its selling point is dedicated CPU and RAM with full administrator access on Windows or Linux, hosted in Europe or the US.

## Paying with Alipay does not mean the server suits mainland China

This is the most expensive misunderstanding in the whole keyword. rdp.monster answers it before anyone asks: "No, and we prefer to say it upfront. Our datacenters are in Europe and the USA, without China-optimized routes such as CN2 GIA." They recommend the servers for cross-border e-commerce, trading platforms, Telegram and Discord bots, automation and remote Windows desktops, and tell latency-sensitive mainland users to buy a China-optimized line instead.

The same logic applies to any Asian location. A Hong Kong VPS is geographically close, but the review of JustHost's Hong Kong plans found outbound traffic routing through the US, with telecom and Unicom return traffic also passing through the US; mobile return paths performed decently for Shanghai and Guangzhou, Beijing went via the US, and the reviewer suggested a relay for better speeds. The France PAR1 test showed direct return routes for all three Chinese carriers, with telecom weak at peak hours. Location on the order form and route quality after delivery are different things, and only the second one shows up as latency.

If your users are in mainland China and latency is the product, budget for a China-optimized line. If your users are everywhere else and you simply need a box you can pay for with Alipay tonight, the standard European and American routes are fine.

## Fees, currency and getting your money back

Run the surcharge through a real invoice. Infrawire's Entry plan at €8.30 plus 3% comes to about €8.55, roughly 25 cents, which is trivial on one server and less trivial across ten. LightNode, rdp.monster and JustHost price in US dollars; Infrawire prices in euros. rdp.monster notes that the exact amount is displayed on the Alipay payment page before you confirm, and that is the number your bank statement will match, not the number in the plan table.

Exit terms differ as much as prices. Infrawire offers 7 days. A SeiMaxim page from 2022 advertises 14 days and extra IPv4 addresses at $3.50 per month each, but treat that page as historical: it still lists Windows Server 2019 as current and its SLA paragraph contradicts itself, quoting both 99.99% and 99.999% on the same screen. LightNode's hourly billing is the cheapest exit of all, since a mistaken order can be destroyed the same day. JustHost's tariff pages do not state a refund window, so read the terms page before you pay rather than after.

## FAQ: buying a VPS with Alipay

**Can I buy an overseas VPS without an international credit card?**
Yes. That is the entire purpose of the method. LightNode explicitly does not require a card binding, and rdp.monster points out that many buyers in China have no card that works with foreign merchants and no daily use for PayPal.

**Does Alipay add a fee?**
Sometimes. Infrawire charges 3% and shows it on the invoice before confirmation. The other hosts covered here do not publish an Alipay surcharge, but silence is not the same as zero, so check the invoice total at the payment step.

**How long until the server is usable?**
Anywhere from about 10 seconds (rdp.monster) to 2 minutes (LightNode), 5 minutes (Infrawire), or 15 minutes to an hour on older setups. Payment confirmation, not order placement, is when the clock starts.

**Can I get a refund if the plan is wrong?**
Infrawire offers 7 days, LightNode lets you destroy an hourly-billed machine, and SeiMaxim's 14-day policy is visible only on a 2022 page. Confirm the current terms in the client area before ordering.

**Will a VPS bought with Alipay be fast for users in mainland China?**
Not by default. Alipay is a payment rail, not a network route. Ask specifically about CN2 GIA or equivalent China-optimized lines, and expect to pay more for them.

## Which one to pick

Match the plan to the job rather than to the lowest number in the table.

A single small site, a proxy, a bot or a test box: JustHost's $1.99 Promo or the $3.81 New Star covers it, and the 12-month rate drops New Star to $3.05. 👉 [See the $1.99 Promo plan and its current price](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392)

Several countries, short experiments, or a plan you may resize tomorrow: LightNode's hourly billing and 40+ locations are worth the higher entry price.

A European or Hong Kong node with euro invoicing and a 7-day exit: Infrawire, with the 3% added to the budget.

Windows remote desktop or guaranteed dedicated cores: rdp.monster, and accept the European or American routing that comes with it.

Before you enter the Alipay password, two checks take thirty seconds. Look for Alipay in the payment selector itself, and read the invoice total rather than the plan price, so any surcharge is visible before it is charged. 👉 [Start from JustHost's full tariff list and confirm the checkout options](https://justhost.asia/?ref=196392)

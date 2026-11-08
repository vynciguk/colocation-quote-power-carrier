# Data Center Colocation Services: What's Included, How the Quote Gets Built, and the Three Questions That Decide It (With a Dallas Colocation Walkthrough)

Data center colocation services supply the physical layer inside a building someone else operates: rack space, power, cooling, bandwidth, physical security. You keep ownership of the servers. Providers rarely publish a rate card, so the number you get is assembled from footprint, power density, bandwidth and cross-connects, and two tenants in the same building can pay very different amounts for the same cabinet count. Power density is the first filter, and the SLA condition attached to whatever uptime percentage appears in the brochure is the first contract term worth reading closely.

This guide covers what a colo contract actually includes, where the cost moves when you stop running your own machine room, how to read an uptime claim, why carrier counts are a poor comparison metric, and what a smaller Dallas provider does differently. Spin Servers sells colocation from a single Tier III facility in Dallas with a 12-month minimum, 30TB of monthly bandwidth and free Level 1 remote hands, which makes it a useful concrete case for the whole category.

> **Quick read:** If you own a server (or a few) built from The Server Store hardware and want it running in a Dallas Tier III building with your own IP space, Spin Servers' standard colocation includes 1 IPv4 (IPv6 on request), 30TB/month of bandwidth, dual 1Gbps ports with LACP, free Level 1 remote hands, and portal access for OS reinstalls and power control, on a 12-month minimum billed monthly. Rates are quoted after you describe hardware, power and bandwidth, not published.
> 👉 [Get a colocation quote from Spin Servers](https://bit.ly/Spinservers)

## Spin Servers colocation options at a glance

Spin Servers does not publish a per-cabinet price. The table below lists what each configuration contains and how it is billed. Treat the price column as "quoted," and treat the term column as the part you can plan around.

| Configuration | What's included | Space and power | Price and term | Order |
| --- | --- | --- | --- | --- |
| Standard colocation, single server | 1 IPv4 (IPv6 on request), 30TB/month bandwidth, dual 1Gbps ports with LACP, free Level 1 remote hands, client portal and remote console | Shared cabinet, Dallas Tier III facility | Quoted; 12-month minimum, paid monthly | [Request current pricing](https://bit.ly/Spinservers) |
| Full cabinet or larger | Same network baseline; supervised access can be arranged; power and bandwidth set per deployment | Dedicated cabinet or larger footprint | Quoted; 12-month minimum | [Discuss a full-cabinet deployment](https://bit.ly/Spinservers) |
| Hardware plus colocation | Server chosen or custom-built with The Server Store, delivered and installed, typically online within 24 hours of delivery | Depends on the build | Hardware priced separately, colo quoted | [Start with a hardware and colo quote](https://bit.ly/Spinservers) |
| Bare metal dedicated server | Provider-owned hardware, dual 10Gbps ports, month-to-month billing, no setup fee | Provider-managed | From $79/mo per third-party listings* | [Check dedicated server availability](https://bit.ly/Spinservers) |

\*Entry dedicated-server pricing appears in third-party reviews rather than on the colocation page. Confirm the current figure before you budget.

## What data center colocation services include, and what stays yours

Colocation means placing your own servers and computing hardware in rented space inside a data center owned or operated by a third party. Tenants share the operating costs of power, cooling, renewable energy coverage, bandwidth, communications and security, which removes a set of capital expenses from your books: the UPS, multiple backup generators, energy sourcing, grid connections and HVAC units. The ongoing cost of maintaining in-house servers and upgrading to more efficient models comes off the list too. What you still pay for is power, cooling, bandwidth and security, just as rent instead of as infrastructure you own.

The ownership line matters when you compare colocation with cloud. A colo tenant keeps ownership and ultimate control of its hardware and knows which building it sits in. A cloud provider owns and is responsible for all the leased hardware, and in many cases the customer knows only the country where the workload runs. If your compliance scope, data residency posture or latency model depends on knowing the building, colo answers that question directly.

Space comes in three common shapes: cabinet, cage and private suite. Some providers go further down the granularity scale, offering compact and standard cabinets, two-post and four-post racks, and custom cages and suites. Single-server colocation is the smallest unit of all, and it is where Spin Servers' standard package sits: one server in a shared cabinet, handled by the onsite team, with full-cabinet and larger deployments moving to arranged supervised access.

## How the quote gets built

None of the providers' public pages reviewed here list a per-cabinet rate. Flexential asks for your infrastructure goal and returns a solution blueprint. Spin Servers asks for hardware, power and bandwidth requirements and builds a package from that. The structural change worth understanding is that colocation converts capital expenditure into an operating expense model, while still letting you amortize the hardware investment, and in some states it opens access to tax incentives.

Four variables usually shape the monthly number:

1. **Footprint.** A shared cabinet slot, a full cabinet, a cage and a suite carry different floor-space economics.
2. **Power.** How many amps per cabinet you draw, and whether you take primary plus redundant circuits, changes both the monthly charge and the SLA you qualify for.
3. **Bandwidth.** Committed rate versus burstable billing, and the overage rate once you exceed the included volume.
4. **Cross-connects.** Ask explicitly whether each physical link to a carrier or cloud on-ramp is included or billed per link per month.

Spin Servers includes 30TB of monthly bandwidth and dual 1Gbps ports with LACP in the standard package, and offers free private networking between your servers plus free announcement of your own IP addresses. Those three inclusions remove line items that show up on many colo invoices.

## Three questions that turn an uptime number into a contract term

Uptime percentages get quoted as if they were comparable. They are not, because the conditions behind them differ.

Equinix states an industry-leading uptime of 99.999%+ across its colocation footprint. CoreSite states a long-standing record of consistently exceeding the industry standard of 99.999%, combined with a 100% uptime SLA. 365 Data Centers guarantees 100% uptime of power **provided customers subscribe to primary and redundant circuits**, and separately offers a 99.999% SLA for its network services. Three providers, three different numbers, and one of them attaches a subscription condition to the guarantee. All of these are vendor claims, not third-party verified figures.

Ask three things before you sign:

- **What does the percentage cover?** Power, network, cooling, or the whole service. A 100% power guarantee and a 100% uptime SLA are not the same promise.
- **What triggers the guarantee?** A utility failure at the building, or only a failure on the redundant path you paid for.
- **What is the remedy?** Service credits, a termination right, or a statement of intent with nothing behind it.

Spin Servers' colocation page does not publish an SLA percentage. It describes a Tier III facility fed by three utility providers, with 24/7 onsite technicians. That is a facilities description, not a contract term, so request the SLA language in writing before you commit to the 12-month minimum.

👉 [Ask Spin Servers for the Dallas colocation SLA and current quote](https://bit.ly/Spinservers)

## Power density decides your shortlist before anything else does

Cabinet density is the filter that eliminates most of the market early. Flexential supports up to 150+ kW per cabinet with advanced liquid cooling across its high-density footprint. Equinix lists high-density air and liquid cooling among its capabilities. CoreSite's own framing is blunt: data centers are getting bigger, denser and more power-hungry, and for most organizations an on-premises facility no longer delivers the performance or power densities required.

If your cabinets run at a few kilowatts each, a shared-cabinet or standard-cabinet arrangement covers you and the density conversation is academic. If you are planning GPU nodes or dense compute at 20 kW and above per cabinet, you need a provider that publishes a density figure and can describe the cooling method behind it. Spin Servers does not publish a kW-per-cabinet ceiling on its colocation page. Ask before you design around it.

## Why carrier counts are not a comparison metric

Interconnect numbers are the easiest figures to quote and the hardest to compare. 365 Data Centers' own pages describe access to 275 carrier POPs in one place, connectivity to 86 carriers including top telecom and cable providers in another, and an ecosystem of more than sixty regional and national providers in a third. A carrier POP count and a carrier count measure different things, and the same provider can look three times larger depending on which sentence you read. Flexential's page lists its on-net carrier total twice with two different figures. Neither discrepancy is unique to those providers; it is what happens when marketing numbers outrun definitions.

Two terms explain what you are actually buying:

- A **carrier hotel** is a facility where many telecommunications carriers install networking equipment, often using it as a centralized point to exchange data between long-haul and metro carriers.
- A **meet-me room** is the place inside a data center where multiple carriers and network service providers interconnect, ensuring traffic moves between colocation clients and carriers, internet traffic included.

The question that replaces carrier counting is narrower: **is the specific carrier or cloud on-ramp I need already inside this building, and what does the cross-connect cost per month?** If the answer is no, a thousand on-net carriers change nothing about your latency or your egress bill.

Spin Servers lists Cogent, Lumen and Zayo on a multihomed network, with 1 Tbps+ of DDoS filtering capacity, free private networking between your servers and free BYOIP announcement. Its downtown Dallas facility (DAL2) sits near the 1950 N Stemmons carrier hotel, a fiber-dense block, and launched with over 300Gbps of network capacity. For a single-server or small-footprint deployment that is a workable set of upstreams. Confirm your own carrier is among them before you assume a cross-connect is available.

## Remote hands and compliance: where the included support stops

Remote hands is the service that decides whether colocation actually saves you staffing. Its scope varies enormously.

Spin Servers includes Level 1 remote hands at no charge, defined as power reboots, hot swaps and checking status LEDs. The client portal handles OS installation, power control and remote console access, so routine software-side work does not require a ticket. Anything past Level 1, such as racking new hardware or running cable, is a request to the onsite team; ask for the rate before you need it at 2am.

For contrast, 365 Data Centers describes remote hands as an extension of your own staff, covering hardware replacement and installation, racking, shipping and receiving, equipment inventory and storage, cross-connects and cabling, emergency response, backup tape rotation, reboots and re-installs. Equinix offers Smart Hands® with 24/7 certified technicians and Smart View® for on-demand visibility into environmental and operating data, which is the closest thing to keeping your own monitoring dashboards. What none of them do is administer your operating system, patch your applications or manage your network configuration. Plan for someone on your side to own that.

On compliance, read the framework names rather than the marketing summary. 365 Data Centers states that its facilities meet data retention and security requirements aligned with HIPAA, PCI DSS, SOC 2, SSAE 18 and ISAE 3404. SOC 2 and ISAE 3404 are attestation report types, not certifications, and the distinction matters when your auditor asks what you actually hold. Spin Servers describes its Dallas facility as SOC 2 certified. If you need HIPAA or PCI scope, request the report, check which systems and locations it covers, and confirm that your cage or cabinet falls inside that boundary.

## When colocation is the wrong purchase

If you do not already own servers, colocation usually does not pay at small scale. Spin Servers' own dedicated line illustrates the alternative: provider-owned bare metal with dual 10Gbps ports as standard, month-to-month billing, no setup fee, and provisioning measured in minutes on in-stock hardware, with entry configurations listed from $79/mo in third-party reviews. Renting that is cheaper than buying a server, shipping it to Dallas and paying a colo minimum for the first year.

Colocation starts to make sense when at least one of these is true: you already own hardware that is depreciating on your books, you need your own IP space or a specific compliance boundary around physical infrastructure, your workload needs a density or hardware shape that is not on a rental menu, or you are consolidating several rented servers into hardware you control.

One structural detail is specific to Spin Servers: standard colocation is designed for servers purchased from The Server Store, so the onsite team keeps spares and knows the hardware. Servers bought elsewhere are handled through sales rather than the standard package. If you already own Dell, HPE or Supermicro gear from another source, confirm eligibility first, because it changes both the price and the support model.

## Choosing between the options

Match your situation to one row and stop there:

- **One server, or a handful, already owned or buildable through The Server Store, Dallas is acceptable:** Spin Servers standard colocation. The 30TB bandwidth allowance, dual 1Gbps LACP ports, free Level 1 remote hands and BYOIP announcement cover the common small-footprint needs, and the 12-month minimum with monthly payments keeps the cash commitment predictable.
- **You want capacity this quarter without buying hardware:** Spin Servers dedicated servers. Month-to-month terms beat a 12-month colo minimum when you are still measuring what you need.
- **You need cages, 20 kW+ per cabinet, multiple metros, or a contractual SLA with penalties attached:** go to a multi-site provider whose published density and SLA terms you can hold them to. Spin Servers' colocation is one metro and does not publish an SLA percentage, which is a real constraint for anyone whose business continuity plan assumes geographic separation.

Before you sign anything, confirm six items in writing: the contract term and whether it auto-renews, the installation or setup fee, how power is metered and what overage costs per amp, the bandwidth overage rate past 30TB, the cross-connect charges for each carrier or cloud link, and the SLA remedy text. Those six numbers decide the second-year cost, which is the one that matters.

👉 [See Spin Servers' current colocation package and request a quote](https://bit.ly/Spinservers)

---
id: kt:inventory-management
type: Practice
title: "Inventory Management: Order Quantities, Reorder Points and Safety Stock"
aliases: [inventory management, inventory control, stock control]
domain: operations-and-supply-chain
summary: >-
  The operations discipline of deciding how much stock of each item to hold, how much to order and
  when to reorder, so that a firm meets demand and service targets at the lowest total cost of
  ordering, holding and running short.
broader: [kt:operations-management, kt:supply-chain-management]
related: [kt:just-in-time, kt:bullwhip-effect, kt:working-capital]
relations:
  - {predicate: hasPart, object: kt:economic-order-quantity}
  - {predicate: dependsOn, object: kt:demand-forecasting}
  - {predicate: exemplifiedBy, object: kt:cisco-systems}
sources:
  - id: s1
    title: "How Many Parts to Make at Once (reprint)"
    publisher: Operations Research (INFORMS), record via IDEAS/RePEc
    url: https://ideas.repec.org/a/inm/oropre/v38y1990i6p947-950.html
    type: primary
    accessed: 2026-11-14
  - id: s2
    title: "Ford Whitman Harris's Economical Lot Size Model"
    publisher: UCLA Anderson School of Management (eScholarship, University of California)
    url: https://escholarship.org/content/qt4s8482p2/qt4s8482p2_noSplash_5dfa07046f9562ca39dee86651320d0b.pdf
    type: academic
    accessed: 2026-11-14
  - id: s3
    title: "8.5 Inventory Models for Certain Demand: Economic Order Quantity (EOQ) Model"
    publisher: Fundamentals of Operations Management (eCampusOntario open textbook)
    url: https://ecampusontario.pressbooks.pub/fundamentalsopsmgmt/chapter/8-5-inventory-models-for-certain-demand-economic-order-quantity-eoq-model/
    type: textbook
    accessed: 2026-11-14
  - id: s4
    title: "6.5 Special Topics in Inventory Management"
    publisher: Introduction to Supply Chain Management (University of Arkansas Pressbooks)
    url: https://uark.pressbooks.pub/introscm/?p=350
    type: textbook
    accessed: 2026-11-14
  - id: s5
    title: "OR-Notes: Inventory control"
    publisher: J. E. Beasley, Brunel University
    url: https://people.brunel.ac.uk/~mastjjb/jeb/or/invent.html
    type: academic
    accessed: 2026-11-14
  - id: s6
    title: "What Actually Happened to the Inventories of American Companies Between 1981 and 2000?"
    publisher: Management Science (record via EconPapers)
    url: https://econpapers.repec.org/RePEc:inm:ormnsc:v:51:y:2005:i:7:p:1015-1031
    type: peer-reviewed
    accessed: 2026-11-14
  - id: s7
    title: "Cisco Systems, Inc. Form 10-K fiscal 2001, Exhibit 13 (Annual Report)"
    publisher: U.S. Securities and Exchange Commission (EDGAR)
    url: https://www.sec.gov/Archives/edgar/data/0000858877/000109581101505065/f75710ex13.txt
    type: primary
    accessed: 2026-11-14
created: 2026-11-14
---

# Inventory Management: Order Quantities, Reorder Points and Safety Stock

**Inventory management** is the part of operations that governs the material a firm holds so it can generate future revenue: raw materials, parts, work in process and finished goods.[^s3] Its two classic questions are how many units to order and when to order them, and its objective is good customer service at reasonably low inventory cost, which means trading the amount of stock held against the service level achieved.[^s3] Stock buffers production and sales from fluctuations in the environment, but until it is sold it is a cost, so it has to be managed deliberately.[^s5]

## Origin

The field's founding model came from industry rather than academia. Ford Whitman Harris, an engineer at Westinghouse from 1904 to 1912, published "How Many Parts to Make at Once" in *Factory, The Magazine of Management* in February 1913.[^s2] He argued that interest on the capital tied up in wages, materials and overhead caps how many parts it pays to make in one run, while setup costs set the floor.[^s1] Harris derived the square-root lot-size formula now called the economic order quantity (EOQ). Donald Erlenkotter of UCLA later showed the paper had been lost from view for roughly 75 years, partly because readers tore articles out of the magazine and later writers misquoted his 1915 version; *Operations Research* reprinted it in 1990.[^s1][^s2]

## How it works

**Costs.** Holding (carrying) costs include storage, the opportunity cost of money tied up, obsolescence, deterioration, theft and insurance; ordering costs include processing, inspection, transport and handling.[^s5] Larger orders lower annual ordering cost but raise average stock and therefore holding cost.[^s2]

**Order quantity.** Under steady, known demand, a fixed cost per order, constant lead time and no stockouts, total relevant cost is ordering cost S × D/Q plus holding cost H × Q/2, and it is minimized at Q* = √(2DS/H), where D is annual demand, S the cost per order and H the annual holding cost per unit.[^s3] At that quantity the two cost components are equal.[^s5]

**Timing and safety stock.** With a lead time, the firm reorders when stock falls to a reorder point, set so a new order arrives just as the old stock runs out.[^s3] Because demand and lead times vary in practice, firms hold buffer or safety stock that is drawn on only to avoid stockouts.[^s5] Under continuous review stock is tracked constantly and reordered at the trigger level; under periodic review it is checked at fixed intervals, which costs less to administer but needs more care between checks.[^s4]

**Prioritization.** ABC analysis applies the Pareto idea to stock: roughly 20% of items (A) carry about 80% of inventory value and get the closest monitoring and the most safety stock, while about half of items (C) account for roughly 5% of value and get little attention.[^s4]

## Evidence and critiques

The EOQ is robust: the total-cost curve is flat near the optimum, so ordering somewhat more or less than Q* adds little cost, and Beasley advises treating the result as a ballpark figure because cost inputs are imprecise and demand is rarely constant.[^s5] Its assumptions are also its main weakness. Textbook EOQ ignores shortage and price effects and presumes certain demand and fixed ordering costs.[^s3] The just-in-time school attacked the fixed-setup-cost premise, treating setup time as something to cut until small lots become economical.

Large-sample evidence shows inventory practice has improved. Studying publicly traded U.S. manufacturers from 1981 to 2000, Chen, Frank and Wu found the median inventory holding period fell from 96 to 81 days, an average decline of about 2% a year, driven by work in process (about 6% a year), while finished-goods inventory did not fall.[^s6] Firms with abnormally high inventories earned poor long-run stock returns, but the leanest firms earned only ordinary returns, which suggests that cutting stock pays only up to a point.[^s6]

## In practice

Cisco Systems shows the cost of misjudging demand. In the third quarter of fiscal 2001 it recorded a $2.25 billion excess inventory charge after a sudden, significant drop in demand left inventory above the requirements implied by its forecasts; a $187 million benefit in the fourth quarter partly offset it.[^s7] The episode shows that inventory decisions depend heavily on forecast quality.[^s7]

## Connections

Inventory management sits under **operations management** and **supply chain management**, its broader fields.[^s3][^s4] The **economic order quantity** is a component model of the discipline, originating with Harris.[^s1][^s2] Setting reorder points and stock levels **depends on demand forecasting**, and **Cisco Systems** exemplifies the losses when forecasts fail.[^s7] **Just-in-time** relates as the production philosophy that challenges EOQ's fixed-setup assumption and treats inventory as waste; the **bullwhip effect** relates as the upstream amplification of orders that inventory policies can cause; and **working capital** relates because stock ties up cash, which is why holding periods matter to investors.[^s5][^s6]

## Sources
[^s1]: Ford W. Harris, "How Many Parts to Make at Once", *Operations Research* 38(6): 947–950, 1990 (reprinted from *Factory, The Magazine of Management* 10(2), February 1913). https://ideas.repec.org/a/inm/oropre/v38y1990i6p947-950.html (accessed 2026-11-14)
[^s2]: Donald Erlenkotter, "Ford Whitman Harris's Economical Lot Size Model", UCLA Anderson School of Management, 2013. https://escholarship.org/content/qt4s8482p2/qt4s8482p2_noSplash_5dfa07046f9562ca39dee86651320d0b.pdf (accessed 2026-11-14)
[^s3]: Azim Abbas and Seyed Goosheh, *Fundamentals of Operations Management*, section 8.5 (adapted from Faramarzi and Drane), eCampusOntario, 2024. https://ecampusontario.pressbooks.pub/fundamentalsopsmgmt/chapter/8-5-inventory-models-for-certain-demand-economic-order-quantity-eoq-model/ (accessed 2026-11-14)
[^s4]: Piyush Shah and Elias Kirche, *Introduction to Supply Chain Management*, section 6.5, 2025. https://uark.pressbooks.pub/introscm/?p=350 (accessed 2026-11-14)
[^s5]: J. E. Beasley, "OR-Notes: Inventory control", Brunel University. https://people.brunel.ac.uk/~mastjjb/jeb/or/invent.html (accessed 2026-11-14)
[^s6]: Hong Chen, Murray Z. Frank and Owen Q. Wu, "What Actually Happened to the Inventories of American Companies Between 1981 and 2000?", *Management Science* 51(7): 1015–1031, 2005. https://econpapers.repec.org/RePEc:inm:ormnsc:v:51:y:2005:i:7:p:1015-1031 (accessed 2026-11-14)
[^s7]: Cisco Systems, Inc., Annual Report for fiscal 2001 (Form 10-K, Exhibit 13), SEC EDGAR. https://www.sec.gov/Archives/edgar/data/0000858877/000109581101505065/f75710ex13.txt (accessed 2026-11-14)

# Qualcomm Licensing Economics: A Theory-Driven Assessment

**Author:** Diyorbek Tulanov  
**Institution:** Seoul National University, Department of Economics  
**Course:** Industrial Organization Special Research  
**Date:** December 2025

## 📄 Project Overview

This project evaluates the economic validity of the argument presented by Carl Shapiro and Keith Waehrer regarding Qualcomm's "no-license/no-chips" policy. The central research question is whether a formally "chip-neutral" royalty functions as an economically meaningful tax that raises rivals' costs and distorts competition.

Using a stylized vertical model of licensing and upstream competition, this paper demonstrates that a uniform downstream royalty imposed by a vertically integrated Standard-Essential Patent (SEP) holder acts as a tax. This mechanism raises the effective marginal costs of rival chip suppliers, even without explicit exclusionary contracts.

## ⚙️ Model Specification

The paper develops a formal vertical model to analyze the interaction between licensing and upstream competition.

### 1. Demand Function

Handset demand is modeled as a function of chip quality ($q_i$) and retail price ($P$). If the OEM uses chip supplier $i \in \{Q, R\}$:

$$
Q_{i}(P) = a + \theta q_{i} - bP
$$

* $a, b > 0$: Demand parameters
* $\theta$: Marginal valuation of performance
* $q_i$: Quality index of chip $i$

### 2. Marginal Cost & Licensing

Under the "no-license/no-chips" regime, the OEM pays a royalty $r$ on all devices, regardless of the chip supplier. The OEM's marginal cost is:

$$
MC_{i} = c_{O} + w_{i} + r
$$

* $c_O$: OEM's non-chip production cost
* $w_i$: Wholesale chip price from supplier $i$
* $r$: Per-device royalty

### 3. OEM Profit Maximization

The OEM chooses a supplier and retail price to maximize operating profit:

$$
\max_{P} \pi_{O} = (P - MC_{i})(a + \theta q_{i} - bP)
$$

Solving for the optimal retail price ($P^*$) yields the equilibrium OEM profit for a given supplier:

$$
\pi_{O}(i;r) = \frac{(a + \theta q_{i} - b(c_{O} + w_{i} + r))^{2}}{4b}
$$

### 4. Upstream Supplier Profits

The distortion arises from the asymmetric profit functions of the suppliers.

**Qualcomm (Integrated Firm):**
Qualcomm collects both chip revenue and royalty revenue. It internalizes the royalty, allowing it to lower $w_Q$ to offset $r$:

$$
\Pi_{Q} = (w_{Q} - c_{Q})Q_{Q}^{\ast} + rQ_{Q}^{\ast}
$$

**Rival Supplier:**
The rival earns only chip margins and cannot offset the royalty burden:

$$
\Pi_{R} = (w_{R} - c_{R})Q_{R}^{\ast}
$$

* $c_Q, c_R$: Suppliers' marginal production costs

## 📊 Methodology & Data

* **Theoretical Framework:** The model proves that because Qualcomm internalizes royalty revenue, it creates an incentive to lower wholesale prices that rivals cannot match, effectively taxing rival chips.
* **Surplus Accounting:** Demonstrates how royalty surcharges reduce gains from trade specifically for rival-OEM pairs.
* **Empirical Illustration:**
    * **Data Sources:** Qualcomm Form 10-K filings, Counterpoint Research, Strategy Analytics.
    * **Key Trend:** Licensing revenue remained insulated from chip competition shocks, and rival market share gains were restricted to lower-value segments, consistent with the model's "margin compression" prediction.

## 📝 Key Findings

1.  **Royalty as Tax:** A per-device royalty functions as a tax on rivals. While formally applied to the OEM, the economic incidence falls on the rival chip supplier through reduced competitiveness.
2.  **Asymmetric Incentives:** The integrated firm (Qualcomm) can strategically offset the royalty to win sales, while the rival cannot, shifting OEM sourcing incentives in favor of the integrated firm.
3.  **Bargaining Dynamics:** High royalties are sustained not necessarily by innovation value alone, but by the asymmetric "disagreement payoffs" where OEMs fear supply disruption.

## 📚 References

* **Primary Case:** *FTC v. Qualcomm*, Ninth Circuit Court of Appeals & District Court findings.
* **Core Literature:** Shapiro, C., & Waehrer, K. (2023). "Using and Misusing Microeconomics: FTC v. Qualcomm".
* **Financial Data:** Qualcomm Historical Financial Results (Licensing and Chip Segment Information).

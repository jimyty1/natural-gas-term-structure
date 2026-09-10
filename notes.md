# Price Discrimination and Limits to Arbitrage, 2014

- Features + effects in LNG market such as shipping.
- One conjecture that gas prices would converge due to sea-based trade.
- Strictly from bilateral long-term contracts to spot + short-term markets. (~25% of LNG sales)
- Price differentials became more pronounced since Fukushima:
  - US ~$3
  - Japan ~$15
  - EU ~$8
- Arbitrage: if price differential > quantity and storage costs → liquid markets.
- LNG producers seem to fail to engage in arbitrage by re-routing European cargoes.
- In a perfectly competitive market, price difference between 2 regions = transport costs.
- Qatar ~30% of global LNG market share.
- Therefore LNG seems to be more tied to exporters' **market power**.

---

## Equalizing Marginal Revenue ≠ Equalizing Price

Equalizing marginal revenue across markets → **revenue is maximized**.

→ Example: target shots when marginal revenues are equalized.

### Marginal Revenue

The extra income a business gets from selling one more unit of a product/service:

$$
MR = \frac{\Delta \text{Total Revenue}}{\Delta \text{Quantity}}
$$

- If a business is in a strong/increasing-demand LNG market → price falls less.
- If price falls less → marginal revenue is closer to price.
- Lerner index gives ~33% to the market.

---

# Profit-Maximizing LNG Exporter

Spot price for producer $k$ in market $l$:

$$
P_l^k
\left(
x_l^k,\,
y_l^k,\,
X_l^{-k},\,
Y_l^{-k};\,
\theta_l
\right)
$$

where:

- $x_l^k$ = short-term LNG sales by producer $k$ in market $l$
- $y_l^k$ = producer $k$'s long-term commitments in market $l$
- $X_l^{-k}$ = short-term LNG sales by all other producers
- $Y_l^{-k}$ = contracted long-term demand
- $\theta_l$ = other factors affecting LNG demand in market $l$, e.g.:
  - coal prices
  - oil prices
  - demand shocks

Producer $k$ has a cost function:

$$
C^k
\left(
\sum_{l=1}^{M}(x_l^k + y_l^k)
\right)
$$

which depends on the sum of producer $k$'s export quantities.

---

## Producer $k$'s Capacity Constraint

Total quantities sold across all $M$ export markets can be subject to a capacity constraint:

$$
q^k \leq Q^k
$$

The producer's profit-maximization problem is:

$$
\max_{\{x_l^k\}_{l=1}^{M}}
\left[
\sum_{l=1}^{M} P_l^k x_l^k
-
C^k
\left(
\sum_{l=1}^{M}(x_l^k+y_l^k)
\right)
-
\sum_{l=1}^{M}T_l^k x_l^k
\right]
$$

subject to:

$$
\sum_{l=1}^{M}(x_l^k+y_l^k) \leq Q^k
$$

where:

$$
T_l^k = \text{transport cost per unit sold to market } l
$$

The producer therefore chooses **how much flexible LNG to send to each market**.

Total spot volume + existing long-term commitments cannot exceed the producer's capacity.

---

# Lagrange Multiplier

A **Lagrangian** is used to find the minimum or maximum of a function subject to constraints.

General form:

$$
\mathcal{L}(x,y,\lambda)
=
f(x,y)-\lambda g(x,y)
$$

where:

- $f(x,y)$ = objective function
- $g(x,y)$ = constraint
- $\lambda$ = **Lagrange multiplier / shadow price**

### Interpretation of $\lambda$

$\lambda$ measures the **marginal value of relaxing the constraint**.

For example, it tells us how much additional profit the producer could make if it had one additional unit of capacity.

For the LNG producer:

$$
\mathcal{L}^k
=
\Pi^k
+
\lambda^k
\left[
Q^k
-
\sum_{l=1}^{M}(x_l^k+y_l^k)
\right]
$$

If the capacity constraint is binding:

$$
\lambda^k > 0
$$

If the producer has spare capacity:

$$
\lambda^k = 0
$$

---

# Optimal LNG Allocation

The optimal output choice $x_l^k$ satisfies the **first-order condition**:

$$
MR_l^k - MC^k - T_l^k - \lambda^k = 0
$$

Rearranging:

$$
\boxed{
MR_l^k = MC^k + T_l^k + \lambda^k
}
$$

where:

- $MR_l^k$ = marginal revenue from selling LNG in market $l$
- $MC^k$ = marginal production cost
- $T_l^k$ = transport cost to market $l$
- $\lambda^k$ = shadow value of production capacity

This means the producer sends LNG to each market until:

> **Marginal revenue = marginal production cost + transport cost + opportunity cost of capacity**

---

## Marginal Revenue and Price Elasticity

Marginal revenue can be expressed using the price elasticity of demand:

$$
\boxed{
MR_l^k
=
P_l^k
\left(
1+\frac{1}{\eta_l^k}
\right)
}
$$

where:

- $P_l^k$ = LNG price received by producer $k$ in market $l$
- $\eta_l^k$ = price elasticity of demand faced by producer $k$ in market $l$

Because demand elasticity differs between markets, producers can have:

$$
P_1 \neq P_2
$$

even when LNG can physically be redirected between those markets.

This provides a mechanism through which an LNG producer with market power can maintain international price differences rather than arbitraging them completely away.

"(A) is rather general: it does not rely on any specific functional-form assumptions
on demand and cost functions (e.g., linear, constant-elasticity, etc.), or on a particular form of competitive conduct in each export markets. Commonly-used models,
e.g., perfect competition, monopoly, Cournot-Nash oligopoly, dominant firm with a
competitive fringe, etc."(pg 12)





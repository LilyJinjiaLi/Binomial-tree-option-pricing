# Binomial-tree-option-pricing
Quant research case study


Consider a multiperiod binomial asset model for an asset S with N periods. Under this particular model, we have the following assumptions:
• the initial price of the asset is 𝑆0=1;
• under the risk-neutral measure, the asset price at period j is 𝑆𝑗=(1+𝑣)𝑆𝑗−1 with probability ½, and 𝑆𝑗=(1−𝑣)𝑆𝑗−1 with probability ½, with 0<𝑣<1; and
• the interest rate associated with borrowing/lending currency for a single time period is 0.

We are asked to do the following:
1. Implement a function which, given v and the strike K of a European call option on the asset S, expiring after N periods, returns its value V.
2. Implement a function which, given the strike K and value V of a European call option on the asset S, expiring after N periods, calibrates v to match this price.
3. Implement a function which, given v and the strike K of an American call option on the asset S, expiring after N periods, returns its value.
4. Implement a function which, given v, returns the expectation of max(𝑆𝑗) for 0≤𝑗≤𝑁.
5. (Optional) Assuming that v is no longer constant, but rather that at period j, the asset price is multiplied with 1± 𝑣𝑗, extend the function from question (2) to calibrate the vector v to a set of at most N European call option prices, where no two options have the same expiration date.

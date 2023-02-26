# Lending_Protocol_LTV

Lending Protocol LtV Dashboard: [Final Product](https://lookerstudio.google.com/reporting/d782e5c1-7f48-4297-86e1-47efb6c0523e)

Dashboard for comparing Loan to Value ratios across Lending Protocols. Submission for Business Analytics on the Blockchain Hackathon hosted by University of Colorado, Boulder and [The Graph](https://thegraph.com/en/).

The idea behind this project is create metrics to measure risk across different lending protocols as each one differs in their own way. While I chose to code up Loan-to-Value ratio, as it is a proven metric that has been used in traditional finance, some ideas for non-traditional metrics for decentralized finance include:

**Closed Position:** Out all the smart contracts, how many have been executed because a borrower has successfully met all the requirements vs. force liquididation.

**[Gini Index](https://en.wikipedia.org/wiki/Gini_coefficient):** While traditionally used to measure income disparity in a country, we can use it in decentralized finance as a guage of legal risk. Having a higher distribution of a token shifts the burden of proof from one company to across the total population of holders.

**Colloateral Compisition:** The compisition of the overall collateral of a lending protocol will provide insights into what a loan is being backed by. Is it mostly stable coins like USDC or is a riskier asset like Dogecoin. Since most lending protocols require over-collaterization this will tells us how much the collateral put up will fluctuate.
- Another interesting analysis would be to see how the collateral compisition changes during bear markets vs. bull runs.

The sample used in this analysis consists of the subgraphs provided by The Graph:

1) **Compound V2 Ethereum:** [Link](https://thegraph.com/hosted-service/subgraph/messari/compound-v2-ethereum)
2) **Aave V3 Ethereum:** [Link](https://thegraph.com/hosted-service/subgraph/messari/aave-v3-ethereum)
3) **Abracadbra Money Ethereum:** [Link](https://thegraph.com/hosted-service/subgraph/messari/abracadabra-money-ethereum)

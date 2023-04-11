# Lending_Protocol_LTV - Hackathon First Place Submission

Lending Protocol Loan-to-Value Ratio Dashboard: **[Final Product](https://lookerstudio.google.com/reporting/d782e5c1-7f48-4297-86e1-47efb6c0523e)**

Dashboard for comparing Loan to Value ratios across Lending Protocols. Submission for Business Analytics on the Blockchain Hackathon hosted by University of Colorado, Boulder and [The Graph](https://thegraph.com/en/).

The idea behind this project is create metrics to measure risk across different lending protocols as each one differs in their own way. Ones I included in this dashboard are:

**[Loan-to-Value ratio](https://www.investopedia.com/terms/m/maximum_loan_to_value_ratio.asp)**: It is a proven metric that has been used in traditional finance, so I thought it was highly applicable here

**Market Confidence**: A measure of which protocols the market trusts the most to put their money into. Divided into % of Amount Borrowed and % of Total Collateral.

Given more than 24 hours worth of time, some other non-traditional metrics for decentralized finance could include:

**Executed Position:** Out of all the smart contracts, how many have been executed because a borrower has successfully met all the requirements versus becuase of a forced liquididation.

**[Gini Index](https://en.wikipedia.org/wiki/Gini_coefficient):** While traditionally used to measure income disparity in a country, we can use it in decentralized finance as a guage of legal risk. Having a higher distribution of a token shifts the burden of proof from one company to across the total population of holders.

**Colloateral Compisition:** The compisition of the overall collateral of a lending protocol will provide insights into what a loan is being backed by. Is it mostly stable coins like USDC (backed by the U.S. Dollar) or is it a riskier asset like Dogecoin or an NFT? Since most lending protocols require over-collaterization this will tells us how much the collateral put up will fluctuate.
- Another interesting analysis would be to see how the collateral compisition changes during bear markets vs. bull runs.

The sample used in this analysis consists of the subgraphs provided by The Graph:

1) **Compound V2 Ethereum:** [Link](https://thegraph.com/hosted-service/subgraph/messari/compound-v2-ethereum)
2) **Aave V3 Ethereum:** [Link](https://thegraph.com/hosted-service/subgraph/messari/aave-v3-ethereum)
3) **Abracadbra Money Ethereum:** [Link](https://thegraph.com/hosted-service/subgraph/messari/abracadabra-money-ethereum)
4) **Aave V2 Ethereum:** [Link](https://thegraph.com/hosted-service/subgraph/messari/aave-v2-ethereum)
5) **CREAM Finance Ethereum:** [Link](https://thegraph.com/hosted-service/subgraph/messari/cream-finance-ethereum)

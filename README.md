# AprioriAl_HighwaybiddingData
## Abstract
Design-bid-build (DBB) is widely used in highway projects, often using low bids to select contractors. However, bid rotation and collusion can reduce competition. This study proposes a novel framework using pattern mining and statistical tests to detect suspicious bidding, demonstrated through a real SHA case study.
## Methodology
This section presents a novel method of detecting red-flag patterns from historical bid tabulation data using frequent itemset mining (FIM) and the Fisher Exact Test. The method includes three main steps:
1) Preparation of a database of the contractors co-occurring in the bidding of past contracts and those winning the contracts from bid tabulation data,
2) Determination of sets of contractors and their frequencies of bidding together by applying an FIM algorithm to the prepared database, and
3) Detection of cases in which the winning proportion of a contractor was improved significantly with the co-occurrence of some particular contractor(s). The Fisher Exact test is used to compare two independent population proportions (i.e., with and without the co-occurrence).
### Data Preparation

![image](https://github.com/user-attachments/assets/238e2256-8746-4db6-8041-a70ca0f174e1)

### Determination of frequencies of contractors bidding together

![image](https://github.com/user-attachments/assets/25af5319-f391-4ded-ae48-53a362fd1a17)

### Detection of red-flag patterns

![image](https://github.com/user-attachments/assets/afbba755-c599-4b6b-864d-f516c5cade61)

## Result and discussion:
Tables 2–4 show red-flag patterns for contractor groups of 2–4. In Table 2, when contractors 121 and 177 bid together, 121 won 48.5% of contracts, versus only 4.5% when bidding alone. This significant difference suggests possible collusion and warrants further investigation.

![image](https://github.com/user-attachments/assets/71416071-931c-4cb6-af4d-80773ddd4458)

In Table 3, Case 5 shows contractor 30 won 83.3% of bids when bidding with contractors 16 and 201, but only 10.8% when bidding without them. This large gap suggests possible collusion or pre-bid coordination to favor contractor 30.

![image](https://github.com/user-attachments/assets/2cb695f3-f11e-4e06-85cd-a1e5138c6ba5)

This study presents a new method using FIM and the Fisher Exact Test to detect red-flag bidding patterns from historical data. It identifies potentially collusive contractors and compares their win rates with and without certain partners. The method works with existing data, is easy to apply, and is adaptable beyond highway projects. Future research could explore project types, sizes, regions, and integrate spatial, temporal, and irregular bid analyses to enhance collusion detection.

# Notes

Regulatory capital is then the amount of capital a bank should have according to a regulation.

Economic capital is the required equity capital which is calculated by their own risk modeling strategy and policy.

The actual capital is then the amount of capital a bank actually holds and is the higher of the economic capital and the regulatory capital.

Note that various types of capital exist, depending upon their loss-absorbing capacity.
- Tier 1 capital typically consists of common stock, preferred stock, and retained earnings.
- Tier 2 capital is of somewhat less quality and is made up of subordinated loans, revaluation reserves, undisclosed reserves, and general provisions.

## Basel I


Important drawbacks of Basel I:
1. The solvency of the debtor was not properly taken into account since the risk weights depended only on the exposure class and not on the obligor or product characteristics. 
2. There was insufficient recognition of collateral guarantees to mitigate credit risk.
3. It offered various opportunities for regulatory arbitrage by making optimal use of loopholes in the regulation to minimize capital. 
4. It considered only credit risk, not operational or market risk.

## Basel II
Basel II Capital Accord consists of three key pillars:
- Pillar 1 covers the minimal capital requirements,
- Pillar 2 is about the supervisory review process, and
- PIllar 3 is market discipline and disclosure.

![Pillars of the Basel II/III Regulation](image.png)

The Basel II Capital Accord foresees three ways to model credit risk:
- the standard approach,
- the foundation internal ratings based approach, and
- the advanced internal ratings based approach.

All quantitative models built under Pillar 1 need to be reviewed by overseeing supervisors.

Key activities to be undertaken in Pillar 2 are the introduction of sound processes to evaluate risk, such as the internal capital adequacy assessment process (ICAAP) and supervisory monitoring.

Finally, once all quantitative risk models have been approved, they can be disclosed to the market. This is covered by Pillar 3.

## Basel III

![alt text](image-1.png)

## Basel Approaches to Credit Risk Modeling
Basically, there are three approaches available:
- the standardized approach,
- the foundation internal ratings based approach,
- the advanced internal ratings based approach.

The approaches differ in terms of their sophistication and level of flexibility related to using internally estimated risk numbers.

### Standardized Approach
Although the standardized approach looks simple and appealing at first sight, it suffers from inconsistencies between ratings of different ECAIs with the accompanying danger of banks' cherry-picking the ECAIs. It also has problems in terms of coverage of various types of exposures. 

### Internal Ratings Based (IRB) Approach
The IRB approach is a more sophisticated approach for quantifying credit risk. It relies on four key risk parameters:
- PD
- EAD
- LGD
- EL ($EL = PD \times EAD \times LGD$)

Basically, there are two subapproaches of the IRB approach:
- the foundation IRB approach
- the advanced IRB appraoch.

In the foundation IRB approach, the PD is estimated internally by the bank, while the LGD and EAD are either prescribed in the Basel Accord or provided by the local regulator. 

In the advanced IRB approach, all three risk parameters, PD, LGD, and EAD, can be estimated internally by the bank itself. Furthermore, regulators provide asset correlations, which measure the degree to which the asset values underlying the credit exposures are correlated. In this setting, the asset correlations are either constant or a monotone function that is declining with increasing PDs.

![Basel Foundation and Advanced IRB Approach](image-2.png)

A distinction is made between the following types of exposure classes:
- corporate,
- retail,
- central governments (sovereigns) and central banks,
- institutions,
- equity exposures,
- securitization positions, and
- other non-credit-obligation assets.

The F-IRB approach is not permitted for retail exposures. Hence, for retail exposures, you can choose either the standard or the A-IRB approach.

Once the PD, LGD, and EAD are known, risk weight functions provided in the Basel Accord or directive can be used to caluclate the regulatory capital.

In essence, capital is set to equal unexpected losses (ULs).

$$\text{Unexpected Losses} = \text{Credit Value-at-Risk} - \text{Expected Losses}$$

Expected losses are provisioned for, and provisions are losses in the P&L statement and hence already netted with the equity account. As a result, the capital of a bank should cover losses that exceed provisions, and these losses are called unexpected losses.

The credit value at risk (VaR) is computed in a similar way as expected losses, with the distinction that PD, LGD, and EAD are stressed to reflect an economic downturn:
- PD is stressed via the concept of a worst-case default rate given a virtual macroeconomic shock based on a confidence level of 99.9 percent and a sensitivity to the macroeconomy that is based on the asset correlation.
- LGD is based on an economic downturn.
- EAD is based on an economic downturn.



### 
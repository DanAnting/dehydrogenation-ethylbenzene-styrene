# Styrene Production: Dehydrogenation of Ethylbenzene
The purpose of this simulation is to explore methods to optimize the purity and yield of styrene via the dehydrogenation of ethylbenzene. ASPEN Plus is used to simulate the catalytic reactor, multiphase separator, and distillation columns. The .bkp are available in the file list with the report. 

Reactin Kinetics:
| Reaction | k_i          | E_{A_i} | K_i       | E_{A_i}     | n               | KEB              | k_i                | KEB             | k_i                |
|----------|--------------|---------|-----------|-------------|-----------------|------------------|--------------------|-----------------|--------------------|
|          | kmolkg-1h-1  | kJ/mol  | bar-1     | kmolkg-1h-1bar-1 | kmolkg-1sec-1Pa-1 | kJ/kmol          |                      | N/m2            | kmolkg-1sec-1(N/m2)-n |
| 1        | 0.854        | 90891.4 | 98.51765139 | 1           | N/A             | 2.372222222e-09  | N/A                | 2.372222222e-09 | N/A                |
| 1.1      | 0.854        | 90891.4 | 98.51765139 | 1           | 0.2258378717    | 2.372222222e-09  | 22583.78717        | 0               |                    |
| 2        | 14.0047      | 207989.23 | 225.4405857 | 1           | N/A             | 3.890194443e-08  | N/A                | 3.890194443e-08 | N/A                |
| 3        | 0.5585       | 91515.26 | 99.19385643 | 2           | N/A             | 0                | N/A                | 0               |                    |
| T        | 873.15       |          |             |             |                 |                 |                    |                 |                    |
| a        | 122725.157   |          |             |             |                 |                 |                    |                 |                    |
| b        | -126.2674    |          |             |             |                 |                 |                    |                 |                    |
| c        | -2.19E-03    |          |             |             |                 |                 |                    |                 |                    |
| DeltaF   | 1.08E+04     |          |             |             |                 |                 |                    |                 |                    |
| R Const. | 8.314462175  |          |             |             |                 |                 |                    |                 |                    |
|          |              |         |           |             |                 |                 |                    |                 |                    |
|          |              | 922.59 |           | KEB         | 8.466         |                 |                    |                 |                    |
|          |              |         |           |             |                 |                 |                    |                 |                    |
|          |              |         |           |             |                 |                 |                    |                 |                    |
| Potassium Promoted Iron Catalyst |              |         |           |             |                 |                 |                    |                 |                    |
| Reaction # | k_i          | E_{A_i} | K_i       | E_{A_i}     | kJ/kmol         |                 |                    |                 |                    |
|            | kmolkg-1h-1  | kJ/mol  | bar-1     | kmolkg-1h-1bar-1 |                |                 |                    |                 |                    |
| 1          | 4.59E+09     | 175.38  | 8.466     | 4.59E+09     | 1.28E+01       | 0.17538         |                    |                 |                    |
| 1-REV      | 0.00E+00     | 175.38  | 287.844   | 0.00E+00     | 0.00E+00       | 0.17538         |                    |                 |                    |
| 2          | 1.06E+15     | 296.29  | 8.466     | 1.06E+15     | 2.94E+06       | 0.29629         |                    |                 |                    |
| 3          | 1.25E+26     | 474.76  | 26.168406 | 1.25E+26     | 3.46E+17       | 0.47476         |                    |                 |                    |
| 4          | 8.02E+10     | 213.78  |           | 8.02E+10     | 2.23E+02       | 0.21378         |                    |                 |                    |
|            |              |         |           |             |                 |                 |                    |                 |                    |
| Parameter | Driving Force Parameter | pa-1   |                 | Driving Force   |                 |                 |                    |                 |                    |
|          | KEB          | 8.466   | 2.136058142 | 846600      |                 | 13.64898361     |                    |                 |                    |
|          | KST          | 34      | 3.526360525 | 3400000     |                 | 15.03928599     |                    |                 |                    |
|          | KH2          | 3.091   | 1.128494663 | 309100      |                 | 12.64142013     |                    |                 |                    |
|          | KEB*KH2      | 26.168406 | 3.264552805 | 2616840.6   |                 | 14.77747827     |                    |                 |                    |
|          | KST*KH2      | 105.094 | 4.654855188 | 10509400    |                 | 16.16778065     |                    |                 |                    |
|          | Keq          | 0.2226088935 |           |             |                 |                 |                    |                 |                    |
|          | KEB/Keq      | 38.03082557 | 3.63839703  |             |                 |                 |                    |                 |                    |
|            |              |         |           |             |                 |                 |                    |                 |                    |
| Potassium Promoted Iron Catalyst |              |         |           |             |                 |                 |                    |                 |                    |
| Reaction # | k_i          | E_{A_i} | K_i       | E_{A_i}     | kJ/kmol         |                 |                    |                 |                    |
|            | kmolkg-1h-1  | kJ/mol  | bar-1     | kmolkg-1h-1bar-1 | 

---
layout: default
---

## Rebuttal to Reviewer 2nGp

### _Table 1.1_  &nbsp; Semantic decoding accuracy


|       | S1    | S2    | S3    | S4    | S5    | sub-001 | sub-002 | sub-003 | sub-004 | sub-005 | UTS01  | UTS02  | UTS03  | UTS05  | UTS06  | UTS07  | UTS08  |
| :---- | :---- | :---- | :---- | :---- | :---- | :------ | :------ | :------ | :------ | :------ | :----- | :----- | :----- | :----- | :----- | :----- | :----- |
| SIM   | 0.745 | 0.747 | 0.754 | 0.748 | 0.752 | 0.758   | 0.764   | 0.767   | 0.760   | 0.764   | 0.832  | 0.833  | 0.836  | 0.826  | 0.838  | 0.834  | 0.830  |
| PCC   | 0.547 | 0.571 | 0.571 | 0.557 | 0.571 | 0.221   | 0.245   | 0.257   | 0.231   | 0.247   | 0.245  | 0.253  | 0.275  | 0.203  | 0.291  | 0.254  | 0.230  |
| R<sup>2</sup> | 0.212 | 0.208 | 0.227 | 0.212 | 0.220 | 0.040   | 0.053   | 0.062   | 0.046   | 0.054   | -0.220 | -0.221 | -0.203 | -0.259 | -0.199 | -0.219 | -0.229 |


### _Table 1.2_  &nbsp;   Upperbound classification accuracy


| Num of stories | 1M1F      | 2M2F      | 3M3F      | 4M4F      |
| -------------- | --------- | --------- | --------- | --------- |
| Num of samples | 595       | 1305      | 2028      | 2474      |
| Upperbound Acc | 0.95±0.03 | 0.97±0.02 | 0.95±0.03 | 0.93±0.03 |


### _Table 1.3_  &nbsp;   Voxel selection

| voxel num     | UTS01     | UTS02     | UTS03     | UTS05     | UTS06     | UTS07     | UTS08     |
| ------------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| all AC voxels | 0.235     | 0.208     | 0.248     | 0.198     | 0.284     | 0.225     | 0.221     |
| 700           | 0.239     | 0.249     | 0.269     | 0.201     | 0.289     | 0.248     | 0.230     |
| 500           | **0.245** | **0.253** | **0.275** | 0.203     | **0.291** | 0.254     | **0.230** |
| 300           | 0.244     | 0.252     | 0.274     | **0.204** | 0.286     | **0.257** | 0.220     |

<br><br>

## Rebuttal to Reviewer AjY4

### _Table 2.1_  &nbsp;  Comparison with fusion baseline

|                | **PCC↑**        | **PSNR↑**        | **FD↓**          | **FAD↓**        | **KL↓**         | **CLAP↑**       |
| -------------- | --------------- | ---------------- | ---------------- | --------------- | --------------- | --------------- |
| coarse-to-fine | **0.405±0.008** | **15.221±0.259** | **11.381±0.619** | **5.164±0.291** | **0.658±0.059** | **0.456±0.015** |
| coarse + fine  | 0.341±0.011     | 14.208±0.194     | 14.047±1.412     | 5.473±0.323     | 0.895±0.119     | 0.407±0.018     |


### _Table 2.2_  &nbsp; Decoding PCC of semantic and acoustic features

|          |  S1   |  S2   |  S3   |  S4   |  S5   | sub-001 | sub-002 | sub-003 | sub-004 | sub-005 | UTS01 | UTS02 | UTS03 | UTS05 | UTS06 | UTS07 | UTS08 |
| :------: | :---: | :---: | :---: | :---: | :---: | :-----: | :-----: | :-----: | :-----: | :-----: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Semantic | 0.547 | 0.571 | 0.571 | 0.557 | 0.571 |  0.221  |  0.245  |  0.257  |  0.231  |  0.247  | 0.245 | 0.253 | 0.275 | 0.203 | 0.291 | 0.254 | 0.230 |
| Acoustic | 0.180 | 0.188 | 0.174 | 0.163 | 0.201 |  0.045  |  0.049  |  0.058  |  0.035  |  0.055  | 0.071 | 0.075 | 0.086 | 0.058 | 0.082 | 0.071 | 0.056 |


### _Table 2.3_ &nbsp;  Comparison with end-to-end baseline

|             | **PCC↑**        | **PSNR↑**        | **FD↓**         | **FAD↓**        | **KL↓**         | **CLAP↑**       |
| ----------- | --------------- | ---------------- | --------------- | --------------- | --------------- | --------------- |
| multi-stage | **0.405±0.008** | **15.221±0.259** | 11.381±0.619    | 5.164±0.291     | 0.658±0.059     | 0.456±0.015     |
| end-to-end     | 0.346±0.001     | 14.743±0.018     | **7.882±0.105** | **3.669±0.077** | **0.562±0.011** | **0.484±0.001** |

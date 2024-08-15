### BBox Dataset

**1. NIH Dataset**: 

- `Atelectasis(180)`

- `Effusion(153)`

- `Cardiomegaly(146)`

___

**2. VinBig Data**

- `Atelectasis(279)`

- `Effusion(2476)`

- `Cardiomegaly(5427)`

There are 10 Radiologist in dataframe like below.

![rad](https://github.com/user-attachments/assets/eba67e2e-4c9d-4ba0-99cc-44ee84425559)


#### => After Choose One Radiologist for each label

 - `Atelectasis`: 279 -> 186

- `Effusion`: 2476 -> 1032
- 
- `Cardiomegaly`: 5427 -> 2300


___

**Final Dataset**

- `Atelectasis(366)`

  => Vin(186) + NIH(180)

- `Effusion(500)`

  => Vin(347) + NIH(153)

- `Cardiomegaly(500)`

  => Vin(354) + NIH(146)

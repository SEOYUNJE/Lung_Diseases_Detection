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

So We need to apply Weighted Box Fusion(WBF) 

![image](https://github.com/user-attachments/assets/46ab3a42-c31e-409a-b872-c1a03bd4dbe6)


#### => After Choose One Radiologist for each label

 - `Atelectasis`: 279 -> 123

- `Effusion`: 2476 -> 824

- `Cardiomegaly`: 5427 -> 2113


___

**Final Dataset**

- `Atelectasis(303)`

  => Vin(123) + NIH(180)

- `Effusion(500)`

  => Vin(347) + NIH(153)

- `Cardiomegaly(500)`

  => Vin(354) + NIH(146)

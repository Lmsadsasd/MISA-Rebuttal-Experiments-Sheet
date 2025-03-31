# MISA-Rebuttal-Experiments-Sheet
| Method    | GSM8K    | SVAMP    | AQUA    | MAWPS | Avg. |
| -------- | -------- | -------- | --------| --------|--------|
| BAdam(ascending)   | 71.9 |  82.3 |  59.4 | 92.4|74|
| BAdam(asd.,5-shot)   | 74.2 |  83.1 |  62.2 | 91.3|77.7|
| BAdam(random)   | 80.2 |  85.9 |  65.1 | 92.4|80.9|

袁坤是我爹
|Model| Method|MMLU| MMLU-pro | MT-Bench|
|--------| -------- | -------- | -------- | -------- |
|TinyLLaMA|LISA|**26.02**|11.59|**2.57**|
||BAdam|25.27|11.44|2.42|
||MISA|25.40|**11.65**|**2.57**|

|Model| Method|MMLU| MMLU-pro | MT-Bench|
|--------| -------- | -------- | -------- | -------- |
|LLaMA2-7B|LISA|46.21|**20.85**|4.94|
||BAdam|45.61|20.68|4.81|
||MISA|**46.27**|20.69|**5.13**| 

|Model| Method|MMLU| MMLU-pro | MT-Bench|
|--------| -------- | -------- | -------- | -------- |
|Mistral-7B|LISA|62.09|32.83|4.85|
||BAdam|62.11|32.79|5.03|
||MISA|**62.90**|**33.44**|**5.19**|

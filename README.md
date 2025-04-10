# MISA-Rebuttal-Experiments-Sheet
**4. About Table 3.** 
 | Method    | GSM8K    | SVAMP    | AQUA    | MAWPS | Avg. |
| -------- | -------- | -------- | --------| --------|--------|
| BAdam(ascending)   | 71.9 |  82.3 |  59.4 | 92.4|74|
| BAdam(asd.,5-shot)   | 74.2 |  83.1 |  62.2 | 91.3|77.7|
| BAdam(random)   | 80.2 |  85.9 |  65.1 | 92.4|80.9|

**Table 1**: Comparison of different BAdam's fine-tuning methods on Qwen-2.5-7b across four arithmetic reasoning tasks.

 **5. Reproduce LISA results.** 
**Notation**: The results for LISA, GaLore, and LoRA in MMLU and MT-Bench are cited from LISA, while others are reproduced by us. MT-Bench evaluation was conducted using GPT-4.

|Model| Method|MMLU| MMLU-pro | MT-Bench|
|--------| -------- | -------- | -------- | -------- |
|TinyLLaMA|LISA|**26.02**|11.59|**2.57**|
||BAdam|25.27|11.44|2.42|
||MISA|25.40|**11.65**|**2.57**|

**Table 1**: Comparison of fine-tuning methods on TinyLLaMA across MMLU, MMLU-pro, and MT-Bench.

|Model| Method|MMLU| MMLU-pro | MT-Bench|
|--------| -------- | -------- | -------- | -------- |
|LLaMA2-7B|LISA|46.21|**20.85**|4.94|
||BAdam|45.61|20.68|4.81|
||MISA|**46.27**|20.69|**5.13**| 

**Table 2**: Comparison of fine-tuning methods on LLaMA2-7B across MMLU, MMLU-pro, and MT-Bench.

|Model| Method|MMLU| MMLU-pro | MT-Bench|
|--------| -------- | -------- | -------- | -------- |
|Mistral-7B|LISA|62.09|32.83|4.85|
||BAdam|62.11|32.79|5.03|
||MISA|**62.90**|**33.44**|**5.19**|

**Table 3**: Comparison of fine-tuning methods on Mistral-7B across MMLU, MMLU-pro, and MT-Bench.

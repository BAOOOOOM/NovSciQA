# NovSciQA

**NovSciQA** is a science question answering benchmark introduced in  
**“Learn to Understand: Knowledge Exemplification via Multi-Agent Cooperation for Science Question Answering”**,  
published in **IEEE Transactions on Knowledge and Data Engineering (TKDE)**.

The dataset is designed to evaluate whether models can **truly understand and apply scientific knowledge**, rather than relying on memorization or pattern matching.


## Key Advantages

### 🧠 Eliminating Memorization Effects
Since the underlying knowledge in NovSciQA is **entirely novel**, the dataset effectively **eliminates the influence of memorized answers**.  
Model performance therefore reflects **knowledge understanding and application**, rather than recall of seen facts.

---

### 🧩 Reasoning-Oriented Incorrect Answers
Incorrect options are **human-constructed based on explicit incorrect reasoning processes**, not random or superficial distractors.  
This design makes the dataset particularly effective for evaluating whether models can **identify and avoid plausible but flawed reasoning paths**.

---

### 🔍 Evaluating Understanding Beyond Accuracy
NovSciQA distinguishes between answers obtained through **genuine reasoning** and those produced by **spurious shortcuts**, enabling analysis that goes beyond final accuracy and focuses on **how answers are derived**.

---

### ⚡ Compact yet Diagnostic
The dataset is **moderate in size but high in diagnostic value**, allowing researchers to conduct meaningful evaluations with **low computational and experimental overhead**, making it suitable for rapid iteration and method comparison.

---

### 🔗 Complementary to Existing Science QA Benchmarks
NovSciQA is designed to **complement existing science QA datasets** (e.g., ARC, ScienceQA).  
While prior benchmarks often mix reasoning ability with memorized knowledge, NovSciQA provides an **orthogonal evaluation setting** that isolates **novel knowledge understanding and reasoning robustness**.

---

## Learn More

For a detailed description of the dataset construction, motivation, and evaluation results,  
please refer to the paper:

**Learn to Understand: Knowledge Exemplification via Multi-Agent Cooperation for Science Question Answering**

---

## 📌 Citation

If you find this repository or the **NovSciQA dataset** useful for your research, please consider citing our paper:

```bibtex
@ARTICLE{11365952,
  author={Bao, Meikai and Zhang, Kai and Liu, Xukai and Liu, Qi and Zhao, Hongke and Chen, Enhong},
  journal={IEEE Transactions on Knowledge and Data Engineering}, 
  title={Learn to Understand: Knowledge Exemplification via Multi-Agent Cooperation for Science Question Answering}, 
  year={2026},
  volume={},
  number={},
  pages={1-13},
  doi={10.1109/TKDE.2026.3658068}}

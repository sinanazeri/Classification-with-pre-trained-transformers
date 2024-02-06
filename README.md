# Classification-with-pre-trained-transformers

https://arxiv.org/pdf/2311.10609.pdf

![image](https://github.com/sinanazeri/Classification-with-pre-trained-transformers/assets/121966646/ca00ca24-5347-4b7f-b052-9ab023c3727f)


The key findings and observations are:

1. **Performance on Different Data Sizes**: TabPFN shows impressive performance on smaller datasets, likely benefiting from transfer learning and its pre-fitted nature. However, as the dataset size increases, CatBoost outperforms TabPFN, which aligns with expectations given their respective designs.

2. **Comparison Choice and Research Support**: The study interestingly focuses exclusively on comparing TabPFN with CatBoost, even citing research that positions CatBoost as a superior model for tabular data, particularly in Kaggle competitions. This choice is supported by real-world observations and research, validating the comparison.

3. **Context with Other Models**: The author notes personal experiences with XGBoost and LightGBM, which, while effective, did not match CatBoost's performance in their trials. This context further strengthens the relevance of the TabPFN vs. CatBoost comparison.

4. **Implications for TabPFN**: The study suggests that TabPFN's ability to outdo CatBoost in scenarios with limited data implies its potential superiority over other models like XGBoost and LightGBM in such situations. This positions TabPFN as a particularly notable tool for small datasets.

Overall, the summary underscores TabPFN's potential in handling small datasets and its special significance in the landscape of machine learning models, especially when compared to established models like CatBoost.


![image](https://github.com/sinanazeri/Classification-with-pre-trained-transformers/assets/121966646/660d207c-2d38-43e0-aa34-48901433aa57)

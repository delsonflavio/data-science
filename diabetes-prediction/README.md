# What do your blood sugars tell you?

## 📖 Background

Diabetes mellitus remains a global health issue, causing several thousand people to die each day from this single condition. Finding and avoiding diabetes in the earlier stages can help reduce the risk of serious health issues such as circulatory system diseases, kidney malfunction, and vision loss.

The goal of this project was developing a predictive model for effectively detecting potential Diabetes cases, ideally, before commencing preventive treatment.

## Summary
This project applies a data-driven methodology to create a predictive model to effectively detect potential cases of diabetes. In the first step, the most important factors that affect the outcome of diabetes are determined. The second step was to create interactive graphs to visualize the relationship between diabetes and the factors determined from the previous step. Then, some classification models were applied and the best performing model was using DecisionTreeClassifier. And in the end, we applied this model to identify the risk of a 54-year-old person, length 178 cm and weight 96 kg, and glucose levels of 125 mg/dL of having diabetes.

## 💾 The data

The [dataset](data/README.md) contains diagnostic measurements that are associated with diabetes, which were collected from a population of Pima Indian women. The data includes various medical and demographic attributes, making it a well-rounded resource for predictive modeling.

## Tools
- Python, Pandas
- Matplotlib, seaborn

## Conclusion
In the case provided, the model identified a 54% probability of the individual having diabetes, according to the model's estimate.

We can also state that the applied DecisionTreeClassifier model is quite accurate and can predict whether an individual has diabetes with an precision rate of 78%.

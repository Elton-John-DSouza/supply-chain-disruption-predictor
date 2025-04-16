# supply-chain-disruption-predictor
Description: Developed a predictive model to identify potential shipping delays, enabling businesses to take proactive measures such as rerouting shipments, adjusting inventory, and negotiating with suppliers.
Analyzed the DataCoSupplyChainDataset from Kaggle to classify shipments as on-time or delayed, helping businesses respond quickly and minimize operational risks.
Approach: Data Preprocessing: Handled missing values using KNN imputation and applied Factor Analysis to group correlated features, improving model interpretability.
Model Development: Tested multiple models and found LightGBM to be the most effective, achieving 88.36% accuracy due to its ability to handle categorical features efficiently.
Evaluation & Impact: Evaluated model performance using the ROC-AUC curve, ensuring robust classification and reliable decision-making. The model's predictions support optimization of logistics, reduction in operational costs, and enhancement of overall supply chain resilience.
Challenges & Solutions: Identified and resolved critical data leakage issues to ensure data integrity. Employed robust feature engineering and selection techniques to efficiently manage a large-scale dataset and enhance model performance.

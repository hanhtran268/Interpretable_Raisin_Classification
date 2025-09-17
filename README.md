# Interpretable_Raisin_Classification

## 📌 Project Summary  
This project explored **model interpretability** using the [Raisin Binary Classification dataset](https://www.kaggle.com/datasets/nimapourmoradi/raisin-binary-classification).  
The dataset contains geometric features of raisin images, with the goal of classifying them into two categories.  
The main objective was not only to build predictive models but also to **interpret the decision-making process** behind their predictions.  

## 🔧 Implemented Models  
- 📊 **Logistic Regression** – captured linear relationships with clear key influencers (MajorAxisLength, ConvexArea, Perimeter).  
- 🤖 **Neural Network** – modeled complex, non-linear interactions with more distributed feature importance (notably MinorAxisLength).  

## 🛠️ Interpretability Techniques  
- 📈 **PDP & ICE** – showed feature effects and individual interactions across ranges.  
- ⚡ **ALE** – improved accuracy for correlated features with faster computation.  
- 📐 **Ridge Surrogate** – provided a simplified linear explanation of complex models.  
- 🎯 **SHAP** – delivered detailed local & global feature attributions.  

## ✅ Key Findings  
- Logistic Regression offered **simple and stable feature effects**, easy to explain.  
- Neural Networks captured **richer, non-linear dynamics** but were harder to interpret.  
- SHAP gave the **most granular insights**, though computationally expensive.  
- ALE provided a good balance between **accuracy and interpretability**.  

## 🏆 Conclusion  
The project highlights the trade-off between **accuracy and interpretability**:  
- Logistic Regression → easier to interpret, stable.  
- Neural Network → more complex, required advanced interpretability tools.  

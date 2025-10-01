# _002_Mushroom_Classification_Custom_SLR

## 🍄 Mushroom Classification — Edible or Existential Crisis?

### Description
This project is about teaching a machine to decide whether a mushroom is edible, poisonous, or just pretending to be both while laughing at our fragile mortality. Using the classic **UCI Mushroom Dataset**, a simple linear regression model (my very own `myslr` implementation, wrapped in scikit-learn style) tries to predict if a mushroom wants to be your dinner… or your last dinner.  

Instead of blindly trusting machine learning libraries, I coded my own barebones **Simple Linear Regression** from scratch, then wrapped it in a pipeline with preprocessing, feature selection, and evaluation. Because why not reinvent the wheel, especially if the wheel is poisonous and growing in the woods?

---

### Features
- **Custom Simple Linear Regression (`myslr`)**  
  Because sometimes you want to suffer through the math yourself.  
- **Pipeline with Preprocessing**  
  One-hot encoding, imputing, and feature selection — mushrooms may be messy, but code doesn’t have to be.  
- **SelectKBest** to discover the **most existentially relevant mushroom feature** (spoiler: it’s odor).  
- **Performance Metrics** (MSE, R², Accuracy, Confusion Matrix) to help you decide if you can trust the model… or nature.  

---

### Results
- Best single predictor: `odor` (apparently, mushrooms smell more reliable than your ex).  
- Accuracy: ~88% with a simple threshold.  
- False negatives (poison predicted as edible): very low, which is good, because death is a bad edge case.

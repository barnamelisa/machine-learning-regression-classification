# Machine Learning - Probleme de Regresie și Clasificare

Acest proiect conține două probleme distincte din domeniul învățării automate: una de **regresie** și una de **clasificare**, ambele abordate folosind o varietate de algoritmi de tip ensemble și non-ensemble. Scopul este antrenarea, evaluarea și explicarea modelelor pe baza unor date reale.

---

## 📈 Problema 1: Regresie

### 🔍 Descriere
Am ales o problemă de regresie reală: **[numele problemei, ex: Predicția prețului biletelor de avion]**, unde obiectivul este de a prezice valori numerice continue.

### 🗂️ Date
Setul de date utilizat provine de la **[sursa datasetului]** și conține informații despre **[descrierea variabilelor]**.

### 🤖 Algoritmi folosiți
Am antrenat următorii algoritmi de regresie:
- Linear Regression
- K-Nearest Neighbors
- Support Vector Machine
- Decision Trees
- Random Forest
- XGBoost (Extreme Gradient Boosting)
- CatBoost (Categorical Boosting)
- Explainable Boosting Machine (EBM)

### 📊 Metrici de evaluare
Pentru a evalua performanța fiecărui regresor, am folosit:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

### ⚙️ Optimizarea hiperparametrilor
Pentru fiecare model, am optimizat hiperparametrii cei mai relevanți folosind:
- `GridSearchCV`
- `BayesSearchCV` (din `scikit-optimize`)

### 🧠 Interpretabilitate modele
Am folosit:
- **SHAP** (SHapley Additive exPlanations)
- **LIME** (Local Interpretable Model-Agnostic Explanations)

pentru a explica caracteristicile de intrare cu cel mai mare impact asupra predicțiilor. Pentru EBM, am folosit graficele explicabile deja integrate.

---

## 🧪 Problema 2: Clasificare

### 🔍 Descriere
Am ales o problemă de clasificare reală: **[numele problemei, ex: Detectarea diabetului]**, cu **[tipul de clasificare: binară/multiclas]**.

### 🗂️ Date
Datele provin din **[sursa datasetului]** și includ **[descriere generală a caracteristicilor și claselor]**.

### 🤖 Algoritmi folosiți
Am antrenat următorii algoritmi de clasificare:
- Logistic Regression
- Naive Bayes
- Support Vector Machine
- K-Nearest Neighbors
- Decision Trees
- Random Forest
- XGBoost
- CatBoost
- Explainable Boosting Machine (EBM)

### 📊 Metrici de evaluare
Fiecare model a fost evaluat folosind:
- Accuracy
- Precision
- Recall
- F1-Score
- Area Under the Curve (AUC) – împreună cu grafic ROC
- Confusion Matrix

### ⚙️ Optimizarea hiperparametrilor
Optimizare realizată cu:
- `GridSearchCV`
- `BayesSearchCV`

### 🧠 Interpretabilitate modele
- SHAP și LIME au fost utilizate pentru a interpreta modelele (cu excepția EBM).
- Pentru EBM, am folosit interpretabilitatea nativă: grafic ponderi pentru caracteristici.

---

## 📝 Observații finale

- Fiecare Jupyter Notebook conține explicații detaliate în celule Markdown.
- Am evidențiat pașii realizați, de la procesarea datelor la interpretarea rezultatelor.
- Graficele generate ajută la o înțelegere mai clară a performanței modelelor și a factorilor determinanți ai predicțiilor.

---

## ✅ Cerințe îndeplinite

- [x] Alegere și justificare probleme reale (regresie + clasificare)
- [x] Antrenare modele ML relevante
- [x] Evaluare cu metrici standard
- [x] Optimizare hiperparametri (GridSearchCV, BayesSearchCV)
- [x] Interpretabilitate (SHAP, LIME, EBM)
- [x] Explicații în notebook-uri (.ipynb)

---


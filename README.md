# ML_Classification_Cardiovascular_Risk_Prediction

The goal of this project is to use machine learning techniques to predict the 10-year risk of future coronary heart disease (CHD) in patients using data from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts.

The dataset is from an ongoing cardiovascular study on residents of the town of Framingham,Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients’ information.
It includes over 4,000 records and 15 attributes.
Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk factors.

Dataset used in this project : 
data_cardiovascular_risk : https://drive.google.com/file/d/1f4FtKN9txiHAvg9APxPfxk87HMTWmmOG/view?usp=sharing



 **The dataset contains patient's information. (Each attribute is a potential risk factor). There are both demographic, behavioral, and medical risk factors.**


**Attribute Information:**

**1).Demographic:**

* **Sex**: male or female("M" or "F")

* **Age**: Age of the patient; (Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)

* **Education**: No further information provided

**2).Behavioral:**

* **is_smoking**: whether or not the patient is a current smoker ("YES" or "NO")

* **Cigs Per Day**: the number of cigarettes that the person smoked on average in one day.(can be
considered continuous as one can have any number of cigarettes, even half a cigarette.)

**3).Medical( history):**

* **BP Meds**: whether or not the patient was on blood pressure medication (Nominal)

* **Prevalent Stroke**: whether or not the patient had previously had a stroke (Nominal)

* **Prevalent Hyp**: whether or not the patient was hypertensive (Nominal)

* **Diabetes**: whether or not the patient had diabetes (Nominal)
Medical(current)

* **Tot Chol**: total cholesterol level (Continuous)

* **Sys BP**: systolic blood pressure (Continuous)

* **Dia BP**: diastolic blood pressure (Continuous)

* **BMI**: Body Mass Index (Continuous)

* **Heart Rate**: heart rate (Continuos)

* **Glucose**: glucose level (Continuous)

**Predict variable (desired target)**

* **TenYearCHD** :10-year risk of coronary heart disease CHD (binary: “1”, means “Yes”, “0” means “No”)


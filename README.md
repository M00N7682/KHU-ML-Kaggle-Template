# ML Midterm Kaggle Template 🧠📊

학교 머신러닝 과목 중간고사 오픈북 시험 대비를 위한 **Kaggle-style 문제 해결 템플릿**입니다.  
Logistic Regression과 KNN 알고리즘을 기반으로, 다양한 하이퍼파라미터 튜닝 기법을 적용하여 최적 성능을 찾아 test set을 예측하고 제출 파일까지 만드는 전 과정을 포함합니다.

---

##  특징

-  `GridSearchCV`, `RandomizedSearchCV`, `Optuna` 세 가지 튜닝 방식
-  `Logistic Regression`, `KNN` 모델 대응
-  `train/test/sample_submission.csv` 구조의 Kaggle-style 문제에 바로 적용 가능
-  성능 비교 → 최적 모델 선택 → 제출 파일 생성까지 한 번에

---

## 🛠 사용 방법

1. `train.csv`, `test.csv`, `sample_submission.csv` 파일을 같은 폴더에 넣습니다.
2. Jupyter Notebook을 실행합니다.
3. 타겟 컬럼명(예: `species`)만 필요에 따라 수정합니다.
4. 모든 셀을 실행하면 `submission.csv` 파일이 자동 생성됩니다.

---

## 💡 파일 설명
| `KHU_ML_Midterm_Logistic_Version.ipynb` | 로지스틱 회귀 기반 최적화 템플릿 |
| `KHU_ML_Midterm_KNN_Version.ipynb` | KNN 기반 최적화 템플릿 |

## 📚 사용 기술

- Python (Scikit-Learn, Optuna)
- Jupyter Notebook
- pandas, numpy 등 기본 라이브러리

---

## 🙋‍♂️ 만든 사람

- 경희대학교 경영학과 머신러닝 중간고사 Kaggle 실기 준비용  
- 더 많은 알고리즘 추가 예정 (SVM, RandomForest 등)

---

제가 오픈북 시험에 활용하기 위해 만든 자료입니다.  
Fork해서 자유롭게 쓰고, 데이터셋만 바꿔서 제출하세요!

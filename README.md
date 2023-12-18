# DACON 제 1회 AI 신약개발 경진대회

2023.09 머신러닝 공부 시작

SMILES를 기반으로 약물 저분자의 대사안정성 예측 시도. + DeepChem의 GCN 이용

Colab을 이용하였기에 대부분 IPYNB 파일임.

**대사_안정성_예측_제출용_스크립트** 

말그대로 대회에 참여한 Colab 코드
간단한 EDA
모델 : 구조 기반의 feature 계산후(rdkit) RF 및 XGB 머신러닝 예측  / Mol2Vec을 통한 1D-CNN 이용 예측 / GCN 예측 -> Stacking


**대사_안정성_예측_Only_SMILES**

대회에서 주어진 Feature을 쓰지 않고 SMILES와 Label만 이용하여 예측 수행. <- 예측력은 떨어지지만 편리하다.

대회에 사용한 코드들을 객체화하여 **Metabolism_only_smiles**에 저장 이후 Colab에서 Smiles 데이터프레임만 기입하면 예측을 수행하도록 함.(*가중치는 업로드하지않음.*)

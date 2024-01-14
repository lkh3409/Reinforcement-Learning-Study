# 강화학습 기초부터 응용까지
🤖 강화학습 초짜들이 만나 정리한 스터디 기록

강화학습의 'ㄱ' 자도 모르는 4명이 만나 방학동안 공부한 내용을 기록합니다. 처음 강화학습을 공부하는 사람들도 이해하기 쉽게 내용을 정리하고자 합니다. `프로그래머를 위한 강화학습` 교재를 기반으로 하며, 다른 여러 학습자료를 활용하여 내용을 구성하였습니다. 

* **Period** : 2024/01/09 - 2024/02/26 (두 달)

<br>

## 📁 Contents
**1. 강화학습 기본 개념**
* [마코프 속성과 마코프 연쇄](https://github.com/LimSoYeong/Reinforcement-Learning-Study/blob/main/1.%20%EA%B0%95%ED%99%94%ED%95%99%EC%8A%B5%20%EA%B8%B0%EB%B3%B8%20%EA%B0%9C%EB%85%90/1-1.%20%EB%A7%88%EC%BD%94%ED%94%84%20%EC%86%8D%EC%84%B1%EA%B3%BC%20%EB%A7%88%EC%BD%94%ED%94%84%20%EC%97%B0%EC%87%84.md)
* [마코프 보상과정(MRP)와 벨만 방정식(Bellman Equation)](https://github.com/LimSoYeong/Reinforcement-Learning-Study/blob/d2c10b89fdaa7939b3d378b2457b464d3e7f1d67/1.%20%EA%B0%95%ED%99%94%ED%95%99%EC%8A%B5%20%EA%B8%B0%EB%B3%B8%20%EA%B0%9C%EB%85%90/1-2.%20%EB%A7%88%EC%BD%94%ED%94%84%20%EB%B3%B4%EC%83%81%EA%B3%BC%EC%A0%95(MRP)%EC%99%80%20%EB%B2%A8%EB%A7%8C%20%EB%B0%A9%EC%A0%95%EC%8B%9D(Bellman%20Equation).md)

**2. 강화학습 기본 알고리즘**
* [마코프 결정과정(MDP, Markov Decisioin Process)](https://github.com/LimSoYeong/Reinforcement-Learning-Study/blob/d2c10b89fdaa7939b3d378b2457b464d3e7f1d67/2.%20%EA%B0%95%ED%99%94%ED%95%99%EC%8A%B5%20%EA%B8%B0%EB%B3%B8%20%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98/2-1.%20%EB%A7%88%EC%BD%94%ED%94%84%20%EA%B2%B0%EC%A0%95%EA%B3%BC%EC%A0%95(MDP%2C%20Markov%20Decisioin%20Process).md)
* [MDP 행동 가치 함수(Q함수)와 MDP 최적 가치 함수](https://github.com/LimSoYeong/Reinforcement-Learning-Study/blob/d2c10b89fdaa7939b3d378b2457b464d3e7f1d67/2.%20%EA%B0%95%ED%99%94%ED%95%99%EC%8A%B5%20%EA%B8%B0%EB%B3%B8%20%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98/2-2.%20MDP%20%ED%96%89%EB%8F%99%20%EA%B0%80%EC%B9%98%20%ED%95%A8%EC%88%98(Q%ED%95%A8%EC%88%98)%EC%99%80%20MDP%20%EC%B5%9C%EC%A0%81%20%EA%B0%80%EC%B9%98%20%ED%95%A8%EC%88%98.md)
* [정책 평가와 정책 제어 / 모델 기반과 모델 프리](https://github.com/LimSoYeong/Reinforcement-Learning-Study/blob/d2c10b89fdaa7939b3d378b2457b464d3e7f1d67/2.%20%EA%B0%95%ED%99%94%ED%95%99%EC%8A%B5%20%EA%B8%B0%EB%B3%B8%20%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98/2-3.%20%EC%A0%95%EC%B1%85%20%ED%8F%89%EA%B0%80%EC%99%80%20%EC%A0%95%EC%B1%85%20%EC%A0%9C%EC%96%B4%2C%20%EB%AA%A8%EB%8D%B8%20%EA%B8%B0%EB%B0%98%EA%B3%BC%20%EB%AA%A8%EB%8D%B8%20%ED%94%84%EB%A6%AC.md)
* [다이내믹 프로그래밍](https://github.com/LimSoYeong/Reinforcement-Learning-Study/blob/d2c10b89fdaa7939b3d378b2457b464d3e7f1d67/2.%20%EA%B0%95%ED%99%94%ED%95%99%EC%8A%B5%20%EA%B8%B0%EB%B3%B8%20%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98/2-4.%20%EB%8B%A4%EC%9D%B4%EB%82%B4%EB%AF%B9%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D.md)
* [몬테카를로 방법](https://github.com/LimSoYeong/Reinforcement-Learning-Study/blob/main/2.%20%EA%B0%95%ED%99%94%ED%95%99%EC%8A%B5%20%EA%B8%B0%EB%B3%B8%20%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98/2-5.%20%EB%AA%AC%ED%85%8C%EC%B9%B4%EB%A5%BC%EB%A1%9C%20%EB%B0%A9%EB%B2%95.md)
* [TD와 SARSA]()
* [Q-Learning]()


<br>

## 🧑‍💻 Contributors
임소영 | 이강훈 | 조수현 | 한주상 | 
:----: | :----: | :----: | :----: | 
<img src="https://github.com/LimSoYeong/NEO-K-means/assets/89073323/87f6b929-832d-4b2a-95d0-ca11b96fdb26" width="100" height="100"/> | <img src="https://github.com/LimSoYeong/Reinforcement-Learning-Study/assets/89073323/d1b00fe3-daba-49c7-803f-5475893c7ef7" width="100" height="100"/> |  <img src="https://github.com/LimSoYeong/Reinforcement-Learning-Study/assets/89073323/0f75b02d-6630-4cce-8351-1abb1a54cadd" width="100" height="100"/> |  <img src="https://github.com/LimSoYeong/Reinforcement-Learning-Study/assets/89073323/def65803-c0ab-4a3e-9e7d-603b9f585700" width="100" height="100"/> | 
<a href="https://github.com/LimSoYeong"><img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=Github&logoColor=white"/></a> | <a href="https://github.com/lkh3409"><img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=white"/></a> | <a href="https://github.com/SOOsuhyuncho"><img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=white"/></a> | <a href="https://github.com/H-Software224"><img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=white"/></a> |

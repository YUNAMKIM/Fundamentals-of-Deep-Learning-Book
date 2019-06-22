# Fundamentals of Deep Learning

This repository is the code companion to [Fundamentals of Deep Learning](https://www.amazon.com/Fundamentals-Deep-Learning-Next-Generation-Intelligence/dp/1491925612 "Fundamentals of Deep Learning") by [Nikhil Buduma](https://github.com/darksigma "Nikhil Buduma") and [Nicholas Locascio](https://github.com/nicholaslocascio "Nicholas Locascio"). Contributions to the text and code have also been made by [Mostafa Samir](https://github.com/Mostafa-Samir "Mostafa Samir"), [Surya Bhupatiraju](https://github.com/suryabhupa "Surya Bhupatiraju"), and [Anish Athalye](https://github.com/anishathalye "Anish Athalye"). All algorithms are implemented in [Tensorflow](https://www.tensorflow.org/ "Tensorflow"), Google's machine intelligence library.

## Guide to the repository

Due to recent changes in the Tensorflow library, specifically the migration to the 1.0 API version, the original code in this repository requires an update. If you are running a pre 1.0 version of Tensorflow, the original code files are contained in the `archive/` folder of this repository. We are now beginning the process of migrating this repository into the 1.0 version of Tensorflow and re-organizing the examples. This work is currently in progress and can be found in the `fdl_examples/` folder. The current state of the migration is summarized here:

* Chapter 3
  * Logistic regression (MNIST)
  * Multilayer perceptron (MNIST)
* Chapter 4
  * Linear interpolation of MLP network (MNIST) 
* Chapter 5
* Chapter 6
* Chapter 7
* Chapter 8
* Chapter 9

## Setting up your development environment


http://www.yes24.com/Product/Goods/58707156?scode=032&OzSrank=5

## 목차
## CHAPTER 1 신경망
_1.1 지능형 기계 만들기	
_1.2 기존 컴퓨터 프로그램의 한계	
_1.3 머신러닝의 작동 원리	
_1.4 뉴런	
_1.5 뉴런으로 선형 퍼셉트론 표현하기	
_1.6 전방향 신경망	
_1.7 선형 뉴런과 그 한계	
_1.8 시그모이드, tanh, ReLU 뉴런 
_1.9 소프트맥스 출력층	
_1.10 요약 

## CHAPTER 2 전방향 신경망 학습
_2.1 패스트푸드 문제	
_2.2 경사 하강법	
_2.3 델타 규칙과 학습률	
_2.4 시그모이드 뉴런의 경사 하강법	
_2.5 역전파 알고리즘	
_2.6 확률적 경사 하강법과 미니배치 경사 하강법	
_2.7 테스트 데이터와 검증 데이터 그리고 과적합	
_2.8 신경망에서 과적합 막기	
_2.9 요약	

## CHAPTER 3 텐서플로로 신경망 구현하기
_3.1 텐서플로란?	
_3.2 텐서플로와 대안들을 어떻게 비교할까?	
_3.3 텐서플로 설치하기	
_3.4 텐서플로 변수 만들기와 조작하기	
_3.5 텐서플로 연산	
_3.6 placeholder 텐서	
_3.7 텐서플로의 세션	
_3.8 변수 범위 탐색과 변수 공유	
_3.9 CPU와 GPU로 모델 관리하기	
_3.10 텐서플로에서 로지스틱 회귀 모델 지정하기	
_3.11 로지스틱 회귀 모델 기록하기와 학습시키기	
_3.12 텐서보드로 계산 그래프와 학습 시각화하기	
_3.13 텐서플로에서 MNIST를 위한 다층 모델 만들기	
_3.14 요약	

## CHAPTER 4 경사 하강법을 넘어서
_4.1 경사 하강법의 과제
_4.2 심층 신경망의 오차 곡면에서 지역 최소값	
_4.3 모델 식별성	
_4.4 심층 신경망에서 가짜 지역 최소값들은 얼마나 다루기 어려운가?	
_4.5 오차 곡면의 평평한 구간	
_4.6 잘못된 방향의 경사
_4.7 모멘텀 기반 최적화	
_4.8 이차 방법에 대한 개요	
_4.9 학습률 적응	
_4.10 최적화 도구 선택의 철학	
_4.11 요약	

## CHAPTER 5 합성곱 신경망
_5.1 인간 시각에서의 뉴런
_5.2 특징 선택의 단점	
_5.3 크기 조정 없는 기본 심층 신경망	
_5.4 필터와 특징 맵	
_5.5 합성곱층 정리	
_5.6 최대 풀링	
_5.7 합성곱 신경망의 전체 구조	
_5.8 합성곱 신경망으로 MNIST에서 순환 반복 끝내기	
_5.9 더 견고한 모델을 만드는 이미지 전처리 파이프라인	
_5.10 배치 정규화로 학습 가속하기	
_5.11 CIFAR-10을 위한 합성곱 신경망 만들기	
_5.12 합성곱 신경망 학습 시각화하기	
_5.13 합성곱 필터로 예술 스타일 복제하기	
_5.14 다른 문제 영역에서 합성곱 필터 학습하기	
_5.15 요약	

## CHAPTER 6 임베딩과 표상학습
_6.1 저차원 표현 학습하기	
_6.2 주성분 분석	
_6.3 오토인코더 구조의 동기	
_6.4 텐서플로로 오토인코더 구현하기	
_6.5 견고한 표현을 강제하는 디노이징	
_6.6 오토인코더의 희소성	
_6.7 입력 벡터보다 문맥이 더 유익할 때	
_6.8 Word2Vec 프레임워크	
_6.9 Skip-Gram 구조 구현하기	
_6.10 요약

## CHAPTER 7 시퀀스 분석을 위한 모델
_7.1 가변 길이 입력 분석하기	
_7.2 신경망 n-gram으로 seq2seq 해결하기	
_7.3 품사 태거 구현하기	
_7.4 의존 구문 분석과 SyntaxNet	
_7.5 빔 탐색과 전역 정규화	
_7.6 상태 기반 딥러닝 모델 사례	
_7.7 순환 신경망	
_7.8 사라지는 경사도 문제	
_7.9 LSTM 유닛	
_7.10 RNN 모델을 위한 텐서플로 기초 요소	
_7.11 감정 분석 모델 구현하기	
_7.12 순환 신경망으로 seq2seq 과제 풀기	
_7.13 주의집중으로 순환망 증강하기	
_7.14 신경 번역망 해부하기	
_7.15 요약	

## CHAPTER 8 메모리 증강 신경망
_8.1 신경 튜링 기계	
_8.2 주의집중 기반 메모리 접근	
_8.3 NTM 메모리 주소 지정 동작 방식	
_8.4 미분 가능 신경 컴퓨터	
_8.5 DNC에서 간섭 없는 쓰기	
_8.6 DNC 메모리 재사용	
_8.7 DNC 쓰기의 시간적 연결	
_8.8 DNC 읽기 헤드 이해	
_8.9 DNC 제어기 신경망	
_8.10 동작 중인 DNC 시각화하기	
_8.11 텐서플로에서 DNC 구현하기	
_8.12 읽기와 이해를 위한 DNC 가르치기	
_8.13 요약	

## CHAPTER 9 심층 강화학습
_9.1 아타리 게임을 점령한 심층 강화학습	
_9.2 강화학습이란? 
_9.3 마르코프 결정 과정	
_9.4 탐색 대 활용	
_9.5 정책 대 가치학습	
_9.6 정책 경사가 있는 막대기-수레 문제	
_9.7 Q 러닝과 DQN 
_9.8 DQN 개선하기	
_9.9 요약

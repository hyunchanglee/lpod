---
layout: page
title: 레이저 분무 가시화
description: PLIF · Mie scattering · shadowgraphy를 이용한 분무 구조 계측
img: assets/img/research/1.jpg
importance: 1
category: 계측기법
---

인젝터에서 분사된 액체 연료가 어떻게 분열하고 분포하는지를 **비접촉·비침습**으로 관찰합니다.

- **PLIF (Planar Laser-Induced Fluorescence)** — 연료에 포함된 형광 물질 또는 첨가 tracer를 여기시켜 액상/기상 연료의 2차원 농도 분포를 취득
- **Mie scattering** — 액적에 의한 산란광으로 액상 분포와 분무각, 관통거리 측정
- **Shadowgraphy / backlight imaging** — 근접 분사장(near-field)의 액주 분열(primary breakup) 관찰

취득 영상은 MATLAB/Python 기반 처리 루틴으로 배경 보정, 레이저 시트 불균일 보정, 통계 평균 처리를 거쳐 정량 데이터로 변환합니다.

##### 주요 계측 항목

- 분무각(spray cone angle), 관통거리(penetration length)
- 액주 분열 길이(breakup length)
- 연료 농도 분포 및 혼합 균일도

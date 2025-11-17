<h1 align="center"> EfficientLLM: Speed always wins </h1>

<div align="center">
<a href="https://pseudo-lab.com"><img src="https://img.shields.io/badge/PseudoLab-S10-3776AB" alt="PseudoLab"/></a>
<a href="https://discord.gg/EPurkHVtp2"><img src="https://img.shields.io/badge/Discord-BF40BF" alt="Discord Community"/></a>
<a href="https://github.com/Pseudo-Lab/10th-template/stargazers"><img src="https://img.shields.io/github/stars/Pseudo-Lab/10th-template" alt="Stars Badge"/></a>
<a href="https://github.com/Pseudo-Lab/10th-template/network/members"><img src="https://img.shields.io/github/forks/Pseudo-Lab/10th-template" alt="Forks Badge"/></a>
<a href="https://github.com/Pseudo-Lab/10th-template/pulls"><img src="https://img.shields.io/github/issues-pr/Pseudo-Lab/10th-template" alt="Pull Requests Badge"/></a>
<a href="https://github.com/Pseudo-Lab/10th-template/issues"><img src="https://img.shields.io/github/issues/Pseudo-Lab/10th-template" alt="Issues Badge"/></a>
<a href="https://github.com/Pseudo-Lab/10th-template/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/Pseudo-Lab/10th-template?color=2b9348"></a>
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fpseudo-lab%2F10th-template&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false"/></a>
</div>
<br>

<!-- sheilds: https://shields.io/ -->
<!-- hits badge: https://hits.seeyoufarm.com/ -->

<div align="center">
  <img src="./speed_always_wins.png" alt="speed always wins" width="600"/>
</div>

> 🚀 `EfficientLLM: Speed always wins repository`에 오신 것을 환영합니다! 저희는 `Transformer` 아키텍처의 근본적인 비효율성을 탐구하고, `Sparse Attention`과 `Speculative Decoding` 같은 최신 최적화 기술들을 깊이 있게 다룹니다. 우리의 목표는 `Large Language Models`의 성능 장벽을 돌파하는 것입니다. `LLM`을 더 빠르고, 더 효율적이며, 더 쉽게 접근할 수 있도록 만드는 여정에 함께해주세요!

## 🌟 프로젝트 목표 (Project Vision)
_"아키텍처 수준의 깊이 있는 이해를 통해 LLM 추론의 현실적인 장벽을 넘어서다"_

Transformer의 $O(N^2)$ 복잡도, 막대한 메모리 요구량은 Long-Context, AI Agent와 같은 차세대 AI 어플리케이션의 가장 큰 병목입니다. 수 조원의 데이터센터, 수 억원의 서빙 비용은 혁신적인 LLM 개발과 서비스를 가로막는 현실적인 장벽이 되고 있습니다.

본 프로젝트는 LLM 추론 효율을 높이기 위한 두 가지 핵심 축, **Sparse Attention**과 **Speculative Decoding**을 중심으로 최신 연구들을 탐구하여 다음과 같은 역량을 갖추는 것을 목표로 합니다.

- **핵심 원리 이해:** 각 최적화 기술의 작동 방식을 아키텍처 수준에서 깊이 있게 이해합니다.
- **통찰력 확보:** 어떤 상황에서 어떤 기술이 효과적인지에 대한 통찰력을 기릅니다.
- **문제 해결 능력:** 비용과 속도의 제약을 해결할 수 있는 실질적인 역량을 갖춥니다.
- **지식 공유:** 모든 학습 결과물을 공개하여 국내 LLM 생태계에 기여합니다.

## 🧑 역동적인 팀 소개 (Dynamic Team)

| 역할          | 이름 |   LinkedIn                          |
|---------------|------|----------------------------------------|
| **Project Manager** | 전경호 |  [LinkedIn](https://www.linkedin.com/in/kyoungho-jeun-590295218/)
| **Member** | 김승우 | [LinkedIn](https://www.linkedin.com/in/seungwoos/) | 
| **Member** | 김형균 | [LinkedIn](https://www.linkedin.com/in/hyeongkyun-kaden-kim/) | 
| **Member** | 박재욱 | [LinkedIn](https://www.linkedin.com/in/lechuckpark/) | 
| **Member** | 이승아 | [LinkedIn](https://www.linkedin.com/in/seungah-lee-79a748245/) | 

## 💻 주차별 활동 (Activity History)
- 시간: 매주 화요일 20:00-22:00
- 장소: Room-AT

| 날짜 | 내용 | 발표자 | 영상 |
| - | - | -------------- | - |
| 2025/9/9 | OT | 전경호 | |
| 2025/9/16 | [Speed Always Wins: A Survey on Efficient Architectures for Large Language Models](https://www.arxiv.org/abs/2508.09834)  | <nobr>전경호</nobr> | |
| 2025/9/23 |  [vLLM](https://arxiv.org/abs/2309.06180) | <nobr>박재욱</nobr> <br> <nobr>이승아</nobr> | [vLLM](https://youtu.be/CXDoHWb0QOs) |
| 2025/9/30 | [MInference 1.0: Accelerating Pre-filling for Long-Context LLMs via Dynamic Sparse Attention](https://arxiv.org/abs/2407.02490)<br> [SmoothQuant: Accurate and Efficient Post-Training Quantization for Large Language Models](https://arxiv.org/abs/2211.10438)<br> [MInference](https://arxiv.org/abs/2407.02490)  | <nobr>김승우</nobr> <br> <nobr>김형균</nobr> | [SmoothQuant](https://youtu.be/dUzFAydJalM?si=fZyqeNE0kZ93btxV)</nobr> <br> <nobr>[MMInference](https://youtu.be/q1i1NAm8z1k?si=1RK4Apiu8oKHwCWC) |
| 2025/10/7 | --Korean Thanksgiving Day-- | | |
| 2025/10/14 | [SageAttention: Accurate 8-Bit Attention for Plug-and-play Inference Acceleration](https://arxiv.org/abs/2410.02367) <br> [SageAttention2: Efficient Attention with Thorough Outlier Smoothing and Per-thread INT4 Quantization](https://arxiv.org/abs/2411.10958) | <nobr>전경호</nobr> <br> <nobr> Tech Talk</nobr> | |
| 2025/10/30 | [EAGLE: Speculative Sampling Requires Rethinking Feature Uncertainty](https://arxiv.org/abs/2401.15077)<br> [Insights into DeepSeek-V3: Scaling Challenges and Reflections on Hardware for AI Architectures](https://arxiv.org/abs/2505.09343)  | <nobr>이승아</nobr> <br> <nobr>박재욱</nobr> |[Eagle](https://youtu.be/m5qXA8LWhq8) |
| 2025/11/4 | [MMInference: Accelerating Pre-filling for Long-Context VLMs via Modality-Aware Permutation Sparse Attention](https://arxiv.org/abs/2504.16083)<br> [FlexPrefill: A Context-Aware Sparse Attention Mechanism for Efficient Long-Sequence Inference](https://arxiv.org/abs/2502.20766)  | <nobr>김승우</nobr> <br> <nobr>김형균</nobr> | [MMInference](https://youtu.be/dTC2kLkoLdY) <br> [FlexPrefill](https://youtu.be/fAqNTu-LmdM) |
| 2025/11/11 | [Medusa: Simple LLM Inference Acceleration Framework with Multiple Decoding Heads](https://arxiv.org/abs/2401.10774)<br> [Native Sparse Attention: Hardware-Aligned and Natively Trainable Sparse Attention](https://arxiv.org/abs/2502.11089)  | <nobr>전경호</nobr> <br> <nobr>김민수</nobr> | [NSA](https://youtu.be/5udj5BSdPLY) |
| 2025/11/18 |   | <nobr>이승아</nobr> | |
| 2025/11/25 |  | <nobr>김승우</nobr> <br> <nobr>김형균</nobr> | |
| 2025/12/2 |  | <nobr>전경호</nobr> <br> <nobr>김민수</nobr> | |
| 2025/12/9 |   | <nobr>이승아</nobr>| |
| 2025/12/16 |   | <nobr>김승우</nobr> <br> <nobr>김형균</nobr> | |
| 2025/12/23 |  | <nobr>전경호</nobr> <br> <nobr>김민수</nobr> | |

## 💡 학습 자원 (Learning Resources)

#### 핵심 Survey 논문
- [Speed Always Wins: A Survey on Efficient Architectures for Large Language Models](https://www.arxiv.org/abs/2508.09834)
- [Unlocking Efficiency in Large Language Model Inference: A Comprehensive Survey of Speculative Decoding](https://arxiv.org/abs/2401.07851)

#### 논문 탐색을 위한 레포지토리
- [Awesome-Efficient-Arch](https://github.com/weigao266/Awesome-Efficient-Arch)
- [Awesome-Efficient-LLM](https://github.com/horseee/Awesome-Efficient-LLM)
- [Awesome-LLM-Inference](https://github.com/xlite-dev/Awesome-LLM-Inference)
- [LLM-inference-optimization-paper](https://github.com/chenhongyu2048/LLM-inference-optimization-paper)
- [SpeculativeDecodingPapers](https://github.com/hemingkx/SpeculativeDecodingPapers)

## 🌱 참여 안내 (How to Engage)
- 빌더로 참여 — 프로젝트 기획·운영 주도
- 러너로 참여 — 연구·개발·테스트 등 실행
- 청강 참여 — 공개 세션 참여 가능

❗️참여 링크: [가짜연구소 디스코드](https://discord.gg/EPurkHVtp2)
❗️커뮤니케이션 채널: 디스코드 #{{채널명}}

**누구나 청강을 통해 모임을 참여하실 수 있습니다.**  
1. 특별한 신청 없이 정기 모임 시간에 맞추어 디스코드 #Room-GH 채널로 입장
2. Magical Week 중 행사에 참가
3. Pseudo Lab 행사에서 만나기

## Acknowledgement 🙏

이 프로젝트는 가짜연구소 Open Academy로 진행됩니다.
여러분의 참여와 기여가 ‘우연한 혁명(Serendipity Revolution)’을 가능하게 합니다. 모두에게 깊은 감사를 전합니다.
OOO is developed as part of Pseudo-Lab's Open Research Initiative. Special thanks to our contributors and the open source community for their valuable insights and contributions.

## About Pseudo Lab 👋🏼</h2>

[Pseudo-Lab](https://pseudo-lab.com/) is a non-profit organization focused on advancing machine learning and AI technologies. Our core values of Sharing, Motivation, and Collaborative Joy drive us to create impactful open-source projects. With over 5k+ researchers, we are committed to advancing machine learning and AI technologies.

<h2>Contributors 😃</h2>
<a href="https://github.com/Pseudo-Lab/10th-template/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Pseudo-Lab/10th-template" />
</a>
<br><br>

<h2>License 🗞</h2>

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

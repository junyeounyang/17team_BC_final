# 17조 대학로 자율주행 — BC 최종본 (PPO 인수인계용)

모든 자료와 설명은 [`BC_final_share/`](BC_final_share/) 폴더에 있다. 먼저 [`BC_final_share/README.md`](BC_final_share/README.md) 를 읽을 것.

- 최종 BC 모델: `BC_final_share/results/bc_600_s30/model.pt`
- 최종 평가 (1,500 에피소드): 도착 93.2%, 위반 없이 도착 81.7%
- 실행은 `BC_final_share` 폴더 안에서 한다 (SUMO 1.27.1, Python 3.12)
- 다음 단계: BC 모델에서 시작하는 PPO — 유의사항은 README 6절

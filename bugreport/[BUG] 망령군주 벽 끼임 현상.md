 [BUG] 망령군주 벽 끼임 현상

버그 요약: 하이엔트로피 망령군주 보스가 벽에 끼임

💻 테스트 환경 (Environment)

OS/버전: Windows 11

대상 버전: L.260212.2_5

📋 재현 단계 (Steps to Reproduce)

1. 헤니르 : 하이엔트로피 진입

2. 나이트메어 : 리셋 룸 2페이즈 망령군주 스테이지 도달

3. 보스를 벽바로 앞에 유도 후 벽 방향으로 할퀴기 패턴 유도

4. 보스가 전진하며 할퀴기, 벽으로 끼인 후 탈출 불가

5. 특수 패턴, 유저가 멀리 이동하지않으면 탈출 불가

6. 접근하지않고 공격 시 유저에게 붙으려 시도, 할퀴기 패턴 발생하지 않음

7. 유저 접근 시 할퀴기 패턴, 탈출하지않음 

✅ 기대 결과 (Expected Result)

벽에 끼이지 않고 공격

❌ 실제 결과 (Actual Result)

할퀴기를 진행하며 전진, 벽으로 들어가서 탈출하지 못함 

📸 에비던스 (Evidence)
<img width="1832" height="1032" alt="SC_L 260212 2_5_ 2026-02-25 20-33-22-940" src="https://github.com/user-attachments/assets/a2876da0-cbc1-4111-bef9-ee8e72c52724" />
<img width="1832" height="1032" alt="SC_L 260212 2_5_ 2026-02-25 20-33-11-953" src="https://github.com/user-attachments/assets/c5e8a8dc-e455-4a1c-88b6-baf97ae245f5" />



https://github.com/user-attachments/assets/5e18b43c-d620-4377-8869-f2f101edd899




🚨 위험도 판정 (Severity & Priority)

심각도 (Severity): Major

우선순위 (Priority): High


 [BUG] 강력한 공격 회피 불가 현상

버그 요약: 공격 이펙트 이외의 장소에서 대기하여도 강력한공격을 피격당하여 사망

💻 테스트 환경 (Environment)

OS/버전: Windows 11

대상 버전: L.260129.1_6

📋 재현 단계 (Steps to Reproduce)

1. 미러 델 '귀목' 던전 진입(스토리 난이도)

2. 보스 강력한 공격 시전

3. 텍스트 및 보스 행동 확인

4. 보스 공격 모션 직전 공중 체공 및 '엘리안의 시계' 사용

5. 보스 피격 이펙트 범위 밖에서 공중 정지

6. 강력한 공격 피격 후 캐릭터 사망 

✅ 기대 결과 (Expected Result)

강력한 공격의 이펙트 범위 밖에서 공격 회피 성공

❌ 실제 결과 (Actual Result)

강력한 공격의 이펙트 범위 밖에 존재 하여도 피격되며 사망

📸 에비던스 (Evidence)

<<img width="1832" height="1032" alt="SC_L 260212 1_7_ 2026-02-12 22-21-40-825" src="https://github.com/user-attachments/assets/926ead63-050f-407f-ae84-6ce58fcfd7a7" />
<<img width="1832" height="1032" alt="SC_L 260212 1_7_ 2026-02-12 22-21-45-652" src="https://github.com/user-attachments/assets/58a6e2c4-dd3d-4d25-83e4-038004fbfd02" />


🚨 위험도 판정 (Severity & Priority)

심각도 (Severity): Major

우선순위 (Priority): High

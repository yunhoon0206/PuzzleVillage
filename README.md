# PuzzleVillage

캐릭터 육성, 마을 발전, 던전 탐험을 결합하는 캐주얼 2D 퍼즐 RPG 프로젝트입니다.

## 개발 환경

- Unity Editor: 6000.6.0f1
- 템플릿: Universal 2D (URP 2D Renderer)
- 우선 개발 플랫폼: Windows PC
- 에디터 자동화: Unity MCP v10.0.0 + Unity Pipeline
- 기존 도구 구성: codex_game 기준. Aseprite, Test Framework, uGUI는 Unity 6.6 템플릿 버전을 유지합니다.

## 시작하기

1. 저장소를 내려받고 `develop` 브랜치로 전환합니다.
2. Unity Hub에서 이 폴더를 추가하고 Unity 6000.6.0f1로 엽니다.
3. 첫 실행의 패키지 복원과 에셋 가져오기가 끝날 때까지 기다립니다.
4. `Assets/Scenes/SampleScene.unity`를 엽니다.

Unity CLI를 사용하는 경우 프로젝트 폴더에서 `unity open .`으로 열 수 있습니다.

## 브랜치

- `main`: 공유 기준 브랜치
- `develop`: 실제 제작 및 통합 작업 브랜치

## 초기 게임 구상

- 캐릭터를 키우고 마을을 발전시켜 던전 탐험을 준비합니다.
- 던전에 캐릭터 1~5명을 편성합니다.
- 같은 종류의 퍼즐을 3개 이상 맞춰 공격합니다.
- 캐릭터에 따라 3칸 매치 피해 증가, 5칸 매치 추가 턴, 십자 매치 주변 파괴 같은 효과를 구상하고 있습니다.
- 탐험 보상을 캐릭터와 마을 성장에 사용합니다.

위 내용은 초기 구상이며 수치, 발동 조건, 조작 방식은 후속 기획에서 확정합니다.
현재는 Unity 기본 프로젝트와 Git 작업 환경을 준비하는 단계로, 게임 플레이는 아직 구현하지 않았습니다.

## 버전 관리

`Assets`, `Packages`, `ProjectSettings`와 에셋의 `.meta` 파일을 함께 관리합니다.
`Library`, `Temp`, `Logs`, `UserSettings`, 빌드 결과물은 `.gitignore`로 제외합니다.
Unity 기본 Welcome 안내 에셋은 포함하지 않으며, 다시 생성되어도 Git에서 제외합니다.

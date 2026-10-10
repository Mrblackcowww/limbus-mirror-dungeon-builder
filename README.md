# 거던 빌더 v1.1

GitHub Pages용 정적 웹 앱입니다.

## 업로드
저장소 최상위에 `index.html`, `README.md`, `data/` 폴더가 있도록 업로드하세요. `data/` 안의 JSON은 앱에서 실제로 fetch하여 사용합니다.

## 기능
- 인격 검색, 수감자/성급/소속/공격 유형 필터
- 편성 추가/해제 및 순서 변경(위/아래, PC 드래그)
- 키워드 집중도 분석
- 실제 거던 시작 기프트 선택 목록을 이용한 검색/추천 및 보유 수량 관리
- 브라우저 내 빌드 저장, JSON 내보내기/가져오기
- 인격별 키워드 가중치 편집(예: `출혈=3, 호흡=2`), 소속/공격 유형 편집

## 데이터 범위와 정확성
- `data/identities.json`: 189개 인격 목록을 기반으로 한 편성용 로스터. 출시명/성급은 게임 업데이트에 따라 변경될 수 있으므로 운영 전 원문과 대조하세요. 일부 태그는 미분류입니다.
- `data/gifts.json`: Mirror Dungeon 시작 기프트 선택 목록에서 확인 가능한 실제 기프트 이름과 키워드 범주를 포함합니다. 효과 설명, 등급, 강화 경로, 합성 레시피는 검증되지 않은 값을 만들지 않도록 비워 두었습니다.
- 키워드 태그는 완전한 전투 데이터베이스가 아닙니다. 미분류 인격은 UI의 `태그 편집`으로 가중치를 추가할 수 있습니다. 편집값은 해당 브라우저에 저장되며 빌드 JSON에 포함됩니다.

## 데이터 출처
- Limbus Company Wiki.gg — List of Identities: https://limbuscompany.wiki.gg/wiki/List_of_Identities
- Limbus Company Wiki.gg — Mirror Dungeon / Infinity Mirror: https://limbuscompany.wiki.gg/wiki/Infinity_Mirror
- E.G.O Gift names/categories are compiled from the starting-gift choice list.

## 저장 관련
localStorage는 기기/브라우저마다 분리되어 있습니다. PC와 휴대폰 사이에 빌드를 옮기려면 JSON 내보내기/가져오기를 사용하세요.


## 분류 편집 안내
- 소속은 인격명에서 자동 추정한 초안이므로 정확성을 보장하지 않습니다.
- 공격 유형(참격/관통/타격)은 확인되지 않은 경우 비워 둡니다. 카드의 `소속/공격 유형` 버튼으로 수정할 수 있습니다.
- 편집 내용은 현재 브라우저에 저장되며 JSON 빌드 내보내기/가져오기로 이동할 수 있습니다.

# a2meter

더이상 DLL을 통해 다른 사람들이 개발할 필요성이 없어서 개인빌드 배포용으로 변경합니다.

WinDivert로 TCP 패킷을 캡처해 미터기 DLL에 투입하고, 콜백으로 실시간 DPS를 집계합니다.

관리자 권한을 필요로 합니다.

---

## 1. 미터기 실행후 화면

<p align="left">
<img width="352" height="161" alt="Image" src="https://github.com/user-attachments/assets/d10b257c-eac6-4421-ae3f-3a8ab7299dde" />
</p>

📊 버튼 : 몬스터 상태이상 창 열기

---

## 2. 미터기 설정창 화면

<p align="left">
<img width="376" height="702" alt="Image"
src="https://github.com/user-attachments/assets/f65de8f6-27fb-4a25-842f-4d3511455b15" />
</p>

<p align="left">
<img width="365" height="601" alt="Image"
src="https://github.com/user-attachments/assets/551f7c2c-86ab-4f50-bcbc-0ef770399ce7" />
</p>

<p align="left">
<img width="891" height="714" alt="Image"
src="https://github.com/user-attachments/assets/ef16ca35-1fe8-429c-8d61-635e3919a8a7" />
</p>

---

## 3. 버프 / 디버프 화면

<p align="left">
<img width="866" height="597" alt="Image"
src="https://github.com/user-attachments/assets/d94ad55f-9e39-40ec-8085-a3ab444f6807" />
</p>

<p align="left">
<img width="648" height="568" alt="Image"
src="https://github.com/user-attachments/assets/9b0352d4-ea10-47b8-bc13-b6cddc3b295c" />
</p>

> 일부 버프 디버프스킬이 스킬이름으로 출력되는 현상이 있음(실제 해당 스킬이 아님에도)

### 대상이 없을시 경고메시지 출력

<p align="left">
<img width="296" height="154" alt="Image"
src="https://github.com/user-attachments/assets/18fe3767-e699-4738-9b31-40a818ab6d26" />
</p>

---

## 4. 디테일 화면

<p align="left">
<img width="1108" height="627" alt="Image"
src="https://github.com/user-attachments/assets/21cbf489-6fc5-46ef-80b2-4bc12b089cb9" />
</p>

---

## 5. 실제 사용 화면

<p align="left">
<img width="343" height="444" alt="Image"
src="https://github.com/user-attachments/assets/95bb33b0-2bc4-498d-bb69-1d775d8c512e" />
</p>

---

## 6. 기본 설정 값(단축키 등)

| 기능 | 단축키 |
|------|--------|
| 초기화 | `Ctrl + R` |
| 클릭 비허용 | `Ctrl + Page Up` |
| 클릭 허용 | `Ctrl + Page Down` |
| 트레이 | `Ctrl + T` |

> 단축키 변경사항은 저장후 프로그램을 재실행 해주세요.

대미지바 영역 우클릭을 통해 디테일 창 확인 가능.

메인 화면을 제외한 설정 디테일 창의 경우 ESC를 통해 닫기 가능.

---

## 7. 예시 스크린샷에 사용된 세팅 값 정보

```json
{
  "barColorTop": "#FFFF2020",
  "barColorMid": "#FFFFDDDD",
  "barColorBottom": "#FF880000",
  "barGlowColor": "#FFFF0000",
  "fontColor": "#FFFFFFFF",
  "backgroundColor": "#E0302828",
  "windowOpacity": 1,
  "barHeightPercent": 15,
  "barOpacity": 1,
  "barRowBgColor": "#80201010",
  "barRowBgOpacity": 1,
  "bossNameColor": "#FFFFFFFF",
  "labelColor": "#66FFFFFF",
  "statValueColor": "#FFFFFFFF",
  "dpsValueColor": "#FFD4E86A",
  "playerNameColor": "#FFFFFFFF"
}
```

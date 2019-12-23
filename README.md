# BCI_Hololnes_Bulb_Control

## 해결해야 할 사항
<ol>
  <li> Vuforia 이미지 타겟 세가지 전구 추가</li>
  <li> 빨간색, 은색, 검정색 전구를 추가해야 하는데 SSVEP는 검정, 흰색 교차하는 매커니즘이라 칼라 아이콘 적용 불가능</li>
  <li> Eye Scene에서 Help 보고 나서 돌아왔을 시 카운트 다운 안하는 점.</li>
  <li> 시간기반 -> 프레임 기반 수정</li>
  <li> Eye Scene UDP 씹히는 문제</li>
  <li> 미들웨어와의 UDP 통신 코드 통일 문제</li>
  <li> 기능 선택 화면 Bulb에 맞게 고치기</li>
</ol>

## Vuforia Image Target
<ul>
  width는 mm 단위로 임의로 200로 설정 함
</ul>

## 버전 관리
<ol>
  <li> Dev_Ctr_어쩌구 <br>
    - 프레임기반, 
   <li>
  <li> Device_Control_191127 <br>
    - 시간기반, 자극 사이 대기시간 +8초
  </li>
  <li> CES_2020_191221 <br>
    - 시간기반
  </li>
</ol>

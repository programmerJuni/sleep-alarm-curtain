# sleep-alarm-curtain : 수면 알람 커튼
아두이노 프로젝트<br>

목표 : 기존의 알람 제품들이나 휴대폰 알람들은 알람의 해제 방식이 너무 간단하고 해제 하더라도 침대 근처에 있으면 해제후 다시 잠들어버릴 가능성이 높습니다. 침대로부터 일어나도록 유도하면서 커튼을 절반이상 거둬서 방을 기상 분위기로 전환시키는게 목적입니다.<br>

동작 간단 설명 : LCD화면과 리모컨을 통해 원하는 기상 시간을 설정할 수 있습니다. 또한 수면램프 모드 활성화 설정도 가능합니다. 수면램프 모드 활성화시 커튼을 향해 LED 빛을 쬐서 수면램프 역할을 할 수 있게 됩니다.(알람 해제시 자동으로 꺼짐) 설정된 시간에 피에조 버저로 알람이 울리게 되고, 사용자가 알람을 해제하려면 커튼을 절반이상 거둬야지 알람이 해제가 됩니다.<br>

사용된 아두이노 제품 :  아두이노 uno, lcd, ir센서, 초음파 센서, DS1302 RTC 모듈, 피에조 버저, LED, 리모컨<br>

아두이노 설계도 : <br>
![아두이노프로젝트설계도(최종)](https://github.com/programmerJuni/sleep-alarm-curtain/assets/57414420/575400a2-369b-476b-b41c-0245069bb4a5)<br>


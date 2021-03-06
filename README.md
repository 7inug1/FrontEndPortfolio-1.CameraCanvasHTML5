# WebRTC/Canvas API 포트폴리오 
## 목차
```
1. 소개
2. 사용 방법
3. 제작 계기
4. 제작 과정 소개
5. 제작 후 느낀 점
6. 한계점
```

## 1. 소개
HTML5에서 추가된 WebRTC API와 Canvas API를 주축으로 사용자 컴퓨터의 웹캠으로 사진을 찍고, 찍은 사진에 그림을 그릴 수 있게 하는 포트폴리오입니다.

## 2. 사용 방법

## 3. 제작 계기
- HTML 및 HTML5의 기능에 대한 이해를 심화시키고자 제작하게 되었습니다.
- MDN 웹사이트의 HTML5의 새 기술을 주체적으로 공부하고 조합하여 포트폴리오를 만들었습니다. 

## 4. 제작 과정 소개
```
1)WebRTC API
2)Canvas API
3)localStorage API
4)Online/Offline events
```

### 1)WebRTC API
- WebRTC(Web Real-Time Communication)기술을 이용하여 웹캠으로 사용자의 화면을 실시간 스트리밍하고 사진을 찍을 수 있는 컴포넌트를 제작했습니다.

### 2)Canvas API
- Canvas 요소를 이용한 컴포넌트를 만듦. 
- 사용자의 실시간 화면을 캡쳐하고 캡쳐한 사진 위에 그림 그릴 수 있게 하는 시각적이고 인터렉티브한 컴포넌트를 제작했습니다.

### 3)localStorage API
- Local Storage를 통해 효과적인 오프라인 경험을 제공하고자 하였습니다.
- 인터넷에 연결되지 않아도 사용자가 캡쳐하고 그림 그린 데이터는 localStorage 객체 안에 담겨 언제든 불러올 수 있습니다.

### 4)Online/Offline events
- Online & Offline events를 사용해 상태바를 만들어 사용자의 인터넷 상태를 알려주는 편의성을 제공하였습니다.

## 5. 제작 후 느낀 점
HTML5에 새로 발표된 기술을 포트폴리오의 필요에 맞게 구현해보며 다양한 HTML5 기술의 작동 방식을 깊이 이해할 수 있게 되었습니다.

## 6. 한계점
- 모바일 환경에서 portrait모드로 사진 찍으면 사진이 왜곡되어 찍히는 문제가 발생하였습니다. 스트리밍되는 비디오의 넓이와 높이를 조정하면 되는 간단한 문제인줄 알았으나 모바일 디바이스에 따른 캔버스의 크기가 자동으로 변경되어 현재 해결 진행중입니다. 

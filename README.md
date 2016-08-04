# NextDrop
NextDrop is a web-based clone of [AirDrop](https://en.wikipedia.org/wiki/AirDrop), created using [Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components).

### 사용 기술
외부 라이브러리를 사용하지 않고, [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) 기술만을 사용하여 개발을 진행한다. 최신 버전의 Chrome을 기준으로 개발한다.

* [WebRTC API](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API) - To share data and perform teleconferencing peer-to-peer
* [File](https://developer.mozilla.org/en-US/docs/Web/API/File) - Using files from web applications
* [Blob](https://developer.mozilla.org/en-US/docs/Web/API/Blob) - Represents a file-like object of immutable, raw data
* [Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components) - Reusable user interface widgets
* [HTML Templates](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template) - A mechanism for holding client-side content

### 주차별 개발 계획
매주 6시간 씩 총 30시간의 작업을 통해 개발을 완료한다.

##### Week 1
사용할 기술에 대한 학습을 진행하고, 컴포넌트를 어떻게 구성할 것인지 기획한다. 특히 WebRTC의 사용 방법과 요구사항을 학습하고, Web Components를 어떤 부분에 적용할 것인지 검토한다. [HTML5 Boilerplate](https://html5boilerplate.com/)를 이용하여 개발 환경을 구성한다.

##### Week 2
WebRTC를 사용하기 위해서는 signaling server와 STUN/TURN server가 필요하다. [SimpleWebRTC.js](https://simplewebrtc.com/)를 사용하거나, [Signalmaster](https://github.com/andyet/signalmaster) 등을 이용하여 서버를 구축한다.

##### Week 3
[WebRTC API](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API)를 사용하여 파일을 보내고 받는 기능을 구현한다.

##### Week 4
[Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components)를 사용하여 파일을 보내고 받는 인터페이스를 구현한다.

##### Week 5
개발된 기능을 통합하고 개발 요구사항을 만족하는지 확인한다.

### Reference
- [ShareDrop](https://www.sharedrop.io/)
- [Snapdrop](https://snapdrop.net/)
- [Getting Started with WebRTC](http://www.html5rocks.com/en/tutorials/webrtc/basics/)
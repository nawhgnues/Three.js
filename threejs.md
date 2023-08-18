### Three.js 란?

> Three.js는 개발자들이 3D를 웹 상에 구현할 수 있도록 도와주는 JS라이브러리이다.
> 점, 선, 삼각형을 그리는 시스템인 WebGL을 이용한다.

### WebGL 란?

> WebGL은 매우 빠른 속도로 캔버스에 삼각형을 렌더링하는 JS API이다.
> WebGL을 사용해 도형을 그리기 위해선 복잡한 로직의 이해와 함께 수 많은 코드가 필요하다.

### Three.js를 사용하면 WebGL을 간편히 사용할 수 있다.

### ThreeJS 에서 가장 기본적인 요소 4가지

### 0. Canvas

#### 1. Scene

#### 2. Objects

#### 3. Camera

> 그야말로 카메라, 3D 오브젝트가 존재하는 Scene을 바라보는 역할을 한다. 여러 카메라가 존재할 수 있으며, scene graph에 추가되지 않는다.

#### 4. Renderer

> ThreeJS의 메인 객체로, Scene과 Camera로 구성된 3D화면을 canvas에 render한다.

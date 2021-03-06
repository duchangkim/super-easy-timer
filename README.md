# super-easy-timer

super-easy-timer는 카운트다운 타이머를 웹페이지에서 사용할 수 있게 해주는 모듈입니다.

![ezgif com-gif-maker](https://user-images.githubusercontent.com/68454100/104812927-0b472180-5849-11eb-813f-2e1dd3129d10.gif)
<br />

![스크린샷 2021-01-14 20 59 01](https://user-images.githubusercontent.com/68454100/104588176-59beb980-56ab-11eb-9dbd-9fec82250204.png)

![스크린샷 2021-01-14 20 58 28](https://user-images.githubusercontent.com/68454100/104588181-5aefe680-56ab-11eb-9293-18e53aa5994b.png)
<br />
<br />

# Features

- JavaScript DOM API와 TypeScript를 사용하여 만든 타이머 입니다.
- 한 페이지 안에 여러 타이머를 사용할 수 있습니다.
- 무거운 다른 작업과 사용시에도 오차가 없습니다.
- 컨테이너 크기에 따라 적절하게 사이즈 조절이 가능합니다.
  <br />
  <br />

# Installing

Using npm:

```bash
$ npm install super-easy-timer
```

Using yarn

```bash
$ yarn add super-easy-timer
```

<br />
<br />

# Example

**Basic use**

```html
<!-- index.html -->

<div id="root"></div>
```

```javascript
// index.js

import Timer from 'super-easy-timer';
import 'super-easy-timer/dist/super-easy-timer.min.css';

const root = document.getElementById('root');
const timer = new Timer(root);
```

<br />
<br />

# StackBlitz

[StackBlitz Example](https://stackblitz.com/edit/super-easy-timer-example?file=index.js)

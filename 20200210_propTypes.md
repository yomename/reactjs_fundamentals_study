## PropTypes

component의 props 타입을 확인하려면 property인 PropTypes를 선언



```
$ npm i prop-types
```

코드 입력후 설치하고 package.jon 파일에서 

```
"dependencies": {
...
"prop-types": "^15.7.2"
}
```

설치된것을 확인 가능하다. App.js 에 아래 코드 입력해서

```
import PropTypes from "prop-types";
```

사용하는 방법은 

```
// ex
Food.propTypes = {
  name: PropTypes.string.isRequired,
  picture: PropTypes.string.isRequired,
  rating: PropTypes.number.isRequired
};

```

isRequired 


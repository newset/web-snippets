## web-snippets

### snippets

#### React

---

- fcomp

> function component

```
import react from 'react';

export default (props) => {

}
```

- redux

> redux connect

```
import { connect } from 'react-redux'

```

#### Taro

---

- cln

```
    className=""
```

- dva

```
    export default {
        namespace: '${1:namespace}',
        state: {},
        reducers: {
            save(state, { payload }) {
            }
        },
        effects: {
            * ${2:effect} ({ payload }, { put, call }) {

            }
        }
    };
```

#### Eslint

---

- eslint-disable
  > disable file

```
/* eslint-disable */
```

- eslint-disable-line
  > disable current line

```
// eslint-disable-line
```

#### Remax

---

- remax
  > import remax

```
import { View } from 'remax';
```

- remax page
  >

```
import react from 'react';
import { View } from 'remax'

export default (props) => {

}
```

- remax class

> remax page class

```
import React, { Compoent } from 'react';
import { View } from 'remax';

export default class Index extends Component {
   render() {

   }
}
```

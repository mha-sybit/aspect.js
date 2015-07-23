# Introduction

Library for aspect-oriented programming with JavaScript, which takes advantage of ECMAScript 7 decorators syntax.

For further reading on decorators, take a look at [the spec](https://github.com/wycats/javascript-decorators).

The library is based on [meld](https://github.com/cujojs/meld).

# Demo

```
git clone https://github.com/mgechev/aop.js --depth 1
npm install -g babel-node
babel-node --optional es7.decorators demo/index.js
```

# Roadmap

- [ ] Implement the following joint points:
  - [ ] Method execution
  - [ ] Constructor call
  - [ ] Constructor execution
  - [ ] Filed get
  - [ ] Field set
  - [ ] Resolved
  - [ ] Rejected
- [ ] Static crosscutting
- [ ] Implement the following aspects:
  - [ ] Before
  - [ ] After
    - [ ] Throwing
    - [ ] Returning

# License

MIT

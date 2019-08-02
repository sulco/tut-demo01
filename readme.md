You can render React components in different environments, but in most cases what we'll want to target is a browser. In such case, we will use react-dom library.

```javascript
import ReactDOM from 'react-dom';

// ...

ReactDOM.render(<App />, document.getElementById('root'))
```

Nice!
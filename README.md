# Redocer

_Pronounced: reducer_

A custom React hook that wraps `useReducer` to provide undo-redo support.

### API

```jsx
import useRedocer from 'redocer'
import { useReducer } from 'react'

function App() {
  let [state, dispatch] = useRedocer(
    useReducer((state, action) => state + 1, 0),
  )
}
```

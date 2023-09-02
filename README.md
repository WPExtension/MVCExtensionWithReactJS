# MVCExtensionWithReactJS
MVCExtension with React JS demo file

Installing ReactJS : ``` npx create-react-app project-name ```

```JS

import React from 'react';
import ReactDOM from 'react-dom/client';

function App() {
  return (
    <div className="App">
      <h1 className="App-header">
        Hellow MVCExtension
      </h1>
    </div>
  );
}

export default App;

const root = ReactDOM.createRoot(document.getElementById('app'));
root.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
);

```

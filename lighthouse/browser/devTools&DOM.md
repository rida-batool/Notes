## Access nodes in the Console

DevTools provides a few shortcuts for accessing DOM nodes from the Console, or getting JavaScript references to them.

### 1. Reference the currently-selected node with $0

When you inspect a node, the == $0 text next to the node means that you can reference this node in the Console with the variable $0.

### 2. Store as global variable

If you need to refer back to a node many times, store it as a global variable.

Right-click the node in DOM and select store as global variable. type temp1 in console to refer it.

### 3. Copy JS path

Copy the JavaScript path to a node when you need to reference it in an automated test.

Right-click the node in the DOM Tree and select Copy > Copy JS Path. A document.querySelector() expression that resolves to the node has been copied to your clipboard.

paste it in the console and press enter.

### 4. Break on DOM changes

DevTools allows you to pause a page's JavaScript when the JavaScript modifies the DOM.

# 🚀 persistent-state-react 📦✨

Easily manage persistent state in React using `localStorage` with this lightweight and efficient hook! 🏆🔥

---

# 📦 Installation 💻🔧

👉 Run this command in your terminal:

```bash
npm i persistent-state-react
```

🎯 Or, directly add it to your `package.json`:

```json
"persistent-state-react": "^0.0.1"
```

---

# 🚀 Example 🛠️✨
## ⚛️ React.js 🏗️

```javascript
import { usePersistentState } from "persistent-state-react";

function MyComponent() {
    const [count, setCount] = usePersistentState("count", 0);
    
    return (
        <div>
            <p>Count: {count}</p>
            <button onClick={() => setCount(prev => prev + 1)}>➕ Increment</button>
        </div>
    );
}
```

---

<!-- # 🎭 Live Demo 🚀🌟

Check it out in action 👉 [CodeSandbox](https://codesandbox.io/) 🎨💡  -->

---

# 🏆 Features 🛠️

✅ Simple API ✨  
✅ Persistent state using `localStorage` 💾  
✅ Works with any React component ⚛️  
✅ Zero dependencies 📦  
✅ Super lightweight & efficient ⚡

---

<!-- # 📸 Snapshot 💖

*(Add a relevant screenshot here! 🖼️)* -->

🎉 Happy coding! 🚀🔥
# Deltamath Equation Copier
Easily copy deltamath equations to uhh calculate them easier.

Create a bookmark with this URL
```javascript
javascript:try{problemObj=problem.qlinesCopy[0],equation=problemObj.line?problemObj.line:`${problemObj.left.replace(/[{}]/g,"")}=${problemObj.right}`,prompt("Equation:",equation)}catch{alert("Equation not detected!")};void 0
```

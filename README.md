# Deltamath Question Copier
Easily copy deltamath questions to uhh calculate it easier.

Create a bookmark with this URL
```javascript
javascript:prompt("Question:",equation=(eqDisplays=document.querySelector(".hasJax").innerText.replace(/[{}]/g,"").split("−").join("-").split("\n")).toString().includes("=")?eqDisplays[0].includes(eqDisplays.at(-1).includes("=")?eqDisplays.at(-1):`=${eqDisplays.at(-1)}`)?eqDisplays[0]:eqDisplays[0]+eqDisplays.at(-1):eqDisplays[0]);void(0)
```

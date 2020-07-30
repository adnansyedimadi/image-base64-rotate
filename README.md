# image base64 rotate

浏览器端生成旋转后的 Base64 图片 | generate rotated image base64 in browser

## 使用 | usage

```
import rotate from 'base64-rotate'
...
let rotated = await rotate(img)
console.log(rotate)
// 'data:image/png;base64,/9j/4AAQSkZJRg...'
```
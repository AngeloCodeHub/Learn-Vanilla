# tailwindcss

- [TailwindCSS DOC](https://tailwindcss.com/docs/installation/using-vite)
- [Bootstrap · The most popular HTML, CSS, and JS library in the world.](https://getbootstrap.com/)

## 安裝

### vite

1. 啟動 vite 會去讀 `vite.config.ts`
2. 加入 /src/style.css `import @tailwindcss` 即可使用
3. 要使用原生 Vanilla 只要把 `import @tailwindcss` 拿掉

### 原生 Vanilla 版本

1. 使用 tailwindcss/cli
2. 監控根目錄 Vanilla-tailwindcss.css
	```Powershell
	pnpm tailwindcss -i ./Vanilla-tailwindcss.css -o ./src/style.css --watch
	```

## 筆記

```css
/* 小於斷點 md 則 hidden，大於 md 則以 block 渲染 */
className="hidden md:block"

/* 小於斷點 md 則以 block 渲染，大於則 hidden */
className="block md:hidden"
```


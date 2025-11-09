# tailwindcss vite版本與原生版本

[TailwindCSS DOC](https://tailwindcss.com/docs/installation/using-vite)

## vite

1. 啟動 vite 會去讀 `vite.config.ts`
2. 加入 /src/style.css `import @tailwindcss` 即可使用
3. 要使用原生 Vanilla 只要把 `import @tailwindcss` 拿掉

## 原生 Vanilla 版本

1. 使用 tailwindcss/cli
2. 監控根目錄 Vanilla-tailwindcss.css
	```Powershell
	pnpm tailwindcss -i ./Vanilla-tailwindcss.css -o ./src/style.css --watch
	```

# shadcn/ui + astro template

## Setup
```bash
npm install
npx shadcn@latest init
```
---

## Usage with the button component
```bash
npx shadcn@latest add button
```
index.html
```html
---
import { Button } from "@/components/ui/button"
---

<html lang="en">
	<head>
		<title>Astro</title>
	</head>
	<body>
		<Button>Hello World</Button>
	</body>
</html>
```

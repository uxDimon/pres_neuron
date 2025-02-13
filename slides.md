---
theme: default
title: Идеальный макет
info: |
    Идеальный макет для веб-разработчиков.
fonts:
    sans: Inter
    serif: Robot Slab
    mono: Fira Code
class: text-start flex content-between
drawings:
    persist: false
transition: slide-left
mdc: true
overviewSnapshots: true
---

<h1 class="title_1">Увлекательная <br/>разработка с AI</h1>

Доступные AI и что с ними делать

<br>
<br>

- Специфика использования AI
- AI в редакторе кода (GitHub Copilot, Codeium)
- Бесплатные / доступные чаты (DeepSeek, Qwen)
- Локальные AI (Ollama + Continue)
- Провайдеры AI (Bothub, GPTunneL)
- Философия использования

<v-drag class='video_1' pos="560,20,1000,1000,1">
  <img class="w-[390px] h-auto" src="./assets/1/start.webp"  width="1080" height="1444" >
</v-drag>

<style>
  .title_1 {
    position: relative;
    z-index: 110;
    background: #121212;
    display: inline-block;
    line-height: 4rem !important;
  }
</style>

---

# Специфика использования AI

Чат / Автозаполнение

<br>
<br>

- Генерация кода с учётом контекста
- Модификация кода
- Объяснения как работает код
- Исправление ошибок
- Генерация документации

<v-drag pos="30,124,2000,_,0">
    <video v-click='[1]' class="w-[700px] h-auto" controls='false' autoplay="autoplay" muted loop width="2496"  src="./assets/2/chat.mp4"></video>
</v-drag>

<v-drag pos="30,124,2000,_,0">
    <img v-click='2' class="w-[800px] h-auto" src="./assets/2/autocomplete.webp"  width="1600" >
</v-drag>

---

# AI в редакторе кода

Доступно нам не так много(

## [GitHub Copilot](https://github.com/features/copilot)

<br/>

- Без VPN ничего не получится (Работает только с vpn)
- Ограничения бесплатной версии
- Проблема с покупкой $10

## [Codeium](https://codeium.com/)

<br/>

- Чат не работает совсем
- Проблема с покупкой $15

---

# Бесплатные / доступные чаты

Китайские народные слоняры с крепким нефритовым стержнем

<br/>
<br/>

<img class="w-[320px] h-auto" src="./assets/4/DeepSeek.svg"  width="196"  >

[DeepSeek](https://www.deepseek.com/) `DeepSeek-R1`

<br/>

<img class="w-[260px] h-auto" src="./assets/4/Qwen.svg"  width="129"  >

[Qwen](https://chat.qwenlm.ai/) `Qwen2.5-Plus` `Qwen2.5-Max`

<v-drag pos="560,170,2000,_,2">
    <img class="w-[360px] h-auto" src="./assets/4/image4.webp"  width="680" >
</v-drag>

---

# Локальные AI

Самый простой способ поднять локальную AI

<v-drag pos="630,40,2000,_,0">
    <img class="w-[240px] h-auto" src="./assets/5/Ollama.svg"  width="129">
</v-drag>

[Ollama](https://ollama.com/)

| Model            | Parameters | Size   |
| ---------------- | ---------- | ------ |
| deepseek-r1:1.5b | 1.5B       | 1.1 GB |
| deepseek-r1:7b   | 7B         | 4.7 GB |
| deepseek-r1:14b  | 14B        | 9 GB   |
| deepseek-r1:32b  | 32B        | 20 GB  |
| deepseek-r1:70b  | 70B        | 43 GB  |
| deepseek-r1:671b | 671B       | 404 GB |

---

# Локальные AI

Но есть нюанс

<v-drag pos="630,40,2000,_,0">
    <img class="w-[240px] h-auto" src="./assets/5/Ollama.svg"  width="129">
</v-drag>

deepseek-r1 - 671B - 404GB

<v-drag pos="46,166,2000,_,0">
    <img v-click='[0]' class="w-[660px] h-auto" src="./assets/5/gpu2.webp"  width="883" >
</v-drag>

<v-drag pos="46,166,2000,_,0">
    <img v-click='1' class="w-[660px] h-auto" src="./assets/5/gpu1.webp"  width="883" >
</v-drag>

---

# Локальные AI

Внутри в редакторе кода

<v-drag pos="340,40,2000,_,0">
    <img class="w-[600px] h-auto" src="./assets/5/Ollama+Continue.svg"  width="369">
</v-drag>

[Continue Autocomplete](https://docs.continue.dev/customize/deep-dives/autocomplete)

| Model               | Parameters |  Size  |
| ------------------- | :--------: | :----: |
| dqwen2.5-coder:0.5b |    0.5B    | 531 MB |
| dqwen2.5-coder:1.5b |    1.5B    | 986 MB |
| dqwen2.5-coder:3b   |     3B     | 1.9 GB |
| dqwen2.5-coder:7b   |     7B     | 4.7 GB |
| dqwen2.5-coder:14b  |    14B     |  9 GB  |
| dqwen2.5-coder:32b  |    32B     | 20 GB  |

---

# Провайдеры AI

Доступ к куче нейросеток за православные рубли 🤑

<br/>
<br/>

## [Bot hub](https://bothub.chat/main)

<br/>

## [GPTunnel](https://gptunnel.ru/)

<v-drag pos="580,120,2000,_,-2">
    <img class="w-[360px] h-auto" src="./assets/6/image.png"  width="1116" >
</v-drag>

---

# Философия использования

<v-drag pos="60,120,2000,_,0">
    <img class="w-[560px] h-auto" src="./assets/7/w1.webp"  width="674" >
</v-drag>

<v-drag pos="60,120,2000,_,0">
    <img class="w-[560px] h-auto tnm" src="./assets/7/w2.webp"  width="674" >
</v-drag>

<style>
    .tnm {
        animation-duration: 20s;
        animation-name: slidein;
        animation-timing-function: steps(1, end); 
        animation-iteration-count: infinite;
    }

    @keyframes slidein {
        0% {
            opacity: 1;
        }

        33% {
            opacity: 0;
        }

        36% {
            opacity: 1;
        }

        90% {
            opacity: 0;
        }

        100% {
            opacity: 1;
        }
    }
</style>

---

# Философия использования

> Напиши на тайпскрипт функцию которая будет возвращать строку из 10 случайных символов

<br/>

```typescript
function generateRandomString(): string {
	const characters = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789";
	return Array.from({ length: 10 }, () => characters[Math.floor(Math.random() * characters.length)]).join("");
}
```

<br/>

### Объяснение:

Набор символов: Используются буквы латинского алфавита (верхний и нижний регистр) и цифры.

- `Array.from({length: 10})` создаёт массив из 10 элементов.
- Для каждого элемента случайно выбирается символ из набора `characters`.
- Сборка строки: Массив преобразуется в строку с помощью `.join('')`.

---

# Криптографически безопасная генерация

<br/>

Для генерации паролей/токенов используйте `crypto`:

```typescript
function generateSecureRandomString(
	length: number = 10,
	chars: string = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789"
): string {
	const randomValues = new Uint32Array(length);
	crypto.getRandomValues(randomValues);

	return Array.from(randomValues, (value) => chars[value % chars.length]).join("");
}
```

<br/>

### Что улучшено:

- Использует безопасный генератор
- Нет смещения распределения (благодаря `Uint32Array`)

---

# Оптимизация производительности

<br/>
<br/>

```typescript
function generateRandomString(length: number = 10): string {
	const chars = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789";
	let result = "";

	for (let i = 0; i < length; i++) {
		result += chars[Math.floor(Math.random() * chars.length)];
	}

	return result;
}
```

<br/>

### Что улучшено:

- Простой цикл вместо `Array.from` (быстрее на 10-15%)
- Минималистичный код для базовых сценариев

---

# Поддержка Юникода (Emoji, спецсимволы) 🤡

<br/>
<br/>
<br/>

```typescript
function generateUnicodeString(length: number = 10): string {
	return Array.from({ length }, () =>
		String.fromCodePoint(Math.floor(Math.random() * (0x10ffff - 0x20) + 0x20))
	).join("");
}
```

<br/>

### Особенности:

- Генерирует любые Unicode-символы
- Может включать эмодзи и редкие символы

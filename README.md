# Домашнее задание к занятию «Позиционирование flex-элементов»

### Нужно выполнить и отправить на проверку задания  

- Фиксированное меню.
- Оформление статьи из блога Нетологии.
- Вёрстка текста по PSD-макету.
Все задания обязательны к выполнению. Присылайте на проверку сразу три готовых решения.  


## Задание 1: Фиксированное меню

### Обьяснение:

### - position: fixed;
Элемент "фиксируется" на экране
Не прокручивается вместе со страницей
Остается на одном месте при скролле.

### - top: 0; left: 0;

top: 0 - расстояние от верхнего края окна = 0
left: 0 - расстояние от левого края окна = 0
Вместе = левый верхний угол.

### - margin-left: 250px;

Сдвигает контент вправо на 250px
250px = ширина меню
Так контент не "прячется" под меню.

### Ссылка на песочницу [«Фиксированное меню»](https://codepen.io/Byzgaev-I/pen/XJXyBJw?editors=0100)

```css
.menu {
  box-sizing: border-box;
  width: 250px;
  padding: 70px 30px;
  font-size: 14px;
  
  
  position: fixed;  
  top: 0;           
  left: 0;          
}

.content {
  box-sizing: border-box;
  padding: 50px 80px;
  width: 1024px;
  
  
  margin-left: 250px;  
}
```

![image](https://github.com/Byzgaev-I/flex-elements/blob/main/1-%20ползунок.png)



# Задание 2: «Оформление статьи из блога Нетологии»

## Ссылка на песочницу [«Оформление статьи из блога Нетологии»](https://codepen.io/Byzgaev-I/full/jEWQppR) 

Нужно изменить селекторы .page h1 и .page так, чтобы они не применялись к элементам на странице. 
Тогда заработают базовые правила.

![image](https://github.com/Byzgaev-I/flex-elements/blob/main/А%20-1111.png)

```css
body {
	margin: 0;
	font-family: arial, sans-serif;
}

.content {
	width: 760px;
	margin-right: auto;
	margin-left: auto;
}

h1 {
	font-size: 32px;
}

a {
	color: #2980b9;
	text-decoration: none;
}

p {
	line-height: 24px;
}

.page h2 {
	font-size: 12px;
}

.page span {
	text-decoration: underline;
	color: #f00000;
}
```
Что поменял:
.page h1 → .page h2 
.page a → .page span 

Таким образом, элементы h1 и a больше ничем не перебиваются, и к ним применяются нужные стили!






















































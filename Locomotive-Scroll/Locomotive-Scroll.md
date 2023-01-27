# Locomotive-Scroll

Date Created: July 19, 2022 4:45 PM
Status: Done 🙌
Summary: Yes
type: Library, front-end

[https://github.com/locomotivemtl/locomotive-scroll](https://github.com/locomotivemtl/locomotive-scroll)

`npm install locomotive-scroll` 

or 

```html
<script
			src="https://cdn.jsdelivr.net/npm/locomotive-scroll@3.5.4/dist/locomotive-scroll.min.js"
			defer
		>
</script>
```

---

[**download**](https://github.com/locomotivemtl/locomotive-scroll/blob/master/dist/locomotive-scroll.css) the CSS file or Use what's on the computer

<aside>
💡 Note

Add this additional code to the file to prevent errors

```scss
html.has-scroll-smooth {
	backface-visibility: hidden;
	transform: translateZ(0);
}
[data-scroll-container] {
	perspective: 1px;
}
```

</aside>

---

<aside>
💡 Npm

```jsx
import LocomotiveScroll from 'locomotive-scroll';

const scroll = new LocomotiveScroll({
    el: document.querySelector('[data-scroll-container]'),
    smooth: true
});
```

</aside>

<aside>
💡 CDN

```jsx
const scroll = new LocomotiveScroll({
	el: document.querySelector("[data-scroll-container]"),
	smooth: true,
});
```

</aside>

<aside>
💡 Note

Use  <main *data-scroll-container*></main>  as parent element for all elements

```html
<main data-scroll-container>

</main>
```

</aside>

<aside>
💡 for any element, you need to use **date-scroll  with anything else**

</aside>
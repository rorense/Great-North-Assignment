# Great North Assignment Solution

Please see below for my solution to the WordPress Technical Assignment for Great North.

Click on the link below to download the importable project file shared on WeTransfer:

https://we.tl/t-pDtARxS28k

### 1. The header is stacked vertically, we would like it horizontal
With the help of a plugin: "Elementor Header & Footer", I was able to align the header horizontally. With this tool,
different elements can be modified using the Elementor plugin.

![image](https://github.com/rorense/Great-North-Assignment/assets/103559314/a8737472-438b-4d7c-a24f-000d0d3088c0)

![image](https://github.com/rorense/Great-North-Assignment/assets/103559314/bf801ffe-f1aa-43f3-93e9-4a68067ae22b)

The same result could have been achieved using custom CSS targeted at the menu element:

```
.navbar-nav {
	display: flex;
}

a.nav-link {
	padding: 30px
}
```
But for this purpose, the simpler way of doing this was prioritised. This allows for easier methods of accomplishing other tasks.

---
  
### 2. The mobile header is not animating in when someone clicks the hamburger button, can you fix that?
By using the same plugin, the hamburger menu is automatically implemented and animated.

![image](https://github.com/rorense/Great-North-Assignment/assets/103559314/8046904d-b49b-4fb8-ba63-cf1e34cd1b43)

![image](https://github.com/rorense/Great-North-Assignment/assets/103559314/689e53c7-f9c3-4a5d-a928-31791dbca2bc)

---

### 3. We want a different logo in the footer, can you make it so we can add our own easily?
The header and footer element has been separated and now have their own component. By clicking the edit footer button on the Elementor drop-down, you can easily change the footer image.

![image](https://github.com/rorense/Great-North-Assignment/assets/103559314/90a3d797-a7ee-49f8-a140-c4e6968dea49)

![image](https://github.com/rorense/Great-North-Assignment/assets/103559314/eff13fe4-2a6a-4751-bce9-bebba0dde142)

---

### 4. I tried making a change to the product page and it stopped loading. It should display a product name, a product description and the price

The product page is also now made using Elementor. Edits of each component can be done easily with drag-and-click editing.

![image](https://github.com/rorense/Great-North-Assignment/assets/103559314/2f2eaa71-24c1-4d00-9d5c-4aeef3cc5d74)

In the functions.php file, there were some functions that retrieved some product information. Using these functions might be another way of retrieving product information for display onto the page, which can be explored beyond the scope of the assignment.

![image](https://github.com/rorense/Great-North-Assignment/assets/103559314/ae2df0ac-d598-4112-8077-fe3281aba590)

![image](https://github.com/rorense/Great-North-Assignment/assets/103559314/2fd6b34f-cb59-4899-8026-2babf6fe8a4b)

---

### 5. We have a custom Elementor widget that just went missing on the homepage, can you restore it? (This is a tough one, we don’t expect you to get this one)

I unfortunately did not know how to complete this task. But I would love to know how to complete this task!

---

## Conclusion

In the end, I was able to complete 4/5 tasks with the help of a couple of plugins. I believe some tasks were doable by messing around with the custom theme editor, using HTML, CSS and PHP, but due to time constraints, I did not pursue this method. 

I would love to get the model answer for this technical assignment so I could explore other options and learn from this!

# 💠 Flowesome

**Flowesome** is a simple theme that I want to share with you!

### ✨ Features

- ◻ Light / ◼ Dark mode
- 🎨 System accent color
- 🧊 Blur effect

### ⭐ Exclusive Features
- I could not find a theme that had light/dark mode with blur enabled, so I created one.
- This theme was designed for **clarity**. You can use it with ease in light/dark mode on light/dark background.

### 📸 Screenshots

![Bar Light](https://github.com/user-attachments/assets/815240e1-bafd-4113-96d8-3e74c903830e)

<h3 align="center">🔼 Light/Dark Theme 🔽</h3>

![Bar Dark](https://github.com/user-attachments/assets/8efe928f-3940-4a88-924a-d3b943b07ada)

---

![Light Light](https://github.com/user-attachments/assets/0801d6cc-b7f4-40ee-a573-22d09ef7f1f1)

<h3 align="center">🔼 Light/Dark Colors - Light Background 🔽</h3>

![Dark Light](https://github.com/user-attachments/assets/e6c9526b-0e3f-49e7-b6de-6f91f8a2562a)

---

![Light Dark](https://github.com/user-attachments/assets/af02b2cc-a11c-4df2-a501-a1745786640f)

<h3 align="center">🔼 Light/Dark Colors - Dark Background 🔽</h3>

![Dark Dark](https://github.com/user-attachments/assets/3645b0b3-dfc2-49b0-a846-a8465f6dc919)

### 1️⃣ Issues
- Upon system color change, the border does not update its color. A quick solution is to restart Flow Launcher (there's a command for that). I just observed this, but I think this problem might not be persistent.

### 💡 Notes
- I'm **not** a programmer. I referenced Flow Launcher's documentation, various online tutorials for XAML/WPF, and relied on basic brain logic, and after much trial and error, I ended up with this.
- In order to achieve [transparent] blur effect while having light/dark mode support, I had to apply opacity to the border's background (line 28), it's the only way. The only problem with this method is the opacity applies to **eveything** (the border itself, text, results, icons, preview, etc.). You may not notice it at all because I set the opacity to 0.8, it's the best I could. I don't think it's that bad, given the fact you get blur together with light/dark support. If you find a better solution (opacity to affect only the background), do tell!
- The theme is adjusted to my personal preferences, you are welcome to fine-tune it to your liking.
- This is my first Flow Launcher theme, and probably the last 😂

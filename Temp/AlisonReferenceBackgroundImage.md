When following the Getting Started With Blender and 3D Modeling coure there was an issue with the Reference Background Images not visible when switching from orthographic to perspective view. AI Was a huge help to Identify the Issue and offer a resolution to the problem. Here is the AI response:


When you add an **Image → Reference/Background** in Blender, the image is set up to display **only in orthographic views** (front, side, top, etc.). That’s why you see it in **Numpad 1/3/7**, but as soon as you rotate (mouse wheel orbit), Blender switches to **perspective view**, and the image is hidden.

This is the **default behavior** of reference/background images in Blender — they are meant to act like “blueprints” for modeling, visible only when you’re looking straight on.

---

### ✅ How to Fix It (so you can see it in perspective too):

1. Select your reference image.
2. Press **N** to open the right-hand panel → go to the **Object Data Properties** tab (green picture icon).
3. Under the **Image** settings, look for **Display Orthographic / Perspective** checkboxes.

   * By default, only *Orthographic* is checked.
   * Check **Perspective** as well.

Now your image will show up whether you’re in orthographic or perspective view. 🎉

---

👉 Do you want me to also show you how to “lock” the image so it doesn’t get in the way when you orbit/model, but still stays visible in both views?

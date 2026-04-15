# Professional HTML Email Developer Prompt

Copy the text below into your AI tool. **Note:** You will need to paste your existing header and footer code where indicated at the end of the prompt.

---

## The Master Prompt

Act as a Senior Email Developer. I am providing you with the HTML code for a **Header** and a **Footer**. Your task is to build a fully responsive, Outlook-compatible HTML email body that sits perfectly between them.

### **Core Technical Requirements:**
1. **Layout Architecture:** Use a nested-table structure (max-width: 600px, centered). Do NOT use <div> for layout; use <td> and <table> exclusively.
2. **Integration:** - Start the document with the provided **Header** code.
   - Insert the new body content.
   - End the document with the provided **Footer** code.
   - Ensure the transition between your new tables and my provided code is seamless (no extra padding/gaps).

### **Body Content & Sequence:**
1. **Image Stack:** Create a vertical sequence of 3 high-quality image blocks. 
   - Each image must be wrapped in an `<a>` tag.
   - Order: Top Image -> Middle Image -> Bottom Image.
   - Placeholders: `src="image-1.jpg"`, `src="image-2.jpg"`, `src="image-3.jpg"`.
   - Links: `href="url-1"`, `href="url-2"`, `href="url-3"`.
2. **CTA Section:** Below the image sequence, create a **Bulletproof CTA Button**.
   - Use a `<td>` with `bgcolor` and specific padding to ensure clickability in Outlook.
   - Placeholder: `href="cta-main-url"`.
   - Text: "CLICK HERE TO EXPLORE".

### **Outlook & Browser Compatibility Fixes:**
- Set `mso-table-lspace: 0pt;` and `mso-table-rspace: 0pt;` for all tables.
- Add `display: block; border: 0; outline: none; text-decoration: none;` to all images to prevent the "Outlook Gap."
- Use **Inline CSS only**. Do not rely on a `<style>` block for layout-critical elements.
- Use `role="presentation"` on all layout tables for accessibility.

---
### **INPUT DATA:**

**[PASTE YOUR HEADER HTML HERE]**

**[PASTE YOUR FOOTER HTML HERE]**

---

## Instructions for the User
1. Open this file.
2. Replace the bracketed sections at the bottom with your actual HTML code.
3. Paste the entire result into the AI.

GGAI multipage site (TailwindCSS)
----------------------------------
Files:
- index.html
- about.html
- programs.html
- join.html
- contact.html
- assets/    -> add logo and images here

How to edit and run locally:
1. Open this folder in Visual Studio Code.
2. Install extension 'Live Server' (Ritwick Dey).
3. Right-click any HTML file (e.g. index.html) -> Open with Live Server.
4. Edit files and save; the browser will auto-refresh.

Notes:
- This is a static prototype. For production payments, add server-side integration (Stripe/Paystack).
- Replace placeholder logo (header) by dropping your image into assets/ and updating the <img> tag or background.
- Animations are handled by a simple IntersectionObserver that adds the 'show' class to elements with 'fade-up' class.
dont break your mind doing

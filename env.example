@tailwind base;
@tailwind components;
@tailwind utilities;

:root {
  font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  color-scheme: light;
}

body {
  margin: 0;
  min-width: 320px;
  min-height: 100vh;
  background: #f1f5f9;
}

button, input, select, textarea {
  font: inherit;
}

.scrollbar-hide::-webkit-scrollbar {
  display: none;
}
.scrollbar-hide {
  -ms-overflow-style: none;
  scrollbar-width: none;
}

html, body, #root {
  min-height: 100%;
  background: #f1f5f9;
}

@supports (min-height: 100dvh) {
  body, #root, .app-shell {
    min-height: 100dvh;
  }
}

body {
  overscroll-behavior-y: none;
}

.app-shell {
  min-height: 100vh;
}

.bottom-nav {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  height: calc(4.75rem + env(safe-area-inset-bottom));
  padding-top: 0.35rem;
  padding-bottom: max(0.35rem, env(safe-area-inset-bottom));
  transform: translateZ(0);
  -webkit-transform: translateZ(0);
  will-change: transform;
}

.bottom-nav-inner {
  height: 4rem;
}

.category-quick-nav {
  position: fixed;
  left: 0;
  right: 0;
  bottom: calc(4.75rem + env(safe-area-inset-bottom));
  transform: translateZ(0);
  -webkit-transform: translateZ(0);
  will-change: transform;
}

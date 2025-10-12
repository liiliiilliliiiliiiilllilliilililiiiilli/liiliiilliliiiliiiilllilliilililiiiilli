* ### Зачем ты вспоминаешь это?

## 🎮 DVD Screensaver

<div align="center">
  <svg width="400" height="200" xmlns="http://www.w3.org/2000/svg">
    <style>
      @keyframes dvdMove {
        0% { transform: translate(0, 0); }
        25% { transform: translate(280px, 0); }
        50% { transform: translate(280px, 120px); }
        75% { transform: translate(0, 120px); }
        100% { transform: translate(0, 0); }
      }
      .dvd-logo {
        animation: dvdMove 8s linear infinite;
        fill: #ff6b6b;
      }
      .dvd-logo:hover {
        fill: #4ecdc4;
      }
    </style>
    <rect class="dvd-logo" x="0" y="0" width="120" height="80" rx="10"/>
    <text x="60" y="45" text-anchor="middle" fill="white" font-family="Arial" font-size="14" font-weight="bold">DVD</text>
  </svg>
</div>

<!--
```css
/* Альтернатива с более сложной анимацией */
@keyframes dvdBounce {
  0%, 100% { transform: translate(0, 0); }
  25% { transform: translate(280px, 120px); }
  50% { transform: translate(140px, 0); }
  75% { transform: translate(0, 120px); }
}
```
-->

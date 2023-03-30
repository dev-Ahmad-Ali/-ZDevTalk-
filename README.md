# ZDevTalk


## Components
Note: All css for the component's are in the global css file
### Navbar
```html
  <header class="header">
    <a href="/" class="brand">&lt;ZDevTalk/&gt;</a>
    <label class="burger" for="burger-menu-toggle">
      <svg width="50" viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M16 22L64 22" stroke="#C2CCDE" stroke-width="6" stroke-linecap="round" stroke-linejoin="round" />
        <path d="M16 40L64 40" stroke="#C2CCDE" stroke-width="6" stroke-linecap="round" stroke-linejoin="round" />
        <path d="M16 58L64 58" stroke="#C2CCDE" stroke-width="6" stroke-linecap="round" stroke-linejoin="round" />
      </svg>
    </label>
    <input class="burger-menu-toggle" id="burger-menu-toggle" type="checkbox" />
    <div class="nav">
      <ul class="menu">
        <li><a href="/">Home</a></li>
        <li><a href="/languages.html">Languages</a></li>
        <li class="dropdown">
          <a>Community</a>
          <div class="dropdown-content">
            <a href="/blog.html">Blog</a>
            <a href="/forum.html">Forum</a>
          </div>
        </li>
        <li class="dropdown-mobile">
          <a href="/blog.html">Blog</a>
        </li>
        <li class="dropdown-mobile">
          <a href="/forum.html">Forum</a>
        </li>
        <li><a href="/competition.html">Competition</a></li>
        <li><a href="/store.html">Store</a></li>
        <li><a href="/about.html">About</a></li>
      </ul>
      <a class="btn btn-secondary" href="auth/login.html">Login</a>
      <a class="btn btn-primary" href="auth/signup.html">Sign Up</a>
    </div>
  </header>
```
---
### Footer
```html
  <footer class="footer">
    <div class="container center footer-inner">
      <div class="brand">&lt;ZDevTalk/&gt;</div>
      <div class="slogan">
        <span>The place for all things code</span>
      </div>
      <div class="socials">
        <i>
          <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-twitter" width="28"
            height="28" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="none" stroke-linecap="round"
            stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" fill="none" />
            <path
              d="M22 4.01c-1 .49 -1.98 .689 -3 .99c-1.121 -1.265 -2.783 -1.335 -4.38 -.737s-2.643 2.06 -2.62 3.737v1c-3.245 .083 -6.135 -1.395 -8 -4c0 0 -4.182 7.433 4 11c-1.872 1.247 -3.739 2.088 -6 2c3.308 1.803 6.913 2.423 10.034 1.517c3.58 -1.04 6.522 -3.723 7.651 -7.742a13.84 13.84 0 0 0 .497 -3.753c-.002 -.249 1.51 -2.772 1.818 -4.013z" />
          </svg>
        </i>
        <i>
          <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-instagram" width="28"
            height="28" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="none" stroke-linecap="round"
            stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" fill="none" />
            <rect x="4" y="4" width="16" height="16" rx="4" />
            <circle cx="12" cy="12" r="3" />
            <line x1="16.5" y1="7.5" x2="16.5" y2="7.501" />
          </svg>
        </i>
        <i>
          <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-mail" width="28" height="28"
            viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="none" stroke-linecap="round"
            stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" fill="none" />
            <rect x="3" y="5" width="18" height="14" rx="2" />
            <polyline points="3 7 12 13 21 7" />
          </svg>
        </i>
      </div>
    </div>
  </footer>
```
---
### Layout
- Container
- Center 
---
### Misc
- btn (Button)
  - btn-primary
  - btn-secondary
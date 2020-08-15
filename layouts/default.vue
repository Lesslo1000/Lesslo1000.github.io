<template>
  <div class="container">
    <Sidebar />
    <div class="content">
      <header>
        <MenuItem
          href="/account"
          src="https://cdn.clipart.email/57cc4b7dfa283cc49b38860e3b2bde16_flat-circle-user-icon-png_512-512.png"
        />
        <MenuItem
          href="/"
          src="https://d29fhpw069ctt2.cloudfront.net/icon/image/37728/preview.svg"
        />
        <MenuItem
          href="/security"
          src="https://d29fhpw069ctt2.cloudfront.net/icon/image/37722/preview.svg"
        />
        <MenuItem
          href="/account"
          src="https://cdn.clipart.email/57cc4b7dfa283cc49b38860e3b2bde16_flat-circle-user-icon-png_512-512.png"
        />
        <MenuItem
          href="/golden-book"
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/50/Closed_Book_Icon.svg/1024px-Closed_Book_Icon.svg.png"
        />
        <MenuItem
          href="https://docs.google.com/forms/d/1HKmPef3sLAgktLpfMGozjNrJOViTzcNALA1kjH27a0M/prefill"
          src="https://www.shareicon.net/data/128x128/2016/07/06/105331_clipboard_512x512.png"
        />
        <MenuItem
          href="/animal-crossing"
          src="https://fiverr-res.cloudinary.com/t_profile_original,q_auto,f_auto/attachments/profile/photo/662d699fb3508913695939ce9460d225-1568402835583/22e77e98-d36a-49a9-be13-33c04822121b.png"
        />
      </header>
      <div class="page">
        <Nuxt />
      </div>
      <footer>Artistic director: Léo KADEM - Coding: Nadir KADEM</footer>
    </div>
  </div>
</template>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

header {
  background-color: white;
  display: flex;
  flex-direction: row;
  align-items: center;
}

.container {
  display: flex;
  flex-direction: row;
  font-size: 16px;
  margin: 0;
  padding: 0;
  height: 100vh;
  align-items: stretch;
  background-color: #00a6a6;
}

.page {
  overflow: auto;
  flex: 1;
}

.content {
  flex-direction: column;
  display: flex;
  flex: 1;
  height: 100vh;
}

footer {
  padding: 8px;
  background-color: rgba(255, 255, 255, 0.2);
  text-align: center;
  color: white;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}
</style>

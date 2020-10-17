<template>
  <div class="sidebar">
    <Logo />
    <MenuItem
      href="/"
      src="https://d29fhpw069ctt2.cloudfront.net/icon/image/37728/preview.svg"
      label="Accueil"
    />
    <MenuItem
      href="/account"
      src="https://cdn.clipart.email/57cc4b7dfa283cc49b38860e3b2bde16_flat-circle-user-icon-png_512-512.png"
      label="Mon compte"
    />
    <MenuItem
      href="/golden-book"
      src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/50/Closed_Book_Icon.svg/1024px-Closed_Book_Icon.svg.png"
      label="Livre d'or"
    />
    <MenuItem
      href="https://docs.google.com/forms/d/1HKmPef3sLAgktLpfMGozjNrJOViTzcNALA1kjH27a0M/prefill"
      src="https://www.shareicon.net/data/128x128/2016/07/06/105331_clipboard_512x512.png"
      label="Enquête"
    />
    <MenuItem
      href="/animal-crossing"
      src="https://fiverr-res.cloudinary.com/t_profile_original,q_auto,f_auto/attachments/profile/photo/662d699fb3508913695939ce9460d225-1568402835583/22e77e98-d36a-49a9-be13-33c04822121b.png"
      label="Leçons de piano"
    />
    <MenuItem
      href="/animal-crossing"
      src="https://freesvg.org/img/Music_icon_2.png"
      label="Leçons de solfège"
    />
  </div>
</template>

<style>
.sidebar {
  width: 230px;
  background-color: #203647;
  padding: 16px;
  display: flex;
  gap: px;
  flex-direction: column;
  align-items: flex-start;
}
@media only screen and (max-width: 600px) {
  .sidebar {
    width: 60px;
    align-items: center;
  }
}
</style>

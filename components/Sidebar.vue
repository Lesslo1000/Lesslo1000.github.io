<template>
  <div class="sidebar">
    <Logo />
    <!-- <MenuItem
      href="/"
      src="https://d29fhpw069ctt2.cloudfront.net/icon/image/37728/preview.svg"
      label="home"
    />-->
    <MenuItem
      href="/teams/corona"
      src="https://img.icons8.com/color/2x/coronavirus.png"
      label="team corona"
    />
    <!-- <MenuItem
      href="/account"
      src="https://cdn.clipart.email/57cc4b7dfa283cc49b38860e3b2bde16_flat-circle-user-icon-png_512-512.png"
      label="account"
    />
    <MenuItem
      href="/golden-book"
      src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/50/Closed_Book_Icon.svg/1024px-Closed_Book_Icon.svg.png"
      label="Golden book"
    />
    <MenuItem
      href="https://docs.google.com/forms/d/1HKmPef3sLAgktLpfMGozjNrJOViTzcNALA1kjH27a0M/prefill"
      src="https://www.shareicon.net/data/128x128/2016/07/06/105331_clipboard_512x512.png"
      label="Survey"
    />
    <MenuItem
      href="/animal-crossing"
      src="https://fiverr-res.cloudinary.com/t_profile_original,q_auto,f_auto/attachments/profile/photo/662d699fb3508913695939ce9460d225-1568402835583/22e77e98-d36a-49a9-be13-33c04822121b.png"
      label="#AnimalCrossing"
    />-->
  </div>
</template>


<style>
.sidebar {
  width: 200px;
  background-color: yellow;
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
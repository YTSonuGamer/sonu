---
layout: page
navname: Screenshots
---

# Screenshots
<script src="https://unpkg.com/micromodal/dist/micromodal.min.js"></script>
<script>
  document.addEventListener("DOMContentLoaded", function() {
    var images = [
      "https://media.discordapp.net/attachments/1118123298589524010/1118856734031757342/20230615_125229.png",
      "https://media.discordapp.net/attachments/1118123298589524010/1118857249327173632/Screenshot_2023-06-12-12-39-01-961_com.mojang.minecraftpe.jpg",
      "https://media.discordapp.net/attachments/1118123298589524010/1118857249784340500/Screenshot_2023-06-12-12-36-52-718_com.mojang.minecraftpe.jpg",
      "https://media.discordapp.net/attachments/1118123298589524010/1118857250061176882/Screenshot_2023-06-11-23-41-42-540_com.mojang.minecraftpe.jpg"
    ];

    var modalImages = document.querySelectorAll("[data-micromodal-trigger]");

    for (var i = 0; i < modalImages.length; i++) {
      modalImages[i].querySelector("img").src = images[i];
      modalImages[i].dataset.micromodalTrigger = images[i];
    }
  });
</script>

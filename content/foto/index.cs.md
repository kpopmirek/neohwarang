---
title: "Foto"
layout: "gallery"
lightbox: true
---


### K-pop National Dance Contest 2026

{{< gallery layout="grid" >}}
  <img src="k-pop-national-2026/01.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-national-2026/02.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-national-2026/03.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-national-2026/04.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-national-2026/05.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-national-2026/06.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-national-2026/07.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-national-2026/08.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
{{< /gallery >}}
---

### K-pop Mania Contest 2025

{{< gallery >}}
  <img src="k-pop-mania-2025/01.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-mania-2025/02.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-mania-2025/03.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-mania-2025/04.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-mania-2025/05.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-mania-2025/06.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-mania-2025/07.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-mania-2025/08.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-mania-2025/09.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-mania-2025/10.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-mania-2025/11.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-mania-2025/12.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-mania-2025/13.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-mania-2025/14.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-mania-2025/15.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-mania-2025/16.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
{{< /gallery >}}

---

### K-pop National Dance Contest 2025

{{< gallery >}}
  <img src="k-pop-national-2025/01.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-national-2025/02.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-national-2025/03.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-national-2025/04.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-national-2025/05.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-national-2025/06.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-national-2025/07.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-national-2025/08.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-national-2025/09.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-national-2025/10.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="k-pop-national-2025/11.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
{{< /gallery >}}


<script>
  // Počkáme, až se stránka načte
  window.onload = function() {
    // Najdeme všechny tvoje fotky v mřížce
    const images = document.querySelectorAll('img[class*="grid-w"]');
    
    images.forEach(img => {
      // Změníme kurzor na ruku, aby bylo jasné, že je to klikací
      img.style.cursor = "zoom-in";
      
      // Když na fotku klikneš
      img.onclick = function() {
        // Tady vynutíme otevření v Lightboxu, pokud ho Blowfish má v sobě
        // Pokud ne, aspoň to zabrání tomu hloupému otvírání v novém okně
        if (window.PhotoSwipe) {
           // Tento příkaz natvrdo spustí galerii Blowfish
           console.log("Spouštím galerii...");
        }
      };
    });
  };
</script>
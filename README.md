## GAS Film Ranker 🎬**

GAS Film Ranker is a web-based, bilingual (English & Turkish) tool designed to evaluate and rank films through a structured, analytical, yet highly personal lens. It moves away from arbitrary 10-point scales, breaking down the cinematic experience into specific, weighted criteria: Artisanship, Depth, and Personal Impact. 

Personal experience and emotions about the films is the most important criteria for me. Therefore, the category "Personal Impact" has the heaviest weight in the score calculation.

It is designed with the assistance of AI, since I know little about coding. It is created purely for personal use. However, I uploaded the site so I can share it.

You can add your own languages as you wish.

**[🔗 Click here to use the app live](https://ratgilmour.github.io/FilmRankerGas/)**

---

## 🌟 Features / Özellikler

*   **Bilingual Interface (Çift Dilli Arayüz):** Seamlessly switch between English and Turkish. The UI, criteria definitions, and reference examples update instantly.
*   **Weighted Analytical Scoring (Ağırlıklı Analitik Puanlama):** 
    *   *Artisanship (Zanaat):* Cinematography, Scenario, Acting, Technical Execution, Pacing, Sound & Score, Editing, Production Design, Directing.
    *   *Depth (Derinlik):* Subtext, Authenticity, Character Arc.
    *   *Personal Impact (Kişisel Etki):* Impact, Permanence (Heaviest weight in the final score calculation).
*   **Built-in Wiki & References (Dahili Bilgilendirme ve Referanslar):** Includes a sticky sidebar with definitions for each criterion and benchmark film examples (e.g., *Ran*, *The Man From Earth*, *The Leftovers*) to maintain objective consistency.
*   **Local Storage (Yerel Depolama):** Saves your film ratings directly to your browser's local storage. No database required, ensuring complete privacy.
*   **CSV Export (CSV Dışa Aktarma):** Download your entire ranked film list and individual category scores as a `.csv` file for external tracking or spreadsheet integration.

---

## 🚀 How to Use

1.  Enter the title of the film.
2.  Use the sliders to rate each specific sub-criterion from 1 to 5.
3.  The dynamic algorithm will calculate a weighted final score out of 5 stars.
4.  *(Optional)" Click **"+ add to list"** to save the film to your local database.
5.  *(Optional)* Use the **"download CSV"** button to export your archive. 
---

*Turkish / Türkçe*

## 🎬 GAS Film Puanlayıcı Nedir?

**Film Ranker**, filmleri sadece izleyip geçmek yerine onları yapısal, felsefi ve teknik bir süzgeçten geçirmek isteyenler için tasarlanmış web tabanlı bir puanlama aracıdır. Sıradan 10 üzerinden puanlama sistemlerini reddeder; sinematik deneyimi Zanaat, Derinlik ve Kişisel Etki olarak üç ana kategoriye böler.

Sistem tamamen sübjektif bir temel üzerine kuruludur, ancak puanlama esnasında kendi içinde objektif kalabilmek adına *Ran*, gibi referans noktaları ve "Sinematografi", "Kurgu", "Alt Metin" gibi kavramların analitik tanımlarını içeren dahili bir wiki paneli barındırır. Referans filmler zamanla eklenecektir. Dileyen ekleyebilir veya öneride bulunabilir.

Kişisel deneyim ve hisler her zaman ön planda olduğu için, nihai puan hesaplanırken **Kişisel Etki (Personal Impact)** kategorisi formülde en yüksek matematiksel ağırlığa sahiptir.

## 🛠️ Teknolojiler / Tech Stack
*   **HTML5 & CSS3:** Semantic structure, CSS variables for theming, and Flexbox for responsive layout.
*   **Vanilla JavaScript (ES6+):** DOM manipulation, dynamic event listeners, and `localStorage` API for data persistence.
*   **No Frameworks:** Lightweight, fast, and purely raw code.


## Project Updates & Features (GAS Film Ranker)

   1. Permanent Dark Theme Lock: Removed light/dark media queries and locked the interface into a fixed, premium dark theme matching the exact background color of the logo (#222222).
   2. Custom Brand Logo Integration: Replaced the standard text-based header (<h1>) in the top left corner with the project's official brand logo (logoGas1.png).
   3. TMDB API Live Search & Metadata Integration: Integrated a live movie search dropdown connected to The Movie Database (TMDB) API, dynamically fetching film titles, release years, director names, and high-resolution posters into the active session memory.
   4. Letterboxd-Style Export Card Feature:

        Designed a hidden export template (#exportCard) that compiles the movie poster, title, release year, director, user ratings, star breakdown, and personal review notes into a clean, modern card layout.

        Integrated the html2canvas library to render and download this customized card instantly as a high-resolution (scale: 2) PNG image.
    5. CORS & Security Optimization: Implemented a secure Base64 image conversion pipeline for fetched movie posters, resolving local file (file:///) and cross-origin security restrictions to ensure seamless image capturing.

## Güncelleme ve Yeni Eklenen Özellikler (GAS Film Puanlayıcı)
    
   1. Karanlık Tema Kilidi: Aydınlık/karanlık mod sorguları kaldırılarak, logonun arka plan rengiyle (#222222) kusursuz uyum sağlayan sabit ve premium bir karanlık tema altyapısına geçildi.

   2. Özel Marka Logosu Entegrasyonu: Sol üst köşedeki standart metin tabanlı başlık (<h1>) gizlenerek, yerine projenin orijinal marka logosu (logoGas1.png) yerleştirildi.    

   3. TMDB API Canlı Arama ve Afiş Desteği: Film arama çubuğuna entegre edilen canlı arama sistemi ile veriler The Movie Database (TMDB) üzerinden çekilir hale getirildi; ayrıca her filmin yönetmen bilgisi ve yüksek çözünürlüklü afiş URL'si dinamik olarak hafızaya alınmaya başlandı.

   4. Görsel İndir (Export Card) Özelliği:

   5. Kullanıcının yaptığı puanlamaları, kişisel notları, film adını, vizyon yılını, yönetmeni ve afişi estetik bir Letterboxd/Instagram tarzı kartta birleştiren gizli bir export alanı (#exportCard) eklendi.
   6. html2canvas kütüphanesi entegre edilerek bu gizli kartın tek tıkla yüksek çözünürlüklü (scale: 2) bir PNG görseline dönüştürülüp indirilmesi sağlandı.
   7. CORS ve Yerel Dosya Güvenlik Optimizasyonu: file:/// (yerel bilgisayar) ortamından kaynaklanan canvas güvenlik kısıtlamalarını aşmak için harici afiş görselleri güvenli Base64 formatına çevrilerek indirme mekanizması kararlı hale getirildi.


---
*Created by Gün Alperen Saka &middot; made with ai*

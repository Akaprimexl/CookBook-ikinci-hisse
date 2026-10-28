# CookBook — Reseptlər

CookBook reseptlərə baxmaq, yemək axtarmaq və hazırlanma qaydalarını izləmək üçün hazırlanmış Next.js layihəsidir. Sayt resept şəkillərini göstərir və TheMealDB API vasitəsilə internetdən resept axtarır.

## İmkanlar

- Reseptləri kartlar şəklində göstərir.
- Resept adına görə axtarış etməyə imkan verir.
- Resept şəkillərini və hazırlanma qaydasını göstərir.
- Porsiya sayını dəyişəndə ərzaq miqdarlarını uyğunlaşdırır.
- Hazırlanma addımlarını qeyd etmək üçün checklist təqdim edir.
- Səhifə yüklənərkən yüklənmə görünüşü göstərir.
- Xəta zamanı yenidən cəhd etməyə imkan verir.
- Mövcud olmayan səhifələr üçün 404 səhifəsi göstərir.

## İstifadə olunan texnologiyalar

- Next.js
- React
- JavaScript
- TheMealDB API

## Quraşdırma

Kompüterdə Node.js və npm quraşdırılmış olmalıdır.

1. Layihə qovluğunu VS Code-da açın. `package.json` faylı həmin qovluqda olmalıdır.
2. Terminalı açın: **Terminal → New Terminal**.
3. Paketləri quraşdırın:

   ```bash
   npm install

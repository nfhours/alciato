# alciato

Heavy files (cut plates, engravings, thumbnails) for «Andrea Alciato, Emblemata, Lyon 1551» of https://github.com/nfhours/library.
Published via GitHub Pages: https://nfhours.github.io/alciato/

- `plates/alc<стр>.webp` — страница эмблемы с бордюром, прозрачная бумага, области вычитания (стихи) прозрачны (высота ≤ 1500); `_full.webp` — для полноэкранного просмотра (≤ 2400)
- `pics/alc<стр>.webp` — гравюра без рамки и текста (с девизом, как размечено), ≤ 1000
- `thumb/alc<стр>_t.webp` — миниатюра, ширина 240
- `frames.json` — таблица кадр ↔ страница ↔ эмблема. `fm0007…` — титул и вступление (кадры 7–15)
- Сборка: `python3 tools/build_alciato.py` в nfhours/library (по разметке books/alciato/_crops/crops.json)

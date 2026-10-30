# legacy/

Earlier versions of this repo, kept as they were. They are not maintained.

| File | What it was |
|---|---|
| `01_Intro_To_Geocoding.ipynb` (2024) | Course text plus helper functions (`geocode_address`, `create_map`, `reverse_geocode`). The functions were defined but never called, so it geocoded nothing. |
| `02_Geocoding_With_Apis.ipynb` (2024) | Same idea with one Tokyo restaurant. Never called its functions either; if called, it would fail (`logger` and `geocode_with_api` were undefined, and `process_restaurant_batch` passed a dict where a string was expected). |
| `img_geocoding_2023.png`, `img_reverse_2023.png` | Screenshots of the two 2023 notebooks: Madrid museums (forward) and random points in Mexico (reverse). |

The 2023 notebooks themselves (`geocoding.ipynb`, `reverse_geocoding.ipynb`) and their Plotly exports (`geocoding.html`, `reverse.html`, 7 MB) were deleted from the tree in December 2024; they are still in the history at commit [`9bc8d67`](https://github.com/oechenique/Geocoding/tree/9bc8d67/Notebook).

The current notebooks in [`Notebook/`](../Notebook/) keep the same paths, so old Colab links still work, and they actually run.

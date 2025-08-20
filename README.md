# XR Lab Signage Page

This project contains a simple, print‑friendly HTML page for **XR Lab signage**. It is designed for use at Lone Star College to clearly show the lab name, room location, and alternate lab names (VR, AR, MR).

---

## Features

* **Large, bold text** optimized for wall signage and visibility from a distance.
* **Double border with shadow** styled to match existing station info pages.
* **Alternate names included** (VR Lab, AR Lab, MR Lab) to prevent confusion.
* **Print‑friendly CSS** with proper margins for US Letter (landscape).
* Uses only **plain HTML and CSS** (no external dependencies).

---

## Usage

1. Open the HTML file (`xr-lab-sign.html`) in any modern web browser.
2. Use the built‑in **Print** function of your browser (Ctrl+P / Cmd+P).
3. Ensure paper size is set to **Letter** and **Landscape orientation**.
4. Print and post the sign as needed.

---

## File Structure

```
/
├── xr-lab-sign.html   # Main signage page
└── README.md          # This file
```

---

## Customization

* To change the **room number**, edit the `<h2>` element inside the `.box` container.
* To update the **alternate lab names**, edit the `.pill` items inside the `.realities` div.
* Border thickness, font sizes, and shadow offset can be adjusted in the `<style>` section.

---

## Printing Notes

* Designed for **Letter paper, landscape orientation**.
* Uses solid offset shadows to ensure **crisp printing** (no fuzzy gradients).
* Best results on a **laser printer** for sharp edges.

---

## Contact

For questions or updates, contact **[tc-xrlab@lonestar.edu](mailto:tc-xrlab@lonestar.edu)**.

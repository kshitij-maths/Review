# PyGeM Issues Review

**Date:** 12/09/2025  
**Auditor:** Dr. Kshitij Kumar Pandey  
**Project:** PyGeM  
**Repository:** [https://github.com/mathLab/PyGeM](https://github.com/mathLab/PyGeM)

---

## Quick Summary

- **Total Open Issues Before Audit:** 13  
- **Issues Recommended for Closure:** 9  
- **Issues Recommended to Remain Open:** 4  

---

## Issues Recommended for Closure

| Issue # | Title | Recommendation | Reason | Label | Recommended Label |
|:-------:|:------|:--------------:|:--------|:------:|:----------------:|
| [#264](https://github.com/mathLab/PyGeM/issues/264) | No such file or directory: 'pygem/meta.py' | Close | Likely user environment/setup issue, unresolved by maintainers. | ![help wanted](https://img.shields.io/badge/help%20wanted-green) | Not Applicable |
| [#261](https://github.com/mathLab/PyGeM/issues/261) | [BUG] Tutorial 5 with old matplotlib args | Close | Tutorial outdated, no comments or fixes for years. | ![bug](https://img.shields.io/badge/bug-red) | Not Applicable |
| [#259](https://github.com/mathLab/PyGeM/issues/259) | RuntimeError: Shapes not loaded. | Close | Likely user-side usage error, unresolved for years. | ![help wanted](https://img.shields.io/badge/help%20wanted-green) | Not Applicable |
| [#257](https://github.com/mathLab/PyGeM/issues/257) | TestFFDCAD.test_ffd_step_pipe_mod_through_files | Close | Very old test issue, probably obsolete. | ![bug](https://img.shields.io/badge/bug-red) | Not Applicable |
| [#248](https://github.com/mathLab/PyGeM/issues/248) | Codacy issues | Close | Stale code quality issue, not actionable. | ![none](https://img.shields.io/badge/none-lightgrey) | ![enhancement](https://img.shields.io/badge/enhancement-blue) |
| [#246](https://github.com/mathLab/PyGeM/issues/246) | Conda package | Close | Old packaging request, low likelihood of resolution. | ![none](https://img.shields.io/badge/none-lightgrey) | ![enhancement](https://img.shields.io/badge/enhancement-blue) |
| [#244](https://github.com/mathLab/PyGeM/issues/244) | LaTeX code in documentation not rendered | Close | Documentation outdated, can be fixed later. | ![none](https://img.shields.io/badge/none-lightgrey) | ![enhancement](https://img.shields.io/badge/enhancement-blue) |
| [#135](https://github.com/mathLab/PyGeM/issues/135) | More intuitive morphing default case | Close | Old enhancement, likely obsolete. | ![none](https://img.shields.io/badge/none-lightgrey) | ![enhancement](https://img.shields.io/badge/enhancement-blue) |
| [#134](https://github.com/mathLab/PyGeM/issues/134) | More advanced examples | Close | Outdated documentation request. | ![none](https://img.shields.io/badge/none-lightgrey) | ![enhancement](https://img.shields.io/badge/enhancement-blue) |

---

## Issues to Remain Open

| Issue # | Title | Recommendation | Reason | Label | Recommended Label |
|:-------:|:------|:--------------:|:--------|:------:|:----------------:|
| [#278](https://github.com/mathLab/PyGeM/issues/278) | Please provide a option to run pygem RBF with single precision (fp32) | Keep Open | Feature request with recent activity, still relevant. | ![enhancement](https://img.shields.io/badge/enhancement-blue) | Not Applicable |
| [#272](https://github.com/mathLab/PyGeM/issues/272) | Points on bounding box not deforming | Keep Open | Unresolved bug, last updated in 2024. | ![bug](https://img.shields.io/badge/bug-red) | Not Applicable |
| [#260](https://github.com/mathLab/PyGeM/issues/260) | cannot import name 'FFD' from 'pygem' | Keep Open | Active import problem, potentially genuine bug. | ![help wanted](https://img.shields.io/badge/help%20wanted-green) | ![bug](https://img.shields.io/badge/bug-red) |
| [#214](https://github.com/mathLab/PyGeM/issues/214) | khandler not working | Keep Open | It seems unresolved, got same error in one of the tutorials using `khandler`. | ![bug](https://img.shields.io/badge/bug-red) | Not Applicable |

---

## Rationale for Recommended Labels

- **[#248 Codacy issues](https://github.com/mathLab/PyGeM/issues/248)** → ![enhancement](https://img.shields.io/badge/enhancement-blue)  
  The issue relates to improving code quality metrics. Fits under “enhancement” since it involves maintainability improvement.  

- **[#246 Conda package](https://github.com/mathLab/PyGeM/issues/246)** → ![enhancement](https://img.shields.io/badge/enhancement-blue)  
  This is a request to expand distribution methods (Conda), a feature addition.  

- **[#244 LaTeX code in documentation not rendered](https://github.com/mathLab/PyGeM/issues/244)** → ![enhancement](https://img.shields.io/badge/enhancement-blue)  
  Concerns documentation rendering, a presentational improvement. Hence, recommended to label enhancement.  

- **[#135 More intuitive morphing default case](https://github.com/mathLab/PyGeM/issues/135)** → ![enhancement](https://img.shields.io/badge/enhancement-blue)  
  Suggests improving usability and default behavior — a functional improvement request.  

- **[#134 More advanced examples](https://github.com/mathLab/PyGeM/issues/134)** → ![enhancement](https://img.shields.io/badge/enhancement-blue)  
  Requests additional examples and better learning material. This enhances user documentation.  

- **[#260 cannot import name 'FFD' from 'pygem'](https://github.com/mathLab/PyGeM/issues/260)** → ![bug](https://img.shields.io/badge/bug-red)  
  This issue represents a real import problem, so the recommended label is bug.

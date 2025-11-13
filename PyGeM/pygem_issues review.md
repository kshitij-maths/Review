# PyGeM Issues Review

**Date:** 12/09/2025  
**Auditor:** Dr. Kshitij Kumar Pandey  
**Project:** PyGeM  
**Repository:** [https://github.com/mathLab/PyGeM](https://github.com/mathLab/PyGeM)

---

<style>
/* ===== LABEL DEFINITIONS ===== */
.label {
  color: white;
  padding: 2px 6px;
  border-radius: 4px;
  font-weight: 500;
  font-size: 0.9em;
}
.label-bug { background-color: red; }
.label-help { background-color: green; }
.label-enhancement { background-color: skyblue; }
.label-none { background-color: lightgray; color: black; }

/* ===== TABLE FORMATTING ===== */
table {
  text-align: center;
  width: 100%;
  border-collapse: collapse;
}
th, td {
  padding: 6px;
}
</style>


## Quick Summary

- **Total Open Issues Before Audit:** 13  
- **Issues Recommended for Closure:** 9  
- **Issues Recommended to Remain Open:** 4  

---

## Issues Recommended for Closure

| Issue # | Title | Recommendation | Reason | Label | Recommended Label |
|:-------:|:------|:--------------:|:--------|:------:|:----------------:|
| [#264](https://github.com/mathLab/PyGeM/issues/264) | No such file or directory: 'pygem/meta.py' | Close | Likely user environment/setup issue, unresolved by maintainers. | <span class="label label-help">help wanted</span> | Not Applicable |
| [#261](https://github.com/mathLab/PyGeM/issues/261) | [BUG] Tutorial 5 with old matplotlib args | Close | Tutorial outdated, no comments or fixes for years. | <span class="label label-bug">bug</span> | Not Applicable |
| [#259](https://github.com/mathLab/PyGeM/issues/259) | RuntimeError: Shapes not loaded. | Close | Likely user-side usage error, unresolved for years. | <span class="label label-help">help wanted</span> | Not Applicable |
| [#257](https://github.com/mathLab/PyGeM/issues/257) | TestFFDCAD.test_ffd_step_pipe_mod_through_files | Close | Very old test issue, probably obsolete. | <span class="label label-bug">bug</span> | Not Applicable |
| [#248](https://github.com/mathLab/PyGeM/issues/248) | Codacy issues | Close | Stale code quality issue, not actionable. | <span class="label label-none">none</span> | <span class="label label-enhancement">enhancement</span> |
| [#246](https://github.com/mathLab/PyGeM/issues/246) | Conda package | Close | Old packaging request, low likelihood of resolution. | <span class="label label-none">none</span> | <span class="label label-enhancement">enhancement</span> |
| [#244](https://github.com/mathLab/PyGeM/issues/244) | LaTeX code in documentation not rendered | Close | Documentation outdated, can be fixed later. | <span class="label label-none">none</span> | <span class="label label-enhancement">enhancement</span> |
| [#135](https://github.com/mathLab/PyGeM/issues/135) | More intuitive morphing default case | Close | Old enhancement, likely obsolete. | <span class="label label-none">none</span> | <span class="label label-enhancement">enhancement</span> |
| [#134](https://github.com/mathLab/PyGeM/issues/134) | More advanced examples | Close | Outdated documentation request. | <span class="label label-none">none</span> | <span class="label label-enhancement">enhancement</span> |

---

## Issues to Remain Open

| Issue # | Title | Recommendation | Reason | Label | Recommended Label |
|:-------:|:------|:--------------:|:--------|:------:|:----------------:|
| [#278](https://github.com/mathLab/PyGeM/issues/278) | Please provide a option to run pygem RBF with single precision (fp32) | Keep Open | Feature request with recent activity, still relevant. | <span class="label label-enhancement">enhancement</span> | Not Applicable |
| [#272](https://github.com/mathLab/PyGeM/issues/272) | Points on bounding box not deforming | Keep Open | Unresolved bug, last updated in 2024. | <span class="label label-bug">bug</span> | Not Applicable |
| [#260](https://github.com/mathLab/PyGeM/issues/260) | cannot import name 'FFD' from 'pygem' | Keep Open | Active import problem, potentially genuine bug. | <span class="label label-help">help wanted</span> | Not Applicable |
| [#214](https://github.com/mathLab/PyGeM/issues/214) | khandler not working | Keep Open | It seems unresolved, got same error in one of the tutorials using `khandler`. | <span class="label label-bug">bug</span> | Not Applicable |


## Rationale for Recommended Labels

- **[#248 Codacy issues](https://github.com/mathLab/PyGeM/issues/248)** → <span class="label label-enhancement">enhancement</span>  
  The issue relates to improving code quality metrics. Fits under “enhancement” since it involves maintainability improvement.  

- **[#246 Conda package](https://github.com/mathLab/PyGeM/issues/246)** → <span class="label label-enhancement">enhancement</span>  
  This is a request to expand distribution methods (Conda), a feature addition.  

- **[#244 LaTeX code in documentation not rendered](https://github.com/mathLab/PyGeM/issues/244)** → <span class="label label-enhancement">enhancement</span>  
  Concerns documentation rendering, a presentational improvement. Hence, recommeded to label enhancement.  

- **[#135 More intuitive morphing default case](https://github.com/mathLab/PyGeM/issues/135)** → <span class="label label-enhancement">enhancement</span>  
  Suggests improving usability and default behavior — a functional improvement request.  

- **[#134 More advanced examples](https://github.com/mathLab/PyGeM/issues/134)** → <span class="label label-enhancement">enhancement</span>  
  Requests additional examples and better learning material. This enhances user documentation.  

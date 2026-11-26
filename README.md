<div align="center">

# Maksim Trushin

**Vibe coder · Python developer · data analyst · DICOM & radiotherapy TPS tooling · author of uncompressMRI**

I build small, dependable tools that make DICOM behave — so Eclipse, Aria and Monaco
can import what the scanner actually wrote. A bit of DevOps when the build breaks.

[![uncompressMRI](https://img.shields.io/github/v/release/loonies321/uncompressMRI?style=flat-square&label=uncompressMRI&color=2f6f9f)](https://github.com/loonies321/uncompressMRI)
[![Downloads](https://img.shields.io/github/downloads/loonies321/uncompressMRI/total?style=flat-square&color=2f6f9f)](https://github.com/loonies321/uncompressMRI/releases)
[![Stars](https://img.shields.io/github/stars/loonies321/uncompressMRI?style=flat-square&color=2f6f9f)](https://github.com/loonies321/uncompressMRI/stargazers)

</div>

---

## Featured project

### [uncompressMRI](https://github.com/loonies321/uncompressMRI)

Enhanced multi-frame MRI → single-frame DICOM slices for Eclipse / Aria / Monaco.
Windows `.exe`, CLI and GUI; no Python required.

<a href="https://github.com/loonies321/uncompressMRI">
  <img src="https://raw.githubusercontent.com/loonies321/uncompressMRI/main/docs/gui-howto-en.png" width="760" alt="uncompressMRI: five-step GUI walkthrough">
</a>

**The problem.** A scanner writes the whole series as `Enhanced MR Image Storage`,
but a treatment planning system expects one `MR Image Storage` file per slice.
uncompressMRI keeps each frame's geometry, regenerates Study and FrameOfReference
UIDs deterministically, repairs truncated Siemens pixel data, and previews slices
without loading a 1 GB source file.

[Source](https://github.com/loonies321/uncompressMRI) ·
[Download](https://github.com/loonies321/uncompressMRI/releases/latest) ·
[Docs](https://github.com/loonies321/uncompressMRI#readme)

## What I care about

- **Geometry over averages.** Slice position, orientation, spacing and order must
  survive conversion — otherwise the plan is wrong.
- **Offline by default.** Clinical files stay local: no upload, no telemetry, no
  update pings.
- **Small tools.** A ~25 MB exe that runs without a Visual C++ runtime beats a stack
  of frameworks.
- **Boring reliability.** Tests, deterministic UIDs, clear errors, reproducible builds.

## Toolbox

![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=flat-square&logo=python&logoColor=white)
![pydicom](https://img.shields.io/badge/pydicom-2.3%2B-2f6f9f?style=flat-square)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-stdlib-FFD43B?style=flat-square)
![PyInstaller](https://img.shields.io/badge/PyInstaller-Windows-2f6f9f?style=flat-square)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![DICOM](https://img.shields.io/badge/DICOM-medical%20imaging-005A9C?style=flat-square)
![Apache 2.0](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

## Currently

- Improving **uncompressMRI**: faster slice preview, UID handling, Windows packaging.
- Exploring **contour QA and auto-segmentation** for radiotherapy research.
- Open to collaboration on DICOM/TPS integration and clinical data pipelines.

<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=loonies321&show_icons=true&theme=transparent&hide_border=true&include_all_commits=true&count_private=false" alt="GitHub stats">
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=loonies321&layout=compact&theme=transparent&hide_border=true&langs_count=6" alt="Top languages">
</p>

## Contact

- Issues and ideas: [uncompressMRI issues](https://github.com/loonies321/uncompressMRI/issues)
- Security: [private advisory](https://github.com/loonies321/uncompressMRI/security/advisories/new)
- Open to collaboration on DICOM, radiotherapy TPS integration and contour QA.

<div align="center"><sub>🇷🇺 Вайбкодер, Python-разработчик и аналитик данных. DICOM, лучевая терапия, Eclipse / Aria / Monaco.</sub></div>

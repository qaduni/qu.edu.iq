# qu.edu.iq — Al-Qadisiyah University

[![Hugo](https://img.shields.io/badge/Hugo-Extended-blue?logo=hugo)](https://gohugo.io/)
[![License](https://img.shields.io/github/license/qaduni/qu.edu.iq)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/qaduni/qu.edu.iq)](https://github.com/qaduni/qu.edu.iq/commits/main)
[![Deploy](https://github.com/qaduni/qu.edu.iq/actions/workflows/deploy.yml/badge.svg)](https://github.com/qaduni/qu.edu.iq/actions/workflows/deploy.yml)

Bilingual (Arabic + English) Hugo website for the Al-Qadisiyah University.


Content is managed through **Sveltia CMS** (Git-backed CMS that commits directly to this repository), and site search is powered by **Pagefind**.

## Technology Stack

* **Hugo Extended** — Content lives in `content/{ar,en}/`, configuration in `config/_default/`.
* **Pagefind (≥ 1.5)** — Client-side search with separate search bundles for News and Announcements.
* **Sveltia CMS** — Available by default in the theme.
* **qu.theme** — Hugo theme included as a Git submodule in `themes/qu.theme/`.

# Setup Checklist

Checklist untuk memastikan lingkungan pengembangan Project Titan1000 sudah siap.

---

## Git

- [x] Git terinstal
- [x] GitHub account sudah dikonfigurasi
- [x] SSH Key berhasil dibuat
- [x] SSH Key berhasil ditambahkan ke GitHub
- [x] Repository lokal berhasil dibuat
- [x] Repository berhasil di-push ke GitHub

---

## Visual Studio Code

- [x] VS Code terinstal
- [x] Git Extension aktif
- [x] Python Extension
- [x] Docker Extension
- [x] SQLTools
- [x] Prettier
- [x] ESLint

---

## Workspace

- [x] README.md dibuat
- [x] .gitignore dibuat
- [x] Folder Portfolio
- [x] Folder SQL
- [x] Folder Dashboard
- [x] Folder Python
- [x] Folder AI
- [x] Folder Business

---

## Tools

- [x] Docker Desktop
- [x] Obsidian
- [x] Notion
- [x] Google Chrome
- [ ] Power BI

---

## Verifikasi Git

Jalankan perintah berikut untuk memastikan semuanya bekerja:

```bash
git status
git branch -vv
git remote -v
ssh -T git@github.com
```

Target:

- Working tree clean
- Branch sinkron dengan origin/main
- SSH berhasil terhubung ke GitHub
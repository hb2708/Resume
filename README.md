# Harshal Bhavsar's Resume

This repository contains the LaTeX source code for my resume.

## 📄 Download Latest Version
Building of the resume is automated using GitHub Actions.
You can download the latest PDF versions from the [Releases Page](https://github.com/hb2708/Resume/releases).

There are two versions available:
- **Harshal_Resume_RPT.pdf**: Global version (Kuala Lumpur, Malaysia address).
- **Harshal_Resume_India.pdf**: India version (Pune, India address).

## 🛠 Build It Yourself

### Requirements
- Docker

### command
```bash
docker run --rm -v $(pwd):/workdir -w /workdir texlive/texlive:latest make
```

## ℹ️ Credits
This resume is based on the [Awesome-CV](https://github.com/posquit0/Awesome-CV) template by [posquit0](https://github.com/posquit0).

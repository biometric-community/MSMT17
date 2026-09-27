# MSMT17

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FMSMT17-181717?logo=github)](https://github.com/biometric-community/MSMT17)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://www.pkuvmc.com/)

**MSMT17** — tbiom catalog packaging for `msmt17` (reid; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/MSMT17
- **Upstream source**: https://www.pkuvmc.com/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `msmt17` |
| Category | `reid` |
| Access | `register` |
| Upstream homepage | https://www.pkuvmc.com/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Multi-Scene Multi-Time person re-ID; request from PKU VMC.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/MSMT17.git
cd MSMT17
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_msmt17.sh
```

Place licensed archives under `projects/datasets/msmt17/` (gitignored).

## Dataset structure

```text
MSMT17/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://www.pkuvmc.com/
- Packaging: https://github.com/biometric-community/MSMT17/issues

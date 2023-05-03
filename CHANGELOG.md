# Change Log

## [1.0.4] 2023-05-03
### Changes

- Bump UI: Material Kit2 PRO `v3.0.3`

## [1.0.3] 2023-02-08
### Changes

- Deployment-ready for Render (CI/CD)
  - `render.yaml`
  - `build.sh`
- `DB Management` Improvement
  - `Silent fallback` to **SQLite**
- `DOCS Update` (readme)  

## [1.0.2] 2022-06-12
### Improvements

- Built with [Material Kit Generator PRO](https://appseed.us/generator/material-kit2-pro/)
  - Timestamp: `2022-06-12 11:24`

## [1.0.1] 2022-04-01
### Fixes

- **Patch ImportError**: [cannot import name 'safe_str_cmp' from 'werkzeug.security'](https://docs.appseed.us/content/how-to-fix/importerror-cannot-import-name-safe_str_cmp-from-werkzeug.security)
  - `Werkzeug` deprecation of `safe_str_cmp` starting with version `2.1.0`
    - https://github.com/pallets/werkzeug/issues/2359

## [1.0.0] 2020-12-11
### Initial Release

- UI Version: `Material Kit 2 PRO` **v3.0.0**
- Codebase: [Flask Boilerplate](https://github.com/app-generator/boilerplate-code-flask) v1.0.7

# Self-Bucket [![Build status](https://ci.appveyor.com/api/projects/status/uiry9brxin86drpi/branch/main?svg=true)](https://ci.appveyor.com/project/JaimeZeng/self-bucket/branch/main) [![Excavator](https://github.com/JaimeZeng/self-bucket/actions/workflows/schedule.yml/badge.svg)](https://github.com/JaimeZeng/self-bucket/actions/workflows/schedule.yml)

## Installation / 安装

```powershell
scoop bucket add self https://github.com/JaimeZeng/self-bucket
scoop update
```

## Manifests / 应用

All manifests can be listed with:

```powershell
scoop install scoop-completion
scoop install scoop-search
scoop-search self/<app_name>
```

Install apps from this bucket with:

```powershell
scoop install self/<app_name>
```

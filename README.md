# scoop-bucket

统一的 Scoop Bucket 仓库，用于分发 `hooziwang` 旗下多个命令行工具。

## 已收录 Manifest

- `syl-md2ppt`
- `muna-image-google`
- `muna-video-google`

## 安装

```powershell
scoop bucket add hooziwang https://github.com/hooziwang/scoop-bucket
scoop install syl-md2ppt
scoop install muna-image-google
scoop install muna-video-google
```

## 维护说明

- Manifest 由各项目仓库的 Release 工作流（GoReleaser）自动更新。
- 常规不手动改版本号与 `hash`，以源项目发版结果为准。

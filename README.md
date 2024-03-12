# Visit https://github.com/lowlighter/metrics#-documentation for full reference
name: Metrics
on:
  # Schedule updates (each hour)
  schedule: [{cron: "0 * * * *"}]
  # Lines below let you run workflow manually and on each commit
  workflow_dispatch:
  push: {branches: ["master", "main"]}
jobs:
  github-metrics:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: lowlighter/metrics@latest
        with:
          # Your GitHub token
          # The following scopes are required:
          #  - public_access (default scope)
          # The following additional scopes may be required:
          #  - read:org      (for organization related metrics)
          #  - read:user     (for user related data)
          #  - read:packages (for some packages related data)
          #  - repo          (optional, if you want to include private repositories)
          token: ${{ secrets.METRICS_TOKEN }}

          # Options
          user: jiawei666
          template: terminal
          base: header, activity, community, repositories, metadata
          config_timezone: Asia/Shanghai

<img src="https://i.loli.net/2020/12/17/RQUBWsvJmx4AhGb.gif" title="山猪" alt="山猪" align="right" style="height:100px;widti:100px">
<img src="https://i.loli.net/2020/12/17/xWpfMuiqKLbTkJS.gif" title="善逸" alt="善逸"  align="right" style="height:100px;widti:100px">
<img src="https://i.loli.net/2020/12/17/KCbR5QEWqSuTtc3.gif" title="妹妹" alt="妹妹" align="right" style="height:100px;widti:100px">
<img src="https://i.loli.net/2020/12/17/4xR9G1YlqE5Ibym.gif" title="哥哥" alt="哥哥" align="right" style="height:100px;widti:100px">

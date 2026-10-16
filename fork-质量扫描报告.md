# Fork 质量扫描报告

> 生成时间：2026-10-16 02:52（北京时间）  |  扫描范围：Hua2026-ai 名下 65 个 fork 的**上游仓库**  |  判定依据：最近 commit 日期 / 归档禁用状态 / 许可证

## 一、建议取消 / 考虑取消（核心结论）

判定为「建议取消」的多为重停滞、低价值或无源码的项目；「考虑取消」为曾高星但已长期停滞、现在可用性存疑。

| Fork 仓库            | 上游                   | 分类            | 星标     | 最近提交   | 许可证  | 原因                |
| ------------------ | -------------------- | ------------- | ------ | ------ | ---- | ----------------- |
| net-test-kit       | feiyuaq/net-test-kit | 网络工具 / 代理客户端  | 17     | 41天前   | 无许可证 | 闭源(仅发二进制,无源码可复用)  |
| Ghosttrack-scanner | NexNoir/Ghosttrack   | 安全 / OSINT 工具 | 11     | 473天前  | 无许可证 | 停滞473天+低星(11)     |
| GhostTrack         | HunxByts/GhostTrack  | 安全 / OSINT 工具 | 18,980 | 1008天前 | 无许可证 | 停滞1008天(高星但长期未更新) |

## 二、内容/列表型但停滞（按需保留，不建议取消）

这类是文档、菜谱、资料索引、导航合集。更新慢是常态，内容不因时间失效；除非你不再需要这份资料，否则不必因「停滞」取消。

| Fork 仓库              | 上游                           | 分类        | 星标     | 最近提交  | 许可证       | 原因               |
| -------------------- | ---------------------------- | --------- | ------ | ----- | --------- | ---------------- |
| HowToLiveLonger      | geekan/HowToLiveLonger       | 学习 / 资源索引 | 35,783 | 514天前 | Unlicense | 内容型，停滞514天但资料不过期 |
| reverse-interview-zh | perkfly/reverse-interview-zh | 学习 / 资源索引 | 18,527 | 955天前 | 自定义许可证    | 内容型，停滞955天但资料不过期 |

## 三、观察名单（半年内未更新，暂保留）

活跃度中等，未到停滞线，但半年无提交。若后续超过 1 年未动再评估取消。

| Fork 仓库       | 上游                      | 分类        | 星标     | 最近提交  | 许可证      | 原因      |
| ------------- | ----------------------- | --------- | ------ | ----- | -------- | ------- |
| cobalt        | imputnet/cobalt         | 影音 / 下载   | 45,014 | 192天前 | AGPL-3.0 | 192天未更新 |
| ChinaTextbook | TapXWorld/ChinaTextbook | 学习 / 资源索引 | 82,906 | 362天前 | 无许可证     | 362天未更新 |

## 四、合规提示：无明确标准许可证的活跃项目（二次开发前需确认）

以下项目本身活跃、不建议取消，但**没有宽松的标准开源许可证**（NONE=未发现许可证文件，默认保留所有权利；NOASSERTION=有自定义/非标准许可证）。若你打算 fork 后改代码或再分发，务必先确认授权，否则只能参考思路、不能直接复用代码。

| Fork 仓库                          | 上游                                              | 星标      | 最近提交   | 许可证    | 判定   |
| -------------------------------- | ----------------------------------------------- | ------- | ------ | ------ | ---- |
| up                               | byoungd/up                                      | 68,755  | 3天前    | 自定义许可证 | 保留   |
| playgta5                         | shadany7824/playgta5                            | 1,636   | 3天前    | 无许可证   | 保留   |
| nvidia-macos-driver              | nullmoth/nvidia-macos-driver                    | 3,157   | 0天前    | 自定义许可证 | 保留   |
| muse-skills                      | jasonbitsmith/muse-skills                       | 277     | 9天前    | 无许可证   | 保留   |
| huobao-drama                     | chatfire-AI/huobao-drama                        | 16,285  | 10天前   | 自定义许可证 | 保留   |
| hypit                            | hypit-ai/hypit                                  | 22,563  | 1天前    | 自定义许可证 | 保留   |
| Open-Source-Face-Recognition-SDK | Faceplugin-ltd/Open-Source-Face-Recognition-SDK | 2,594   | 13天前   | 无许可证   | 保留   |
| Wan2GP                           | deepbeepmeep/Wan2GP                             | 10,547  | 0天前    | 自定义许可证 | 保留   |
| hideck                           | yibaiba/hideck                                  | 271     | 0天前    | 自定义许可证 | 保留   |
| jianying-headless                | mcncarl/jianying-headless                       | 3,090   | 0天前    | 自定义许可证 | 保留   |
| clash                            | clashbk/clash                                   | 9,777   | 11天前   | 无许可证   | 保留   |
| TelegramGroup                    | itgoyo/TelegramGroup                            | 5,897   | 7天前    | 无许可证   | 保留   |
| MacCheck                         | andyhuo520/MacCheck                             | 707     | 92天前   | 无许可证   | 保留   |
| HelloGitHub                      | 521xueweihan/HelloGitHub                        | 182,361 | 18天前   | 无许可证   | 保留   |
| ChinaTextbook                    | TapXWorld/ChinaTextbook                         | 82,906  | 362天前  | 无许可证   | 观察   |
| reverse-interview-zh             | perkfly/reverse-interview-zh                    | 18,527  | 955天前  | 自定义许可证 | 按需保留 |
| GhostTrack                       | HunxByts/GhostTrack                             | 18,980  | 1008天前 | 无许可证   | 考虑取消 |
| better-douyin                    | anYuJia/better-douyin                           | 874     | 6天前    | 自定义许可证 | 保留   |

## 五、其余：活跃且健康（保留）

共 **58** 个仓库最近 180 天内有提交，许可证清晰或自定义但活跃，建议保留。包括：  
awesome、rea、HelloGitHub、HowToCook、claude-mem、Agent-Reach、VoiceStudio、up、OpenMontage、HowToLiveBetter、Win11Debloat、everyone-can-use-english、ai-website-cloner-template、freellmapi、knowledge-work-plugins、hypit、moli、lingbot-map、vibe-coding-cn、huobao-drama、patent-disclosure-skill、DiPlay、Wan2GP、clash、mobile-mcp、Octop、rectg、kimi-k3-in-c、goutoujunshi、CyberStrikeAI、qingjian、TelegramGroup、SenseNova-Skills、iPhone-use、Easel、chinese-poetry-api、OpenNOW、nvidia-macos-driver、jianying-headless、bloodborne_pc、UFI-TOOLS、Open-Source-Face-Recognition-SDK、12306-mcp、floorplan-3d、dsh-im、videdown、playgta5、better-douyin、MacCheck、DiPlay-Legacy-Android、lipflow、Atria-Dawn-Preview、android-airplay-server、Microsoft-Rewards-Script、ProsperoStore、playport、muse-skills、hideck。

## 判定规则说明

- **已归档/禁用**：上游已停止或下架，直接建议取消。
- **停滞（>365 天无 commit）**：软件/工具类若同时低星(<500)或无源码 → 建议取消；高星工具类 → 考虑取消（现在能否跑起来存疑）；内容/列表型 → 按需保留。
- **观察（180–365 天）**：暂保留，超 1 年再评估。
- **保留（<180 天）**：活跃，正常保留。
- **许可证**：NONE=无标准许可证（默认保留所有权利，不能直接复用代码）；NOASSERTION=自定义/非标准许可证，需看仓库内 LICENSE 文件原文。
- 注：fork 本身不 sync，故评估以**上游原仓库**状态为准；你的 fork 仅作镜像/备份。

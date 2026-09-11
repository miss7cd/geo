url: http://www.xinzhizi.com/
fetched_at: 2026-08-25 17:54 (GMT+8)
http_status: HTTP 502（首页，重试仍 502）；HTTPS https://www.xinzhizi.com/ 连接失败（curl exit 35，HTTP 000）
title: （页面未返回，无法获取）

# 官网抓取存证说明

本文件用于按 GEO 系统规范存证企业官网抓取结果。抓取时官网不可达，未能取得原始 HTML 内容，因此本文件无可摘录的正文。

抓取尝试记录：
- 首页 HTTP：返回 502 Bad Gateway（含 --retry 2 重试仍 502）
- 首页 HTTPS：TLS/连接失败（curl exit 35，HTTP 000，WebFetch 亦 fetch failed）
- 结论：官网在抓取时点（2026-08-25 17:54 GMT+8）对本环境不可达。

处理原则（遵循 expert 规范「文档优先、官网为补充」）：
- 企业事实一律以用户提供的 source/ 文档为准（文档已包含企业名称、地址、电话、官网域名、产品矩阵、客户案例等可验证信息）。
- 若后续官网恢复可达，应重新抓取首页及产品/关于/联系/资质等子页，将原始 HTML 以带 url/fetched_at/http_status/title 头的 .md 存入 source/ 作为补充来源。
- 本文件不代表任何虚构内容，仅记录抓取状态。

# SERP 最终意图审计（2026-10-25）

本文件、serp.json.final_decisions、报告与离线网页使用同一最终判定表。原始文件存于证据包。

量源：[PXAny](https://api.pxany.com/v1/keyword-volumes)；排名：[PXAny SERP](https://api.pxany.com/v1/serp)；接口需授权。数据来自本批已取得快照，不声称本次成功重查。

零值保留供应商快照状态，但脚本把null转0，原始metrics未保留，391条不能当独立确认的真实零。

| 市场/语言 | 词数 | 正数/供应商记0/未返回/未查询 | 核心SERP组数（返回条数） | 最终判断 |
|---|---:|---|---|---|
| US/en | 55 | 0/53/2/0 | 11（0条×1组、8条×4组、9条×6组） | 仅作英欧出口者表达参考；不可视为美国本土CLP需求 |
| UK/en | 55 | 0/53/2/0 | 11（9条×8组、10条×3组） | 主验证市场；有对口工具；3组跑偏，暂不优先SEO |
| CA/en | 55 | 0/53/2/0 | 11（7条×1组、8条×5组、9条×5组） | 仅出口参考；1组跑偏；不可作加拿大本土需求 |
| AU/en | 55 | 0/53/2/0 | 11（8条×5组、9条×6组） | 仅出口参考；2组跑偏；不可作澳洲本土需求 |
| DE/de | 40 | 0/2/38/0 | 2（5条×1组、10条×1组） | 主市场；量大量未返回，1组跑偏；需补查 |
| FR/fr | 40 | 1/36/3/0 | 1（8条×1组） | 主市场；唯一90是打印混合意图，未计主量；需补查 |
| ES/es | 40 | 0/38/2/0 | 1（10条×1组） | 主市场；免费目录与模板混排；未证实SEO获客规模 |
| IT/it | 40 | 0/38/2/0 | 1（8条×1组） | 主市场；模板/目录混排，样本8条；未证实规模 |
| NL/nl | 40 | 0/39/1/0 | 1（10条×1组） | 主市场；课程/模板/供应商混排；未证实规模 |
| JP/ja | 30 | 0/0/30/0 | 1（9条×1组） | 仅出口参考；月搜全未返回，不能视为0 |
| KR/ko | 30 | 0/26/4/0 | 1（9条×1组） | 仅出口参考；工具/印刷/平台混排，未证实规模 |

## 逐词最终判定

| 市场 | 词 | 月搜 | 状态 | 意图 | 最终判定 |
|---|---|---|---|---|---|
| US | candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| US | CLP label maker for candles | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论 |
| US | candle CLP label software | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论 |
| US | scented candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未取得结果；不可作竞争判断；无SEO优先立项结论 |
| US | UK candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| US | EU candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| US | candle CLP label calculator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| US | SDS to candle CLP label | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论 |
| US | CLP labels for blended fragrance candles | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论 |
| US | printable candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| US | CLP label template for candles | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条 |
| US | free candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | online candle CLP label maker | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle CLP label design tool | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle CLP label builder | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle CLP label editor | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | make CLP labels for candles | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | create CLP labels for scented candles | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | custom candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | handmade candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | artisan candle CLP label maker | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | soy candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | essential oil candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle hazard label generator UK | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle hazard label generator EU | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle CLP label PDF generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | downloadable candle CLP label template | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| US | editable candle CLP label template | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| US | round candle CLP label template | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| US | rectangular candle CLP label template | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| US | candle CLP label PNG download | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle CLP labels from safety data sheet | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle CLP labels from fragrance SDS | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | upload SDS candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle CLP label from recipe | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle CLP label fragrance percentage calculator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | custom fragrance load candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle CLP labels for mixed fragrance oils | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle CLP label calculator multiple oils | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | 8% fragrance candle CLP label | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | 10% fragrance candle CLP label | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | multilingual candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle CLP labels in French | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle CLP labels in German | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | GB CLP candle label maker | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | Northern Ireland candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | Etsy candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | small business candle CLP label software | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle CLP label with company details | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle CLP label with UFI | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle CLP label H and P statements | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle EUH208 label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle allergen CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | candle CLP label with hazard pictograms | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| US | batch generate candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 明显跑偏；样本9条；剔除竞争判断；无SEO优先立项结论 |
| UK | CLP label maker for candles | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| UK | candle CLP label software | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本10条；无SEO优先立项结论 |
| UK | scented candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| UK | UK candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 明显跑偏；样本9条；剔除竞争判断；无SEO优先立项结论 |
| UK | EU candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| UK | candle CLP label calculator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| UK | SDS to candle CLP label | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本10条；无SEO优先立项结论 |
| UK | CLP labels for blended fragrance candles | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 明显跑偏；样本9条；剔除竞争判断；无SEO优先立项结论 |
| UK | printable candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本10条；无SEO优先立项结论 |
| UK | CLP label template for candles | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条 |
| UK | free candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | online candle CLP label maker | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle CLP label design tool | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle CLP label builder | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle CLP label editor | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | make CLP labels for candles | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | create CLP labels for scented candles | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | custom candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | handmade candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | artisan candle CLP label maker | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | soy candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | essential oil candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle hazard label generator UK | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle hazard label generator EU | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle CLP label PDF generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | downloadable candle CLP label template | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| UK | editable candle CLP label template | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| UK | round candle CLP label template | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| UK | rectangular candle CLP label template | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| UK | candle CLP label PNG download | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle CLP labels from safety data sheet | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle CLP labels from fragrance SDS | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | upload SDS candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle CLP label from recipe | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle CLP label fragrance percentage calculator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | custom fragrance load candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle CLP labels for mixed fragrance oils | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle CLP label calculator multiple oils | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | 8% fragrance candle CLP label | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | 10% fragrance candle CLP label | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | multilingual candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle CLP labels in French | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle CLP labels in German | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | GB CLP candle label maker | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | Northern Ireland candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | Etsy candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | small business candle CLP label software | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle CLP label with company details | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle CLP label with UFI | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle CLP label H and P statements | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle EUH208 label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle allergen CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | candle CLP label with hazard pictograms | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| UK | batch generate candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 明显跑偏；样本9条；剔除竞争判断；无SEO优先立项结论 |
| CA | CLP label maker for candles | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本7条，不足10条；无SEO优先立项结论 |
| CA | candle CLP label software | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论 |
| CA | scented candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论 |
| CA | UK candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论 |
| CA | EU candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| CA | candle CLP label calculator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| CA | SDS to candle CLP label | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论 |
| CA | CLP labels for blended fragrance candles | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论 |
| CA | printable candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| CA | CLP label template for candles | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条 |
| CA | free candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | online candle CLP label maker | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle CLP label design tool | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle CLP label builder | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle CLP label editor | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | make CLP labels for candles | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | create CLP labels for scented candles | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | custom candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | handmade candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | artisan candle CLP label maker | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | soy candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | essential oil candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle hazard label generator UK | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle hazard label generator EU | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle CLP label PDF generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | downloadable candle CLP label template | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| CA | editable candle CLP label template | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| CA | round candle CLP label template | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| CA | rectangular candle CLP label template | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| CA | candle CLP label PNG download | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle CLP labels from safety data sheet | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle CLP labels from fragrance SDS | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | upload SDS candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle CLP label from recipe | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle CLP label fragrance percentage calculator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | custom fragrance load candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle CLP labels for mixed fragrance oils | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle CLP label calculator multiple oils | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | 8% fragrance candle CLP label | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | 10% fragrance candle CLP label | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | multilingual candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle CLP labels in French | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle CLP labels in German | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | GB CLP candle label maker | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | Northern Ireland candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | Etsy candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | small business candle CLP label software | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle CLP label with company details | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle CLP label with UFI | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle CLP label H and P statements | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle EUH208 label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle allergen CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | candle CLP label with hazard pictograms | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| CA | batch generate candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| AU | CLP label maker for candles | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 明显跑偏；样本9条；剔除竞争判断；无SEO优先立项结论 |
| AU | candle CLP label software | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| AU | scented candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论 |
| AU | UK candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 明显跑偏；样本9条；剔除竞争判断；无SEO优先立项结论 |
| AU | EU candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| AU | candle CLP label calculator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论 |
| AU | SDS to candle CLP label | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论 |
| AU | CLP labels for blended fragrance candles | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论 |
| AU | printable candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| AU | CLP label template for candles | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条 |
| AU | free candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | online candle CLP label maker | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle CLP label design tool | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle CLP label builder | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle CLP label editor | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | make CLP labels for candles | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | create CLP labels for scented candles | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | custom candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | handmade candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | artisan candle CLP label maker | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | soy candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | essential oil candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle hazard label generator UK | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle hazard label generator EU | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle CLP label PDF generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | downloadable candle CLP label template | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| AU | editable candle CLP label template | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| AU | round candle CLP label template | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| AU | rectangular candle CLP label template | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| AU | candle CLP label PNG download | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle CLP labels from safety data sheet | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle CLP labels from fragrance SDS | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | upload SDS candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle CLP label from recipe | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle CLP label fragrance percentage calculator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | custom fragrance load candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle CLP labels for mixed fragrance oils | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle CLP label calculator multiple oils | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | 8% fragrance candle CLP label | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | 10% fragrance candle CLP label | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | multilingual candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle CLP labels in French | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle CLP labels in German | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | GB CLP candle label maker | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | Northern Ireland candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | Etsy candle CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | small business candle CLP label software | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle CLP label with company details | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle CLP label with UFI | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle CLP label H and P statements | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle EUH208 label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle allergen CLP label generator | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | candle CLP label with hazard pictograms | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| AU | batch generate candle CLP labels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten für Kerzen erstellen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本5条，不足10条；无SEO优先立项结论 |
| DE | CLP-Etiketten Generator Duftkerzen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 明显跑偏；样本10条；剔除竞争判断；无SEO优先立项结论 |
| DE | CLP-Etiketten Software für Kerzen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten für Kerzen online erstellen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten für Kerzen kostenlos erstellen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten Vorlage Kerzen | 未返回 | 未返回 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| DE | CLP-Etiketten Vorlage Duftkerzen | 未返回 | 未返回 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| DE | CLP-Etiketten für Kerzen zum Ausdrucken | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten für Kerzen als PDF | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten für handgemachte Kerzen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten für Sojawachskerzen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten für Kerzen mit ätherischen Ölen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | Gefahrenetiketten für Duftkerzen erstellen | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | Warnetiketten für Kerzen nach CLP erstellen | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten Rechner Kerzen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etikett aus Sicherheitsdatenblatt Kerze | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etikett aus Duftöl-Sicherheitsdatenblatt | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | Kerzen CLP-Etikett nach Rezeptur | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten Kerzen Duftölanteil berechnen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten für Kerzen mit Duftmischungen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etikett Kerze mehrere Duftöle | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etikett Kerze 10 Prozent Duftöl | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etikett Kerze 8 Prozent Duftöl | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | mehrsprachige CLP-Etiketten für Kerzen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten für Kerzen auf Englisch | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten für Kerzen auf Französisch | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten für Kerzen EU | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten für Kerzen Großbritannien | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten für Kerzen Export | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten für Etsy-Kerzen erstellen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | runde CLP-Etiketten für Kerzen erstellen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | rechteckige CLP-Etiketten für Kerzen erstellen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten für Kerzen bearbeiten | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten für Kerzen herunterladen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten Kerzen eigene Firmendaten | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten Kerzen mit UFI-Code | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten Kerzen mit Gefahrenpiktogrammen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten Kerzen H- und P-Sätze | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten Kerzen EUH208 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| DE | CLP-Etiketten für mehrere Kerzensorten erstellen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | générateur étiquettes CLP bougies | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论 |
| FR | logiciel étiquettes CLP bougies | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | créer étiquette CLP bougie | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | outil étiquette CLP bougie parfumée | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | générateur étiquette CLP bougie gratuit | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie en ligne | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | modèle étiquette CLP bougie | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| FR | modèle étiquette CLP bougie modifiable | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| FR | étiquette CLP bougie à imprimer | 90 | 返回正数 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie PDF | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie à télécharger | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie artisanale | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie cire de soja | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie huiles essentielles | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | calculateur étiquette CLP bougie | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie à partir de la FDS | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | générateur étiquette CLP bougie import FDS | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie selon recette | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie selon dosage parfum | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie mélange de parfums | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie plusieurs parfums | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie parfum à 10 % | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie parfum à 8 % | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette de danger CLP bougie personnalisée | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie multilingue | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie en anglais | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie en allemand | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie vente en Europe | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie export Royaume-Uni | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie vente sur Etsy | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie ronde | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie rectangulaire | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | personnaliser étiquette CLP bougie | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie coordonnées entreprise | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie avec code UFI | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie pictogrammes de danger | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie mentions H et P | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie allergènes | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | étiquette CLP bougie EUH208 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| FR | créer plusieurs étiquettes CLP bougies | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | generador etiquetas CLP velas | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本10条；无SEO优先立项结论 |
| ES | crear etiquetas CLP para velas | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | programa etiquetas CLP velas | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | herramienta etiquetas CLP velas aromáticas | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | generador etiquetas CLP velas gratis | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiquetas CLP velas en línea | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | plantilla etiqueta CLP vela | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| ES | plantilla editable etiqueta CLP velas | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| ES | etiquetas CLP velas para imprimir | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiquetas CLP velas PDF | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | descargar etiqueta CLP vela | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiquetas CLP velas artesanales | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiquetas CLP velas de soja | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiquetas CLP velas con aceites esenciales | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | calculadora etiquetas CLP velas | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiqueta CLP vela desde ficha de seguridad | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiqueta CLP vela a partir de FDS | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | generador etiqueta CLP vela cargar SDS | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiqueta CLP vela según fórmula | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiqueta CLP vela según porcentaje de fragancia | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiqueta CLP vela mezcla de fragancias | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiqueta CLP vela varios aceites aromáticos | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiqueta CLP vela fragancia al 10 % | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiqueta CLP vela fragancia al 8 % | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | generador etiquetas de peligro CLP velas | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiquetas CLP velas multilingües | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiquetas CLP velas en inglés | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiquetas CLP velas en francés | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiquetas CLP velas Unión Europea | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiquetas CLP velas exportar a Reino Unido | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiquetas CLP velas para vender en Etsy | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiqueta CLP vela redonda | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiqueta CLP vela rectangular | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | personalizar etiqueta CLP vela | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiqueta CLP vela datos del fabricante | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiqueta CLP vela con código UFI | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiqueta CLP vela pictogramas de peligro | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiqueta CLP vela frases H y P | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiqueta CLP vela alérgenos | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| ES | etiqueta CLP vela EUH208 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | generatore etichette CLP candele | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论 |
| IT | creare etichette CLP candele | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | programma etichette CLP candele | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | strumento etichette CLP candele profumate | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | generatore etichette CLP candele gratis | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichette CLP candele online | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | modello etichetta CLP candela | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| IT | modello etichetta CLP candela modificabile | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| IT | etichette CLP candele da stampare | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichette CLP candele PDF | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | scaricare etichette CLP candele | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichette CLP candele artigianali | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichette CLP candele di soia | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichette CLP candele con oli essenziali | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | calcolo etichetta CLP candela | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichetta CLP candela da scheda di sicurezza | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichetta CLP candela da SDS | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | generatore etichette CLP candele caricamento SDS | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichetta CLP candela da ricetta | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichetta CLP candela percentuale fragranza | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichetta CLP candela miscela di fragranze | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichetta CLP candela più fragranze | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichetta CLP candela fragranza al 10 % | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichetta CLP candela fragranza all'8 % | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | generatore etichette di pericolo candele CLP | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichette CLP candele multilingue | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichette CLP candele in inglese | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichette CLP candele in tedesco | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichette CLP candele Unione Europea | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichette CLP candele esportazione Regno Unito | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichette CLP candele vendita Etsy | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichetta CLP candela rotonda | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichetta CLP candela rettangolare | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | personalizzare etichetta CLP candela | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichetta CLP candela dati aziendali | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichetta CLP candela con codice UFI | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichetta CLP candela pittogrammi di pericolo | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichetta CLP candela frasi H e P | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichetta CLP candela allergeni | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| IT | etichetta CLP candela EUH208 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiketten maken voor geurkaarsen | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本10条；无SEO优先立项结论 |
| NL | CLP etiketten generator kaarsen | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiketten software kaarsen | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiketten ontwerptool kaarsen | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | gratis CLP etiketten maken kaarsen | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiketten kaarsen online maken | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiket sjabloon kaarsen | 0 | 供应商返回0 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| NL | bewerkbaar CLP etiket kaarsen | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiketten kaarsen zelf printen | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiketten kaarsen PDF | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiketten kaarsen downloaden | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiketten handgemaakte kaarsen | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiketten sojakaarsen | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiketten kaarsen met etherische olie | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiket berekenen kaarsen | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiket kaars uit veiligheidsinformatieblad | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiket kaars uit SDS | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiket kaars SDS uploaden | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiket kaars op basis van recept | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiket kaars percentage geurolie | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiket kaars eigen geurmengsel | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiket kaars meerdere geuroliën | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiket kaars 10 procent geurolie | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiket kaars 8 procent geurolie | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | gevarenetiket kaars CLP maken | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | meertalige CLP etiketten kaarsen | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiketten kaarsen in het Engels | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiketten kaarsen in het Duits | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiketten kaarsen EU | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiketten kaarsen Verenigd Koninkrijk | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiketten kaarsen verkopen op Etsy | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | ronde CLP etiketten kaarsen maken | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | rechthoekige CLP etiketten kaarsen maken | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiketten kaarsen aanpassen | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiket kaars bedrijfsgegevens | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiket kaars UFI invullen | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiket kaars gevarenpictogrammen | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiket kaars H- en P-zinnen | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiket kaars allergenen | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| NL | CLP etiket kaars EUH208 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル CLPラベル 作成ツール | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| JP | キャンドル CLPラベル 自動作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル CLPラベル 作成ソフト | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル CLPラベル オンライン作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル CLPラベル 無料作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル CLPラベル テンプレート | 未返回 | 未返回 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| JP | キャンドル CLPラベル PDF出力 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル CLPラベル 印刷データ作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | 手作りキャンドル CLPラベル 作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | アロマキャンドル CLPラベル 作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | ソイキャンドル CLPラベル 作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | 精油キャンドル CLPラベル 作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | EU輸出 キャンドル CLPラベル作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | 英国輸出 キャンドル CLPラベル作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | 海外販売 キャンドル CLPラベル作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | Etsy キャンドル CLPラベル作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル SDSからCLPラベル作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル 安全データシートからラベル作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル 配合からCLPラベル作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル 香料濃度 CLPラベル計算 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル 香料ブレンド CLPラベル作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル 複数香料 CLPラベル作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル CLPラベル 英語で作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル CLPラベル ドイツ語で作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル CLPラベル 多言語作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル CLPラベル 丸型テンプレート | 未返回 | 未返回 | 排除：只找现成模板/排版 | 相邻模板意图，不计主任务搜索量或竞争分；未查询（外围词未过单市场>200门槛） |
| JP | キャンドル CLPラベル 社名入り作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル CLPラベル UFI入力 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル CLPラベル 絵表示付き作成 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| JP | キャンドル CLPラベル EUH208表示 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 CLP 라벨 생성기 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论 |
| KR | 캔들 CLP 라벨 자동 생성 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 CLP 라벨 제작 프로그램 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 CLP 라벨 온라인 제작 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 CLP 라벨 무료 제작 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 CLP 라벨 양식 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 CLP 라벨 PDF 저장 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 CLP 라벨 인쇄 파일 만들기 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 수제 캔들 CLP 라벨 만들기 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 향초 CLP 라벨 제작 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 소이 캔들 CLP 라벨 제작 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 에센셜 오일 캔들 CLP 라벨 제작 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 유럽 수출 캔들 CLP 라벨 만들기 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 영국 수출 캔들 CLP 라벨 만들기 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 해외 판매 캔들 CLP 라벨 제작 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 엣시 판매 캔들 CLP 라벨 만들기 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 SDS 기반 CLP 라벨 생성 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 물질안전보건자료로 CLP 라벨 만들기 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 배합비 CLP 라벨 생성 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 향료 함량 CLP 라벨 계산 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 블렌딩 향료 캔들 CLP 라벨 제작 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 여러 향료 캔들 CLP 라벨 생성 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 CLP 라벨 영어로 만들기 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 CLP 라벨 독일어로 만들기 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 다국어 CLP 라벨 제작 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 원형 CLP 라벨 양식 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 CLP 라벨 업체 정보 입력 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 CLP 라벨 UFI 입력 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 CLP 라벨 유해성 그림문자 넣기 | 未返回 | 未返回 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |
| KR | 캔들 CLP 라벨 EUH208 문구 | 0 | 供应商返回0 | 保留候选：SDS/浓度到标签；信息或印刷意图仍须页面确认 | 未查询（外围词未过单市场>200门槛）；无SEO优先立项结论 |

## 补充短词（不冒充已查量或国家前十）

| 市场 | 词 | 月搜状态 | 判定 |
|---|---|---|---|
| UK | CLP label generator | 未查询 | 混合：含其他化学品，不直接计主需求；量未查询，国家SERP未取得；不贡献搜索量或排名竞争判断 |
| UK | candle CLP labels | 未查询 | 混合：信息/实体印刷/软件，不直接计主需求；量未查询，国家SERP未取得；不贡献搜索量或排名竞争判断 |
| UK | CLP labels for candles | 未查询 | 混合：信息/实体印刷/软件，不直接计主需求；量未查询，国家SERP未取得；不贡献搜索量或排名竞争判断 |
| UK | candle CLP generator | 未查询 | 主任务核心词；量未查询，国家SERP未取得；不贡献搜索量或排名竞争判断 |
| UK | SDS CLP label generator candles | 未查询 | 主任务核心词；量未查询，国家SERP未取得；不贡献搜索量或排名竞争判断 |
| UK | CLP label calculator candles | 未查询 | 主任务核心词；量未查询，国家SERP未取得；不贡献搜索量或排名竞争判断 |
| FR | générateur étiquette CLP bougie | 未查询 | 主任务核心词；量未查询，国家SERP未取得；不贡献搜索量或排名竞争判断 |
| DE | CLP Etiketten erstellen Kerzen | 未查询 | 主任务核心词；量未查询，国家SERP未取得；不贡献搜索量或排名竞争判断 |
| NL | CLP etiketten generator kaarsen | 未查询 | 主任务核心词；量未查询，国家SERP未取得；不贡献搜索量或排名竞争判断 |

## 已取得核心词的排名页与域龄观察

### US · candle CLP label generator

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 2 | [pinterest.com](https://www.pinterest.com/pin/free-clp-label-design-template--441352832249199217/) | 2009-11-26 | 97 |
| 3 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 4 | [nextsds.com](https://nextsds.com/tools/clp-widget/) | 2024-12-13 | 28 |
| 5 | [etsy.com](https://www.etsy.com/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
| 6 | [luxurycandlesupplies.co.uk](https://www.luxurycandlesupplies.co.uk/fragrance-oils/clp-label-maker.html) | 2018-05-22 | 35 |
| 7 | [glowclp.co.uk](https://www.glowclp.co.uk/product/clp-labels-for-candles-wax-melts/) | 2021-10-19 | 0 |
| 8 | [stickyprintpixels.co.uk](https://stickyprintpixels.co.uk/collections/clp-labels?srsltid=AYCX9vIh7vnxjytLYn6Uy6dsEbCuemf0noFF6gwn_dpPskhQXy6dX09T) | 2021-03-01 | 0 |
| 9 | [suppliesforcandles.co.uk](https://www.suppliesforcandles.co.uk/clps-getting-your-label-right-first-time/) | 2016-12-16 | 39 |
### US · CLP label maker for candles

含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [optimedialabs.com](https://www.optimedialabs.com/candle-labels/?srsltid=AYCX9vJm_SgsbsVHiipJWNXEfblEk1NgdJVrRWtZ-hYcdSg7E80IR2ZD) | 2005-01-11 | 6 |
| 2 | [facebook.com](https://www.facebook.com/groups/806335036656581/posts/999887767301306/) | 1997-03-29 | 100 |
| 3 | [pinterest.com](https://www.pinterest.com/pin/clp-label-templates-for-candles-and-wax-melts--441352832243105209/) | 2009-11-26 | 97 |
| 4 | [reddit.com](https://www.reddit.com/r/candlemaking/comments/xu2c8x/what_labelerprinter_do_you_use_to_print_your/) | 2005-04-29 | 95 |
| 5 | [nicandlesupplies.com](https://www.nicandlesupplies.com/pages/clp-label-printing?srsltid=AYCX9vJuYZ6A7tqaN1qQAEjs5yGjbTY1R74zD_NoHuOGvzms1cvH-XLN) | 2017-10-28 | 27 |
| 6 | [primera.com](https://www.primera.com/candle-labels/) | 1997-03-06 | 68 |
| 7 | [etsy.com](https://www.etsy.com/listing/926612234/45mm-candle-clp-label-round) | 2004-02-05 | 94 |
| 8 | [reddit.com](https://www.reddit.com/r/candlemaking/comments/1iyurk7/label_maker_for_candles_printer_recommendations/) | 2005-04-29 | 95 |
### US · candle CLP label software

含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 2 | [reddit.com](https://www.reddit.com/r/candlemaking/comments/1s3nqoy/clp_labels_is_anyone_actually_confident_theyre/) | 2005-04-29 | 95 |
| 3 | [etsy.com](https://www.etsy.com/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
| 4 | [facebook.com](https://www.facebook.com/candleshackuk/posts/clp-labels-dont-need-to-be-complicated-our-free-design-tool-helps-you-create-cle/1334931478677304/) | 1997-03-29 | 100 |
| 5 | [nicandlesupplies.com](https://www.nicandlesupplies.com/blogs/news-and-updates/what-you-need-to-know-about-clp-labels-for-candles?srsltid=AYCX9vIiIZPi3y7fG_n-NVYdUGU8nKoMo6AfRM0TgFrC0orT74ICcRk2) | 2017-10-28 | 27 |
| 6 | [nextsds.com](https://nextsds.com/tools/clp-widget/) | 2024-12-13 | 28 |
| 7 | [glowclp.co.uk](https://www.glowclp.co.uk/product-category/digital-downloads/) | 2021-10-19 | 0 |
| 8 | [pinterest.com](https://www.pinterest.com/pin/clp-label-templates-for-candles-and-wax-melts--441352832243105209/) | 2009-11-26 | 97 |
### US · scented candle CLP label generator

未取得结果；不可作竞争判断；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
### US · UK candle CLP label generator

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 2 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 3 | [handylabels.co.uk](https://www.handylabels.co.uk/products/specialised-products/clp-labels.html?srsltid=AYCX9vIuzag-hWL5Iye9UnMph-IHJVa-zlvL9bxllW5Toc9QKn7QnPFc) | 2007-05-04 | 36 |
| 4 | [facebook.com](https://www.facebook.com/candleshackuk/posts/clp-labels-dont-need-to-be-complicated-our-free-design-tool-helps-you-create-cle/1334931478677304/) | 1997-03-29 | 100 |
| 5 | [glowclp.co.uk](https://www.glowclp.co.uk/product/clp-labels-for-candles-wax-melts/) | 2021-10-19 | 0 |
| 6 | [craftcert.co.uk](https://craftcert.co.uk/blog/what-to-look-for-clp-label-generator) | 2026-03-14 | 0 |
| 7 | [etsy.com](https://www.etsy.com/listing/1019772028/editable-candle-warning-labels-clp) | 2004-02-05 | 94 |
| 8 | [luxurycandlesupplies.co.uk](https://www.luxurycandlesupplies.co.uk/fragrance-oils/clp-label-maker.html) | 2018-05-22 | 35 |
| 9 | [pinterest.com](https://www.pinterest.com/pin/free-clp-label-design-template--441352832249199217/) | 2009-11-26 | 97 |
### US · EU candle CLP label generator

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 2 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 3 | [facebook.com](https://www.facebook.com/candleshackuk/posts/clp-labels-dont-need-to-be-complicated-our-free-design-tool-helps-you-create-cle/1334931478677304/) | 1997-03-29 | 100 |
| 4 | [nextsds.com](https://nextsds.com/tools/clp-widget/) | 2024-12-13 | 28 |
| 5 | [youtube.com](https://www.youtube.com/watch?v=4-Xq0TeKdcM) | 2005-02-15 | 99 |
| 6 | [armatagecandlecompany.com](https://armatagecandlecompany.com/blog/eu-candle-label-requirements/) | 2020-02-01 | 29 |
| 7 | [etsy.com](https://www.etsy.com/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
| 8 | [taobe.consulting](https://taobe.consulting/clp-candle-label-regulations/) | 2019-03-22 | 21 |
| 9 | [glowclp.co.uk](https://www.glowclp.co.uk/product/clp-labels-for-candles-wax-melts/) | 2021-10-19 | 0 |
### US · candle CLP label calculator

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/candle-making-tools-services) | 2010-07-22 | 37 |
| 2 | [youtube.com](https://www.youtube.com/watch?v=4-Xq0TeKdcM) | 2005-02-15 | 99 |
| 3 | [suppliesforcandles.co.uk](https://www.suppliesforcandles.co.uk/clps-getting-your-label-right-first-time/) | 2016-12-16 | 39 |
| 4 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 5 | [thesoapkitchen.co.uk](https://www.thesoapkitchen.co.uk/tsk-blog/articles/clp-legislation-explained/) | 2000-06-26 | 46 |
| 6 | [etsy.com](https://www.etsy.com/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
| 7 | [facebook.com](https://www.facebook.com/groups/806335036656581/posts/1079223046034444/) | 1997-03-29 | 100 |
| 8 | [nextsds.com](https://nextsds.com/tools/clp-widget/) | 2024-12-13 | 28 |
| 9 | [reddit.com](https://www.reddit.com/r/candlemaking/comments/oe845a/clp_labels/) | 2005-04-29 | 95 |
### US · SDS to candle CLP label

含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [terre-de-bougies.com](https://www.terre-de-bougies.com/en/blogs/news/bonds-sale-candles-melts?srsltid=AYCX9vLGQUDB9nYiPjyVGYKOS2GpYaZYoDf9ZQRqh26Ay6uzRks_exgD) | 2012-03-09 | 40 |
| 2 | [homefragrance.academy](https://www.homefragrance.academy/blog/top-clp-labelling-mistakes-candle-makers-should-avoid-expert-tips-and-advice) | 2023-06-04 | 1 |
| 3 | [facebook.com](https://www.facebook.com/groups/candlemakingclub/posts/1845433812903169/) | 1997-03-29 | 100 |
| 4 | [yourcrafts.co.uk](https://yourcrafts.co.uk/blogs/candle-soap-making-blog/a-simple-guide-to-candle-clp?srsltid=AYCX9vL14nWbWSs4X9zSd3tInsCht1n0CXkuVCulL8viaEcssJEXWbic) | 2017-08-04 | 2 |
| 5 | [reddit.com](https://www.reddit.com/r/candlemaking/comments/1s3nqoy/clp_labels_is_anyone_actually_confident_theyre/) | 2005-04-29 | 95 |
| 6 | [handylabels.co.uk](https://www.handylabels.co.uk/blog/post/clp-compliance-candles-2026-guide?srsltid=AYCX9vKzOkT1-54sQCdhDMyD4av0MaWNw-EI9XQU781PEsc2FWr7H54W) | 2007-05-04 | 36 |
| 7 | [clp-services.co.uk](https://clp-services.co.uk/products/clp-label-sds-authoring-service-essential-oil-blend) | 2026-04-07 | 0 |
| 8 | [essentialoilblends.co.uk](https://essentialoilblends.co.uk/products/clp?srsltid=AYCX9vJ5hYtfAA7b0nT8N-fiAdFTtSBJiLNvtLtWdvAiJVRmcO3nTp5S) | 2021-01-09 | 0 |
### US · CLP labels for blended fragrance candles

含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [facebook.com](https://www.facebook.com/groups/candlemakingclub/posts/2178029686310245/) | 1997-03-29 | 100 |
| 2 | [glowclp.co.uk](https://www.glowclp.co.uk/product-category/clp-labels/clps-candles/) | 2021-10-19 | 0 |
| 3 | [taobe.consulting](https://taobe.consulting/clp-candle-label-regulations/) | 2019-03-22 | 21 |
| 4 | [nicandlesupplies.com](https://www.nicandlesupplies.com/blogs/news-and-updates/what-you-need-to-know-about-clp-labels-for-candles?srsltid=AYCX9vJMATuFxrJtQGpy7MasB0Wk9_W82PplLsPQS9z6l9TJ9O-PXv0N) | 2017-10-28 | 27 |
| 5 | [terre-de-bougies.com](https://www.terre-de-bougies.com/en/blogs/news/bonds-sale-candles-melts?srsltid=AYCX9vLduZIyMz8AZiTBxD3-VwDWONbaYN82fafVjjZwubHd2V5PtSEJ) | 2012-03-09 | 40 |
| 6 | [yourcrafts.co.uk](https://yourcrafts.co.uk/blogs/candle-soap-making-blog/a-simple-guide-to-candle-clp?srsltid=AYCX9vKVtlCss0zsoOxEkpgDSwJOaMtdO5eujXBvLKmJLdZulouE6tGo) | 2017-08-04 | 2 |
| 7 | [homefragrance.academy](https://www.homefragrance.academy/blog/clp-for-candles-wax-melts) | 2023-06-04 | 1 |
| 8 | [purescented.com](https://purescented.com/labels/?srsltid=AYCX9vITScq9WO-X9rJxEtgms8U1KPFYKGWT_3rwoMRV4wKTvclCint6) | 2016-01-06 | 25 |
### US · printable candle CLP label generator

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [handylabels.co.uk](https://www.handylabels.co.uk/products/specialised-products/clp-labels.html?srsltid=AYCX9vJvM-_DqOvW1TOb6C3aEyZTybgj00-bVS2Ftw4ytOikShR6QEWW) | 2007-05-04 | 36 |
| 2 | [nextsds.com](https://nextsds.com/tools/clp-widget/) | 2024-12-13 | 28 |
| 3 | [pinterest.com](https://www.pinterest.com/ideas/how-to-make-clp-labels-for-candles/922954665750/) | 2009-11-26 | 97 |
| 4 | [pinterest.com](https://www.pinterest.com/pin/clp-templates--141230138304513258/) | 2009-11-26 | 97 |
| 5 | [suppliesforcandles.co.uk](https://www.suppliesforcandles.co.uk/clps-getting-your-label-right-first-time/) | 2016-12-16 | 39 |
| 6 | [betckey.com](https://betckey.com/blogs/news/7-must-have-free-candle-label-template-websites?srsltid=AYCX9vKeZOMB2etcYreS01YDtTNsPKSWiKIikanNZe6juMDVF4aZyVFf) | 2016-03-30 | 53 |
| 7 | [pinterest.com](https://www.pinterest.com/ideas/clp-label-example/926107940527/) | 2009-11-26 | 97 |
| 8 | [etsy.com](https://www.etsy.com/listing/1019813088/candle-warning-label-template-clp) | 2004-02-05 | 94 |
| 9 | [magicclps.co.uk](https://www.magicclps.co.uk/products/clp-printable-pdfs?srsltid=AYCX9vLuy3paipOokQgp36_3PnRMEb337QknfcawMyOvf8h3kUsHOWrd) | 2020-05-24 | 7 |
### US · CLP label template for candles

相邻模板意图，不计主任务搜索量或竞争分；含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 2 | [pinterest.com](https://www.pinterest.com/pin/free-clp-label-design-template--441352832249199217/) | 2009-11-26 | 97 |
| 3 | [etsy.com](https://www.etsy.com/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
| 4 | [nicandlesupplies.com](https://www.nicandlesupplies.com/blogs/news-and-updates/what-you-need-to-know-about-clp-labels-for-candles?srsltid=AYCX9vJ7gSJxiK9DP7X5MkOsas-UI5ZuhS6PhdZkYhx-adHEED46Is4b) | 2017-10-28 | 27 |
| 5 | [handylabels.co.uk](https://www.handylabels.co.uk/products/specialised-products/clp-labels.html?srsltid=AYCX9vIEm-0gzCZwvdzJBzVmWfxa5yH19kfEQtBTvgr8dO7pghtqN4WZ) | 2007-05-04 | 36 |
| 6 | [adobe.com](https://www.adobe.com/express/templates/label/candle) | 1986-11-17 | 96 |
| 7 | [glowclp.co.uk](https://www.glowclp.co.uk/product/clp-labels-for-fragrance-oils-pdf-or-word-digital-download/) | 2021-10-19 | 0 |
| 8 | [betckey.com](https://betckey.com/blogs/news/7-must-have-free-candle-label-template-websites?srsltid=AYCX9vK1Cy6Wuz1D43Mcj_Vf37jkJfIjKqiE2t4YxUyfky1rXURC9QFV) | 2016-03-30 | 53 |
| 9 | [pinterest.com](https://www.pinterest.com/ideas/clp-labels/898018620354/) | 2009-11-26 | 97 |
### UK · candle CLP label generator

明显跑偏；样本9条；剔除竞争判断；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [v-label.com](https://www.v-label.com/) | 2010-06-04 | 71 |
| 2 | [pefc.org](https://pefc.org/for-business/supply-chain-companies/use-the-pefc-label) | 1999-01-18 | 83 |
| 3 | [europa.eu](https://education.ec.europa.eu/education-levels/higher-education/joint-european-degree/joint-european-degree-label) | 未找到 | 97 |
| 4 | [avery.co.uk](https://www.avery.co.uk/blank-labels) | 1997-12-05 | 61 |
| 5 | [label.co.uk](https://label.co.uk/) | 1997-06-10 | 25 |
| 6 | [nih.gov](https://pubmed.ncbi.nlm.nih.gov/38691359/) | 1997-10-02 | 95 |
| 7 | [behindthelabel.co.uk](https://www.behindthelabel.co.uk/) | 2010-10-14 | 29 |
| 8 | [mascotlabelgroup.com](https://www.mascotlabelgroup.com/?srsltid=AYCX9vID2VZi04h_sA4n6o2hk_6KyYjIhPrYjDgdJQOHM4KaB7enYiWH) | 2010-04-13 | 53 |
| 9 | [theslowlabel.com](https://www.theslowlabel.com/?srsltid=AYCX9vJsmc92YuLvjkrnqWDsmOvnEoLIWOl4QKZ3ywBN7LkOF4u6aV7i) | 2019-02-06 | 45 |
### UK · CLP label maker for candles

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [luxurycandlesupplies.co.uk](https://www.luxurycandlesupplies.co.uk/clpprinting-roomspray.html) | 2018-05-22 | 35 |
| 2 | [glowclp.co.uk](https://www.glowclp.co.uk/product-category/clp-labels/digital-files-print-at-home-clp/) | 2021-10-19 | 0 |
| 3 | [trustpilot.com](https://uk.trustpilot.com/review/luxurycandlesupplies.co.uk/product/clp-label-printing-candle-wax-melt-less-10percent-69ea67f187f4ad5fee210230) | 2007-06-30 | 94 |
| 4 | [nicandlesupplies.com](https://www.nicandlesupplies.com/blogs/news-and-updates/what-you-need-to-know-about-clp-labels-for-candles?srsltid=AYCX9vKWpVkMXIwDgER1bKizJyseEcrYHw0Jd9P_v-H80xSFlF1rg7cT) | 2017-10-28 | 27 |
| 5 | [stoneglowcandles.co.uk](https://www.stoneglowcandles.co.uk/clplabelservice?srsltid=AYCX9vK_b6LZzMSFnDkyiifKKiPfFKGbDcfrIWApulGj-o0hu6Zuc2Vn) | 2000-02-17 | 33 |
| 6 | [discountstickerprinting.co.uk](https://www.discountstickerprinting.co.uk/custom-stickers/clp-labels.html?srsltid=AYCX9vJcRYmBuCwgmtb3AjDHug4roL4vlkBHliNizs2m-ind8-2_7W8z) | 2010-10-12 | 36 |
| 7 | [pinterest.com](https://www.pinterest.com/ideas/how-to-make-clp-labels-for-candles/922954665750/) | 2009-11-26 | 97 |
| 8 | [facebook.com](https://www.facebook.com/groups/806335036656581/posts/999887767301306/) | 1997-03-29 | 100 |
| 9 | [etsy.com](https://www.etsy.com/uk/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
### UK · candle CLP label software

含相关页面但混合模板/印刷/指南/工具；样本10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 2 | [glowclp.co.uk](https://www.glowclp.co.uk/product-category/digital-downloads/) | 2021-10-19 | 0 |
| 3 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 4 | [suppliesforcandles.co.uk](https://www.suppliesforcandles.co.uk/clps-getting-your-label-right-first-time/) | 2016-12-16 | 39 |
| 5 | [youtube.com](https://www.youtube.com/watch?v=4-Xq0TeKdcM) | 2005-02-15 | 99 |
| 6 | [etsy.com](https://www.etsy.com/uk/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
| 7 | [magicclps.co.uk](https://www.magicclps.co.uk/?srsltid=AYCX9vI_kGtJmO0p_BgCjKeTSLOjiswR38sOHzwo9cLd6jYnWJ9gV3OE) | 2020-05-24 | 7 |
| 8 | [nextsds.com](https://nextsds.com/tools/clp-widget/) | 2024-12-13 | 28 |
| 9 | [facebook.com](https://www.facebook.com/candleshackuk/posts/clp-labels-dont-need-to-be-complicated-our-free-design-tool-helps-you-create-cle/1334931478677304/) | 1997-03-29 | 100 |
| 10 | [luxurycandlesupplies.co.uk](https://www.luxurycandlesupplies.co.uk/clpprinting-candle.html) | 2018-05-22 | 35 |
### UK · scented candle CLP label generator

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [luxurycandlesupplies.co.uk](https://www.luxurycandlesupplies.co.uk/blog/post/solving-clp-labels) | 2018-05-22 | 35 |
| 2 | [yourcrafts.co.uk](https://yourcrafts.co.uk/blogs/candle-soap-making-blog/a-simple-guide-to-candle-clp?srsltid=AYCX9vJRKp2pHsJojtGs5Dz_r7byJCHpp0PFVhbQPVhNRFuyJcwRQvYp) | 2017-08-04 | 2 |
| 3 | [purescented.com](https://purescented.com/labels/?srsltid=AYCX9vJSzYZeM7lSrVwzSxqg6N8lxGCfsSuklC_oG-F7zYyX0TK8erAT) | 2016-01-06 | 25 |
| 4 | [facebook.com](https://www.facebook.com/groups/806335036656581/posts/1954726491817424/) | 1997-03-29 | 100 |
| 5 | [pinterest.com](https://www.pinterest.com/pin/free-clp-label-design-template--441352832249199217/) | 2009-11-26 | 97 |
| 6 | [fastlabels.co.uk](https://www.fastlabels.co.uk/custom-labels-stickers/clp-labels.html) | 2009-07-22 | 36 |
| 7 | [etsy.com](https://www.etsy.com/uk/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
| 8 | [glowclp.co.uk](https://www.glowclp.co.uk/product-category/clp-labels/digital-files-print-at-home-clp/) | 2021-10-19 | 0 |
| 9 | [glowclp.co.uk](https://www.glowclp.co.uk/creating-clp-labels-for-blended-fragrance-essential-oils/) | 2021-10-19 | 0 |
### UK · UK candle CLP label generator

明显跑偏；样本9条；剔除竞争判断；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [generator.org.uk](https://www.generator.org.uk/) | 1999-01-07 | 45 |
| 2 | [staygenerator.com](https://staygenerator.com/?lang=en-GB) | 2018-09-21 | 69 |
| 3 | [cmake.org](https://cmake.org/cmake/help/latest/manual/cmake-generators.7.html) | 2001-12-10 | 84 |
| 4 | [generators-direct.co.uk](https://www.generators-direct.co.uk/product-category/generators/petrol-generators/) | 2012-07-01 | 18 |
| 5 | [generatorprojects.co.uk](https://www.generatorprojects.co.uk/) | 2005-10-28 | 35 |
| 6 | [python.org](https://docs.python.org/3/library/collections.abc.html) | 1995-03-27 | 92 |
| 7 | [youtube.com](https://www.youtube.com/watch?v=coatlRPYpcE) | 2005-02-15 | 99 |
| 8 | [numpy.org](https://numpy.org/doc/stable/reference/random/generator.html) | 2000-03-29 | 85 |
| 9 | [reddit.com](https://www.reddit.com/r/Generator/) | 2005-04-29 | 95 |
### UK · EU candle CLP label generator

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 2 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 3 | [luxurycandlesupplies.co.uk](https://www.luxurycandlesupplies.co.uk/fragrance-oils/clp-label-maker.html) | 2018-05-22 | 35 |
| 4 | [nextsds.com](https://nextsds.com/tools/clp-widget/) | 2024-12-13 | 28 |
| 5 | [glowclp.co.uk](https://www.glowclp.co.uk/product-category/digital-downloads/) | 2021-10-19 | 0 |
| 6 | [youtube.com](https://www.youtube.com/watch?v=4-Xq0TeKdcM) | 2005-02-15 | 99 |
| 7 | [fastlabels.co.uk](https://www.fastlabels.co.uk/custom-labels-stickers/clp-labels.html) | 2009-07-22 | 36 |
| 8 | [armatagecandlecompany.com](https://armatagecandlecompany.com/blog/eu-candle-label-requirements/) | 2020-02-01 | 29 |
| 9 | [etsy.com](https://www.etsy.com/uk/listing/1595807000/planche-de-10-etiquettes-autocollantes) | 2004-02-05 | 94 |
### UK · candle CLP label calculator

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/candle-making-tools-services) | 2010-07-22 | 37 |
| 2 | [suppliesforcandles.co.uk](https://www.suppliesforcandles.co.uk/clps-getting-your-label-right-first-time/) | 2016-12-16 | 39 |
| 3 | [thesoapkitchen.co.uk](https://www.thesoapkitchen.co.uk/tsk-blog/articles/clp-legislation-explained/) | 2000-06-26 | 46 |
| 4 | [discountstickerprinting.co.uk](https://www.discountstickerprinting.co.uk/custom-stickers/clp-labels.html?srsltid=AYCX9vINO6RPGlgh2SJPGeaoa-soQ-oGEicREaYhRyTd9y56si_mFsZP) | 2010-10-12 | 36 |
| 5 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 6 | [luxurycandlesupplies.co.uk](https://www.luxurycandlesupplies.co.uk/fragrance-oils/clp-printing-service/clpprinting-candle.html) | 2018-05-22 | 35 |
| 7 | [youtube.com](https://www.youtube.com/watch?v=4-Xq0TeKdcM) | 2005-02-15 | 99 |
| 8 | [handylabels.co.uk](https://www.handylabels.co.uk/blog/post/clp-compliance-candles-2026-guide?srsltid=AYCX9vJuu8Fmso_hxMnY1ai7_k9yOnEHJNgFd306qjoUNf3RX-_y6elc) | 2007-05-04 | 36 |
| 9 | [glowclp.co.uk](https://www.glowclp.co.uk/product/combined-clp-safety-labels-for-candles-non-hazardous-base-up-to-10/) | 2021-10-19 | 0 |
### UK · SDS to candle CLP label

含相关页面但混合模板/印刷/指南/工具；样本10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [facebook.com](https://www.facebook.com/groups/733984733761856/posts/1009230066237320/) | 1997-03-29 | 100 |
| 2 | [suppliesforcandles.co.uk](https://www.suppliesforcandles.co.uk/clps-getting-your-label-right-first-time/) | 2016-12-16 | 39 |
| 3 | [britishcandles.org](https://www.britishcandles.org/documents/www.britishcandles.org/candlesadvicesheet(2019)_v6.pdf) | 2008-08-14 | 55 |
| 4 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 5 | [reddit.com](https://www.reddit.com/r/candlemaking/comments/oe845a/clp_labels/) | 2005-04-29 | 95 |
| 6 | [twinkcandlecompany.co.uk](https://www.twinkcandlecompany.co.uk/blogs/news/clp-labels-essential-for-candle-wax-melt-safety?srsltid=AYCX9vLkLMKfovKQst050ib9ishTAk1puca0zbnG61ZC3aeeP4V1pQrY) | 2023-03-22 | 7 |
| 7 | [glowclp.co.uk](https://www.glowclp.co.uk/product/combined-clp-safety-labels-for-candles-non-hazardous-base-up-to-10/) | 2021-10-19 | 0 |
| 8 | [glowclp.co.uk](https://www.glowclp.co.uk/product-category/clp-labels/clps-wax-melts/) | 2021-10-19 | 0 |
| 9 | [clp-services.co.uk](https://clp-services.co.uk/products/clp-label-sds-authoring-service-essential-oil-blend) | 2026-04-07 | 0 |
| 10 | [stallsync.co.uk](https://stallsync.co.uk/guides/clp-regulations-labelling) | 2024-08-12 | 3 |
### UK · CLP labels for blended fragrance candles

明显跑偏；样本9条；剔除竞争判断；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [stickylabels.com](https://www.stickylabels.com/) | 1998-04-15 | 34 |
| 2 | [amazon.co.uk](https://www.amazon.co.uk/labels/b?ie=UTF8&node=200900031) | 1994-12-05 | 93 |
| 3 | [google.com](https://docs.cloud.google.com/resource-manager/docs/creating-managing-labels) | 1997-09-15 | 100 |
| 4 | [avery.co.uk](https://www.avery.co.uk/blank-labels) | 1997-12-05 | 61 |
| 5 | [atlassian.com](https://support.atlassian.com/confluence-cloud/docs/use-labels-to-organize-your-content/) | 2001-03-19 | 92 |
| 6 | [label.co.uk](https://label.co.uk/) | 1997-06-10 | 25 |
| 7 | [fca.org.uk](https://www.fca.org.uk/firms/climate-change-and-sustainable-finance/labels) | 2010-10-05 | 91 |
| 8 | [prometheus.io](https://prometheus.io/docs/practices/naming/) | 2013-01-25 | 87 |
| 9 | [kubernetes.io](https://kubernetes.io/docs/concepts/overview/working-with-objects/labels/) | 2014-07-23 | 90 |
### UK · printable candle CLP label generator

含相关页面但混合模板/印刷/指南/工具；样本10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery.co.uk](https://www.avery.co.uk/print-service/personalised-labels/use/craft/clp) | 1997-12-05 | 61 |
| 2 | [glowclp.co.uk](https://www.glowclp.co.uk/product-category/digital-downloads/) | 2021-10-19 | 0 |
| 3 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 4 | [pinterest.com](https://www.pinterest.com/pin/free-clp-label-design-template--441352832249199217/) | 2009-11-26 | 97 |
| 5 | [luxurycandlesupplies.co.uk](https://www.luxurycandlesupplies.co.uk/fragrance-oils/clp-label-maker.html) | 2018-05-22 | 35 |
| 6 | [etsy.com](https://www.etsy.com/uk/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
| 7 | [suppliesforcandles.co.uk](https://www.suppliesforcandles.co.uk/clps-getting-your-label-right-first-time/) | 2016-12-16 | 39 |
| 8 | [nextsds.com](https://nextsds.com/tools/clp-widget/) | 2024-12-13 | 28 |
| 9 | [stickyprintpixels.co.uk](https://stickyprintpixels.co.uk/collections/clp-labels?srsltid=AYCX9vK4H0wDi-YojkfdpK29V5BRxA4A6tW81bGedC5YaF46WYwFawAa) | 2021-03-01 | 0 |
| 10 | [youtube.com](https://www.youtube.com/watch?v=4-Xq0TeKdcM) | 2005-02-15 | 99 |
### UK · CLP label template for candles

相邻模板意图，不计主任务搜索量或竞争分；含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 2 | [glowclp.co.uk](https://www.glowclp.co.uk/product/clp-labels-for-fragrance-oils-pdf-or-word-digital-download/) | 2021-10-19 | 0 |
| 3 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 4 | [suppliesforcandles.co.uk](https://www.suppliesforcandles.co.uk/clps-getting-your-label-right-first-time/) | 2016-12-16 | 39 |
| 5 | [etsy.com](https://www.etsy.com/uk/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
| 6 | [pinterest.com](https://www.pinterest.com/pin/free-clp-label-design-template--441352832249199217/) | 2009-11-26 | 97 |
| 7 | [stickyprintpixels.co.uk](https://stickyprintpixels.co.uk/collections/clp-labels?srsltid=AYCX9vJyiFbBmIGEXXoVZJJy_Foib1MkXG4j-eA3FOSFrrHjVbwlE6OE) | 2021-03-01 | 0 |
| 8 | [handylabels.co.uk](https://www.handylabels.co.uk/products/specialised-products/clp-labels.html?srsltid=AYCX9vIkD0CJzxUUP5NV_-iCgJfKzVUWP3b4vkCZq8YtIgLY_8afEV5t) | 2007-05-04 | 36 |
| 9 | [cosyowl.com](https://cosyowl.com/guides/clp-labelling-what-you-need-to-know) | 2017-10-27 | 46 |
### CA · candle CLP label generator

明显跑偏；样本9条；剔除竞争判断；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [clp.com.hk](https://www.clp.com.hk/en/index) | 未找到 | 69 |
| 2 | [ubc.ca](https://www.math.ubc.ca/~CLP/) | 2000-10-05 | 90 |
| 3 | [europa.eu](https://echa.europa.eu/regulations/clp/legislation) | 未找到 | 97 |
| 4 | [qc.ca](https://alliancedesprofs.qc.ca/votre-equipe-syndicale/clp) | 未找到 | 15 |
| 5 | [rnao.ca](https://rnao.ca/membership/benefits/cyber-liability-protection-clp) | 2006-03-17 | 73 |
| 6 | [reddit.com](https://www.reddit.com/r/DigitalPiano/comments/1q1bj29/help_me_chose_between_the_yamaha_clp875_and_the/) | 2005-04-29 | 95 |
| 7 | [facebook.com](https://www.facebook.com/CLPawards/videos/-40-years-of-clp-promoting-harmony-with-nature-the-theme-of-todays-international/1883944422441613/) | 1997-03-29 | 100 |
| 8 | [europa.eu](https://environment.ec.europa.eu/topics/chemicals/classification-labelling-and-packaging-chemicals_en) | 未找到 | 97 |
| 9 | [youtube.com](https://www.youtube.com/watch?v=9d_zNkd2jys) | 2005-02-15 | 99 |
### CA · CLP label maker for candles

含相关页面但混合模板/印刷/指南/工具；样本7条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 2 | [facebook.com](https://www.facebook.com/groups/806335036656581/posts/999887767301306/) | 1997-03-29 | 100 |
| 3 | [nicandlesupplies.com](https://www.nicandlesupplies.com/pages/clp-label-printing?srsltid=AYCX9vLqyP18KU8SneuEYEIuCK6GTEfu8NIuQxRvjEsDMAisjOQonzWE) | 2017-10-28 | 27 |
| 4 | [pinterest.com](https://www.pinterest.com/pin/clp-label-templates-for-candles-and-wax-melts--441352832243105209/) | 2009-11-26 | 97 |
| 5 | [trustpilot.com](https://www.trustpilot.com/review/luxurycandlesupplies.co.uk/product/clp-label-printing-diffuser-base-less-25percent-69f228aab054841c966f3945) | 2007-06-30 | 94 |
| 6 | [etsy.com](https://www.etsy.com/ca/listing/926615392/37mm-candle-clp-label-round) | 2004-02-05 | 94 |
| 7 | [niimbots.com](https://niimbots.com/blogs/news/how-to-make-candle-labels?srsltid=AYCX9vLrymmr4_b3h1wYOy-Wf7LSR98aPBFPp1FWHyZjfiZZ5WCKEVhu) | 2021-11-03 | 41 |
### CA · candle CLP label software

含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 2 | [youtube.com](https://www.youtube.com/watch?v=4-Xq0TeKdcM) | 2005-02-15 | 99 |
| 3 | [nicandlesupplies.com](https://www.nicandlesupplies.com/blogs/news-and-updates/what-you-need-to-know-about-clp-labels-for-candles?srsltid=AYCX9vJE7bhIG-jvYwpIPD7kpsudDv1gJJO7LCLFfc7gIGyDo-jNK3x2) | 2017-10-28 | 27 |
| 4 | [nextsds.com](https://nextsds.com/tools/clp-widget/) | 2024-12-13 | 28 |
| 5 | [facebook.com](https://www.facebook.com/candleshackuk/posts/clp-labels-dont-need-to-be-complicated-our-free-design-tool-helps-you-create-cle/1334931478677304/) | 1997-03-29 | 100 |
| 6 | [glowclp.co.uk](https://www.glowclp.co.uk/product-category/digital-downloads/) | 2021-10-19 | 0 |
| 7 | [etsy.com](https://www.etsy.com/ca/listing/1019772028/editable-candle-warning-labels-clp) | 2004-02-05 | 94 |
| 8 | [pinterest.com](https://www.pinterest.com/pin/clp-label-templates-for-candles-and-wax-melts--441352832243105209/) | 2009-11-26 | 97 |
### CA · scented candle CLP label generator

含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 2 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 3 | [luxurycandlesupplies.co.uk](https://www.luxurycandlesupplies.co.uk/fragrance-oils/clp-label-maker.html) | 2018-05-22 | 35 |
| 4 | [facebook.com](https://www.facebook.com/groups/806335036656581/posts/1954726491817424/) | 1997-03-29 | 100 |
| 5 | [pinterest.com](https://www.pinterest.com/pin/free-clp-label-design-template--441352832249199217/) | 2009-11-26 | 97 |
| 6 | [craftcert.co.uk](https://craftcert.co.uk/blog/what-to-look-for-clp-label-generator) | 2026-03-14 | 0 |
| 7 | [glowclp.co.uk](https://www.glowclp.co.uk/product/clp-labels-for-fragrance-oils-pdf-or-word-digital-download/) | 2021-10-19 | 0 |
| 8 | [etsy.com](https://www.etsy.com/ca/listing/1019772028/editable-candle-warning-labels-clp) | 2004-02-05 | 94 |
### CA · UK candle CLP label generator

含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 2 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 3 | [handylabels.co.uk](https://www.handylabels.co.uk/products/specialised-products/clp-labels.html?srsltid=AYCX9vIvY2DIUBymQjKF5SOtTOyTI8xN39E3_nQY8JwmlC1kH1F6O7dP) | 2007-05-04 | 36 |
| 4 | [facebook.com](https://www.facebook.com/candleshackuk/posts/clp-labels-dont-need-to-be-complicated-our-free-design-tool-helps-you-create-cle/1334931478677304/) | 1997-03-29 | 100 |
| 5 | [craftcert.co.uk](https://craftcert.co.uk/blog/what-to-look-for-clp-label-generator) | 2026-03-14 | 0 |
| 6 | [luxurycandlesupplies.co.uk](https://www.luxurycandlesupplies.co.uk/fragrance-oils/clp-label-maker.html) | 2018-05-22 | 35 |
| 7 | [glowclp.co.uk](https://www.glowclp.co.uk/product/clp-labels-for-candles-wax-melts/) | 2021-10-19 | 0 |
| 8 | [pinterest.com](https://www.pinterest.com/pin/free-clp-label-design-template--441352832249199217/) | 2009-11-26 | 97 |
### CA · EU candle CLP label generator

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 2 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 3 | [armatagecandlecompany.com](https://armatagecandlecompany.com/blog/eu-candle-label-requirements/) | 2020-02-01 | 29 |
| 4 | [nicandlesupplies.com](https://www.nicandlesupplies.com/blogs/news-and-updates/what-you-need-to-know-about-clp-labels-for-candles?srsltid=AYCX9vIvZzxJLwfTlQ2nROXGkL2Ea4MHqX83TLRb1pACjeFBIFEvd7zC) | 2017-10-28 | 27 |
| 5 | [nextsds.com](https://nextsds.com/tools/clp-widget/) | 2024-12-13 | 28 |
| 6 | [youtube.com](https://www.youtube.com/watch?v=4-Xq0TeKdcM) | 2005-02-15 | 99 |
| 7 | [pinterest.com](https://www.pinterest.com/pin/free-clp-label-design-template--441352832249199217/) | 2009-11-26 | 97 |
| 8 | [etsy.com](https://www.etsy.com/ca/listing/1643448058/sheet-of-12-clp-self-adhesive-labels-for) | 2004-02-05 | 94 |
| 9 | [taobe.consulting](https://taobe.consulting/clp-candle-label-regulations/) | 2019-03-22 | 21 |
### CA · candle CLP label calculator

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/candle-making-tools-services) | 2010-07-22 | 37 |
| 2 | [youtube.com](https://www.youtube.com/watch?v=4-Xq0TeKdcM) | 2005-02-15 | 99 |
| 3 | [nicandlesupplies.com](https://www.nicandlesupplies.com/blogs/news-and-updates/what-you-need-to-know-about-clp-labels-for-candles?srsltid=AYCX9vI3lMhISEuGps7FmBGDrAfp5GFTvboEh0b2Cfq_2SmGK9N5-QWc) | 2017-10-28 | 27 |
| 4 | [facebook.com](https://www.facebook.com/candleshackuk/posts/clp-labels-dont-need-to-be-complicated-our-free-design-tool-helps-you-create-cle/1334931478677304/) | 1997-03-29 | 100 |
| 5 | [suppliesforcandles.co.uk](https://www.suppliesforcandles.co.uk/clps-getting-your-label-right-first-time/) | 2016-12-16 | 39 |
| 6 | [etsy.com](https://www.etsy.com/ca/listing/1019772028/editable-candle-warning-labels-clp) | 2004-02-05 | 94 |
| 7 | [pinterest.com](https://www.pinterest.com/pin/clp-label-templates-for-candles-and-wax-melts--441352832243105209/) | 2009-11-26 | 97 |
| 8 | [nextsds.com](https://nextsds.com/tools/clp-widget/) | 2024-12-13 | 28 |
| 9 | [yourcrafts.co.uk](https://yourcrafts.co.uk/blogs/candle-soap-making-blog/a-simple-guide-to-candle-clp?srsltid=AYCX9vIBW5Hl0A_iSjMnlCHjzahd6WwhX2zp3npFX3y7PXqaPhCLrbci) | 2017-08-04 | 2 |
### CA · SDS to candle CLP label

含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [terre-de-bougies.com](https://www.terre-de-bougies.com/en/blogs/news/bonds-sale-candles-melts?srsltid=AYCX9vKiEZhKzlaU8PAw34mQ37EUWnAXYzAKOWTf0lPiibIQsPQ-jjAh) | 2012-03-09 | 40 |
| 2 | [facebook.com](https://www.facebook.com/groups/candlemakingclub/posts/1845433812903169/) | 1997-03-29 | 100 |
| 3 | [homefragrance.academy](https://www.homefragrance.academy/blog/top-clp-labelling-mistakes-candle-makers-should-avoid-expert-tips-and-advice) | 2023-06-04 | 1 |
| 4 | [handylabels.co.uk](https://www.handylabels.co.uk/blog/post/clp-compliance-candles-2026-guide?srsltid=AYCX9vImG-gPhb4QKa_f9tEWsN4ybIz0H3HHgnLMMcY8IOrR3sNdwsGY) | 2007-05-04 | 36 |
| 5 | [essentialoilblends.co.uk](https://essentialoilblends.co.uk/products/clp?srsltid=AYCX9vLJ3aDulnoEWyYEcefdXg4FPpypTqxtD8zwmGHrUusYqrKHGiuX) | 2021-01-09 | 0 |
| 6 | [reddit.com](https://www.reddit.com/r/candlemaking/comments/1s3nqoy/clp_labels_is_anyone_actually_confident_theyre/) | 2005-04-29 | 95 |
| 7 | [craftcert.co.uk](https://craftcert.co.uk/blog/clp-labelling-guide-candle-wax-melt) | 2026-03-14 | 0 |
| 8 | [clp-services.co.uk](https://clp-services.co.uk/products/clp-label-sds-authoring-service-essential-oil-blend) | 2026-04-07 | 0 |
### CA · CLP labels for blended fragrance candles

含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [terre-de-bougies.com](https://www.terre-de-bougies.com/en/blogs/news/bonds-sale-candles-melts?srsltid=AYCX9vIHBTfKMNQqeZPWkDAlZh7vOqAF_7B9J2XHN052GCbbs22HmN_e) | 2012-03-09 | 40 |
| 2 | [facebook.com](https://www.facebook.com/groups/candlemakingclub/posts/2178029686310245/) | 1997-03-29 | 100 |
| 3 | [glowclp.co.uk](https://www.glowclp.co.uk/creating-clp-labels-for-blended-fragrance-essential-oils/) | 2021-10-19 | 0 |
| 4 | [suppliesforcandles.co.uk](https://www.suppliesforcandles.co.uk/clps-getting-your-label-right-first-time/) | 2016-12-16 | 39 |
| 5 | [craftcert.co.uk](https://craftcert.co.uk/blog/clp-labels-for-candles-guide) | 2026-03-14 | 0 |
| 6 | [purescented.com](https://purescented.com/labels/?srsltid=AYCX9vLg2wRO4vnPZps8O3x5ELxsl_f9naA0VH5VKn4ZozZ8PAVIl2NF) | 2016-01-06 | 25 |
| 7 | [yourcrafts.co.uk](https://yourcrafts.co.uk/blogs/candle-soap-making-blog/a-simple-guide-to-candle-clp?srsltid=AYCX9vIY4ELC98I2cl-vH5Xl9zxIEDBZV4-4As3jS0HycIJAMO_Bf8aU) | 2017-08-04 | 2 |
| 8 | [youwish.nl](https://www.youwish.nl/en/candle-making/clp-label/?srsltid=AYCX9vLRF3SIr1pKXhYrPXDRU_Wj87pywW5bHOvpdWOEAk4BS96ZFvFI) | 2009-12-08 | 28 |
### CA · printable candle CLP label generator

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [pinterest.com](https://www.pinterest.com/pin/free-clp-label-design-template--441352832249199217/) | 2009-11-26 | 97 |
| 2 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 3 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 4 | [nextsds.com](https://nextsds.com/tools/clp-widget/) | 2024-12-13 | 28 |
| 5 | [youtube.com](https://www.youtube.com/watch?v=4-Xq0TeKdcM) | 2005-02-15 | 99 |
| 6 | [luxurycandlesupplies.co.uk](https://www.luxurycandlesupplies.co.uk/fragrance-oils/clp-label-maker.html) | 2018-05-22 | 35 |
| 7 | [glowclp.co.uk](https://www.glowclp.co.uk/product-category/digital-downloads/) | 2021-10-19 | 0 |
| 8 | [betckey.com](https://betckey.com/blogs/news/7-must-have-free-candle-label-template-websites?srsltid=AYCX9vJAtvERQbs2l6O_yY-7O_pPo7ZpeLgRZD9WUjaXmbNfmaWTSmAI) | 2016-03-30 | 53 |
| 9 | [etsy.com](https://www.etsy.com/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
### CA · CLP label template for candles

相邻模板意图，不计主任务搜索量或竞争分；含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 2 | [pinterest.com](https://www.pinterest.com/pin/free-clp-label-design-template--441352832249199217/) | 2009-11-26 | 97 |
| 3 | [handylabels.co.uk](https://www.handylabels.co.uk/products/specialised-products/clp-labels.html?srsltid=AYCX9vKx3thqbSZWYt9eOEbRpW5y10uBQh86rgLcZ1vFY8n0pIxd1ewZ) | 2007-05-04 | 36 |
| 4 | [etsy.com](https://www.etsy.com/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
| 5 | [glowclp.co.uk](https://www.glowclp.co.uk/product/clp-labels-for-fragrance-oils-pdf-or-word-digital-download/) | 2021-10-19 | 0 |
| 6 | [nicandlesupplies.com](https://www.nicandlesupplies.com/blogs/news-and-updates/what-you-need-to-know-about-clp-labels-for-candles?srsltid=AYCX9vLgF3Zrrqj0xzgF8B5n0u54w5CfARtqZq663O3YNALKaw4W8HVu) | 2017-10-28 | 27 |
| 7 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 8 | [adobe.com](https://www.adobe.com/express/templates/label/candle) | 1986-11-17 | 96 |
| 9 | [canva.com](https://www.canva.com/labels/templates/candle/) | 2001-05-05 | 93 |
### AU · candle CLP label generator

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 2 | [pinterest.com](https://www.pinterest.com/pin/free-clp-label-design-template--441352832249199217/) | 2009-11-26 | 97 |
| 3 | [luxurycandlesupplies.co.uk](https://www.luxurycandlesupplies.co.uk/fragrance-oils/clp-label-maker.html) | 2018-05-22 | 35 |
| 4 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 5 | [nextsds.com](https://nextsds.com/tools/clp-widget/) | 2024-12-13 | 28 |
| 6 | [etsy.com](https://www.etsy.com/au/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
| 7 | [glowclp.co.uk](https://www.glowclp.co.uk/product-category/digital-downloads/) | 2021-10-19 | 0 |
| 8 | [stickyprintpixels.co.uk](https://stickyprintpixels.co.uk/collections/clp-labels?srsltid=AYCX9vLvldfM3wlwFR1IGfRcaxAsZ8J-QnLnbMNvFCUDqYyIt05_ubBs) | 2021-03-01 | 0 |
| 9 | [facebook.com](https://www.facebook.com/groups/806335036656581/posts/2085214892101916/) | 1997-03-29 | 100 |
### AU · CLP label maker for candles

明显跑偏；样本9条；剔除竞争判断；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [centreforhumanitarianleadership.org](https://www.centreforhumanitarianleadership.org/education/courses/short-courses/crisis-leadership-program/) | 2015-08-20 | 42 |
| 2 | [edu.au](https://schoolforstudentleadership.vic.edu.au/clp/) | 未找到 | 27 |
| 3 | [clp.org.au](https://clp.org.au/) | 未找到 | 28 |
| 4 | [yamaha.com](https://au.yamaha.com/en/musical-instruments/pianos/products/clavinova/clp-800-series/clp-875/) | 1994-11-01 | 88 |
| 5 | [clpgroup.com](https://clpgroup.com/) | 1997-12-23 | 64 |
| 6 | [thesaturdaypaper.com.au](https://www.thesaturdaypaper.com.au/comment/politics/2026/09/05/clp-writing-australias-far-right-playbook) | 未找到 | 73 |
| 7 | [clpsychiatry.org](https://clpsychiatry.org/about-aclp/whatis-clp/) | 2016-12-21 | 60 |
| 8 | [fao.org](https://www.fao.org/gfoi/resources/videos/video-detail/fourth--connect-and-reflect--virtual-forum--guatemala-s-experience-in-the-clp-process/en) | 1993-07-14 | 91 |
| 9 | [youtube.com](https://www.youtube.com/watch?v=vyknbn7B4iE) | 2005-02-15 | 99 |
### AU · candle CLP label software

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 2 | [nicandlesupplies.com](https://www.nicandlesupplies.com/blogs/news-and-updates/what-you-need-to-know-about-clp-labels-for-candles?srsltid=AYCX9vJ59HFOpCYgBMJg7RKOjanoaq3LkFVh6t4HBJK8sEC0cg8Z24KD) | 2017-10-28 | 27 |
| 3 | [youtube.com](https://www.youtube.com/watch?v=4-Xq0TeKdcM) | 2005-02-15 | 99 |
| 4 | [nextsds.com](https://nextsds.com/tools/clp-widget/) | 2024-12-13 | 28 |
| 5 | [etsy.com](https://www.etsy.com/au/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
| 6 | [facebook.com](https://www.facebook.com/candleshackuk/posts/clp-labels-dont-need-to-be-complicated-our-free-design-tool-helps-you-create-cle/1334931478677304/) | 1997-03-29 | 100 |
| 7 | [glowclp.co.uk](https://www.glowclp.co.uk/product-category/digital-downloads/) | 2021-10-19 | 0 |
| 8 | [luxurycandlesupplies.co.uk](https://www.luxurycandlesupplies.co.uk/clpprinting-candle.html) | 2018-05-22 | 35 |
| 9 | [pinterest.com](https://www.pinterest.com/pin/clp-label-templates-for-candles-and-wax-melts--441352832243105209/) | 2009-11-26 | 97 |
### AU · scented candle CLP label generator

含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 2 | [luxurycandlesupplies.co.uk](https://www.luxurycandlesupplies.co.uk/fragrance-oils/clp-label-maker.html) | 2018-05-22 | 35 |
| 3 | [etsy.com](https://www.etsy.com/au/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
| 4 | [facebook.com](https://www.facebook.com/groups/806335036656581/posts/1954726491817424/) | 1997-03-29 | 100 |
| 5 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 6 | [pinterest.com](https://www.pinterest.com/pin/free-clp-label-design-template--441352832249199217/) | 2009-11-26 | 97 |
| 7 | [craftcert.co.uk](https://craftcert.co.uk/blog/what-to-look-for-clp-label-generator) | 2026-03-14 | 0 |
| 8 | [glowclp.co.uk](https://www.glowclp.co.uk/product/clp-labels-for-fragrance-oils-pdf-or-word-digital-download/) | 2021-10-19 | 0 |
### AU · UK candle CLP label generator

明显跑偏；样本9条；剔除竞争判断；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [glasshousefragrances.com](https://www.glasshousefragrances.com/collections/home-fragrance-candles?srsltid=AYCX9vLECYDJhfwVPdLMwxO6w3b6XBuxzsFfFAkCONTU5C3WW20T2Q8R) | 2009-04-18 | 58 |
| 2 | [ecoya.com.au](https://www.ecoya.com.au/collections/candles?srsltid=AYCX9vISLus14UUSDAPSqgGClzJo_FnPxpeYofX8xuvH4-Y-_FhbMXVQ) | 未找到 | 45 |
| 3 | [dusk.com.au](https://www.dusk.com.au/candles-melts/candles?srsltid=AYCX9vJ4HwscukRSq8DMQTkPvCTWW9EtNeXzyZ85j6wttL5XcIw-ap1J) | 未找到 | 51 |
| 4 | [gov.au](https://www.cancer.nsw.gov.au/research-and-data/cancer-data-and-statistics/data-available-on-request/candle-program/how-to-access-the-candle-data/candle-data) | 未找到 | 39 |
| 5 | [candle-project.eu](https://candle-project.eu/) | 未找到 | 18 |
| 6 | [flamingoestate.com](https://flamingoestate.com/products/roma-heirloom-tomato-soy-wax-candle?srsltid=AYCX9vLudwg6UU0qGYx5IRjLBZXdVzlheZ1ouvsUD2jFKtk3Dup8bcvU) | 2018-06-21 | 69 |
| 7 | [instagram.com](https://www.instagram.com/sircandleman/?hl=en) | 2004-06-04 | 100 |
| 8 | [albathermalsprings.com.au](https://albathermalsprings.com.au/shop/the-cape-candle/) | 未找到 | 50 |
| 9 | [abeautifulmess.com](https://abeautifulmess.com/how-to-make-candles-beginners-guide/) | 2005-12-17 | 77 |
### AU · EU candle CLP label generator

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 2 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 3 | [nextsds.com](https://nextsds.com/tools/clp-widget/) | 2024-12-13 | 28 |
| 4 | [facebook.com](https://www.facebook.com/candleshackuk/posts/clp-labels-dont-need-to-be-complicated-our-free-design-tool-helps-you-create-cle/1334931478677304/) | 1997-03-29 | 100 |
| 5 | [armatagecandlecompany.com](https://armatagecandlecompany.com/blog/eu-candle-label-requirements/) | 2020-02-01 | 29 |
| 6 | [nicandlesupplies.com](https://www.nicandlesupplies.com/blogs/news-and-updates/what-you-need-to-know-about-clp-labels-for-candles?srsltid=AYCX9vKzkuomaSa40mR0ixV1tGoBAkkyCrb2GpuIcR0GzEQ5BCkqT_9J) | 2017-10-28 | 27 |
| 7 | [luxurycandlesupplies.eu](https://luxurycandlesupplies.eu/product/clp-label-printing/) | 未找到 | 5 |
| 8 | [youtube.com](https://www.youtube.com/watch?v=4-Xq0TeKdcM) | 2005-02-15 | 99 |
| 9 | [etsy.com](https://www.etsy.com/au/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
### AU · candle CLP label calculator

含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/candle-making-tools-services) | 2010-07-22 | 37 |
| 2 | [suppliesforcandles.co.uk](https://www.suppliesforcandles.co.uk/clps-getting-your-label-right-first-time/) | 2016-12-16 | 39 |
| 3 | [thesoapkitchen.co.uk](https://www.thesoapkitchen.co.uk/tsk-blog/articles/clp-legislation-explained/) | 2000-06-26 | 46 |
| 4 | [etsy.com](https://www.etsy.com/au/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
| 5 | [facebook.com](https://www.facebook.com/groups/806335036656581/posts/1079223046034444/) | 1997-03-29 | 100 |
| 6 | [cosyowl.com](https://cosyowl.com/guides/clp-labelling-what-you-need-to-know) | 2017-10-27 | 46 |
| 7 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 8 | [handylabels.co.uk](https://www.handylabels.co.uk/blog/post/clp-compliance-candles-2026-guide?srsltid=AYCX9vJNRK-ggRqKIaGnUDTHxkFVhqgMoKOZ7cAofT-6yR52OxFybQlZ) | 2007-05-04 | 36 |
### AU · SDS to candle CLP label

含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [terre-de-bougies.com](https://www.terre-de-bougies.com/en/blogs/news/bonds-sale-candles-melts?srsltid=AYCX9vKTQtc2aDBhlaFO9VAYbZSZR9WcxNWZC_bnvB31SGzMZO6_HqWN) | 2012-03-09 | 40 |
| 2 | [facebook.com](https://www.facebook.com/groups/candlemakingclub/posts/1845433812903169/) | 1997-03-29 | 100 |
| 3 | [yourcrafts.co.uk](https://yourcrafts.co.uk/blogs/candle-soap-making-blog/a-simple-guide-to-candle-clp?srsltid=AYCX9vKQH43tkWSYFf0mej49Fcauy85rS984OzDBLFlGMsqKxWlXwY1P) | 2017-08-04 | 2 |
| 4 | [gov.uk](https://www.hseni.gov.uk/articles/candles-and-clp) | 未找到 | 86 |
| 5 | [homefragrance.academy](https://www.homefragrance.academy/blog/top-clp-labelling-mistakes-candle-makers-should-avoid-expert-tips-and-advice) | 2023-06-04 | 1 |
| 6 | [handylabels.co.uk](https://www.handylabels.co.uk/blog/post/clp-compliance-candles-2026-guide?srsltid=AYCX9vLhxgr0i3A36Xhrzf2hgWUFu5YSgUC4qkfvOVQn8RY2h_Vx33hf) | 2007-05-04 | 36 |
| 7 | [essentialoilblends.co.uk](https://essentialoilblends.co.uk/products/clp?srsltid=AYCX9vI7gIE4meQwLFmFSPjJqVCKE7JXUy64skDU5XDKJKPSTYmMioAL) | 2021-01-09 | 0 |
| 8 | [etsy.com](https://www.etsy.com/au/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
### AU · CLP labels for blended fragrance candles

含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [glowclp.co.uk](https://www.glowclp.co.uk/product-category/clp-labels/clps-candles/) | 2021-10-19 | 0 |
| 2 | [facebook.com](https://www.facebook.com/groups/candlemakingclub/posts/2178029686310245/) | 1997-03-29 | 100 |
| 3 | [suppliesforcandles.co.uk](https://www.suppliesforcandles.co.uk/clps-getting-your-label-right-first-time/) | 2016-12-16 | 39 |
| 4 | [taobe.consulting](https://taobe.consulting/clp-candle-label-regulations/) | 2019-03-22 | 21 |
| 5 | [terre-de-bougies.com](https://www.terre-de-bougies.com/en/blogs/news/bonds-sale-candles-melts?srsltid=AYCX9vLHRLS-mxaReCdV012H4vcfV-HU5bnW_Se3ga5-Lb96mGn6SY-Y) | 2012-03-09 | 40 |
| 6 | [yourcrafts.co.uk](https://yourcrafts.co.uk/blogs/candle-soap-making-blog/a-simple-guide-to-candle-clp?srsltid=AYCX9vIUeYEp4ufW_jMKOJfzKDIARNhKEj-mp90vhlCgGlIa6yPnv9aE) | 2017-08-04 | 2 |
| 7 | [craftcert.co.uk](https://craftcert.co.uk/blog/clp-labels-for-candles-guide) | 2026-03-14 | 0 |
| 8 | [purescented.com](https://purescented.com/labels/?srsltid=AYCX9vJStL1IlzZ3kne3OsKcuraABJPGkXv4gaFoeUrTXYeG4lhD0qjN) | 2016-01-06 | 25 |
### AU · printable candle CLP label generator

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [pinterest.com](https://www.pinterest.com/pin/free-clp-label-design-template--441352832249199217/) | 2009-11-26 | 97 |
| 2 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 3 | [luxurycandlesupplies.co.uk](https://www.luxurycandlesupplies.co.uk/fragrance-oils/clp-label-maker.html) | 2018-05-22 | 35 |
| 4 | [nextsds.com](https://nextsds.com/tools/clp-widget/) | 2024-12-13 | 28 |
| 5 | [etsy.com](https://www.etsy.com/au/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
| 6 | [youtube.com](https://www.youtube.com/watch?v=4-Xq0TeKdcM) | 2005-02-15 | 99 |
| 7 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 8 | [glowclp.co.uk](https://www.glowclp.co.uk/product-category/digital-downloads/) | 2021-10-19 | 0 |
| 9 | [canva.com](https://www.canva.com/labels/templates/candle/) | 2001-05-05 | 93 |
### AU · CLP label template for candles

相邻模板意图，不计主任务搜索量或竞争分；含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery.co.uk](https://www.avery.co.uk/blog/tips/clp-templates-candle-wax-melt-labels-stickers) | 1997-12-05 | 61 |
| 2 | [pinterest.com](https://www.pinterest.com/pin/free-clp-label-design-template--441352832249199217/) | 2009-11-26 | 97 |
| 3 | [etsy.com](https://www.etsy.com/au/listing/1019738820/clp-candle-warning-label-template) | 2004-02-05 | 94 |
| 4 | [nicandlesupplies.com](https://www.nicandlesupplies.com/blogs/news-and-updates/what-you-need-to-know-about-clp-labels-for-candles?srsltid=AYCX9vJ38IhyhX7KwqGAvBhUTtYU9vbaMo4PNgJjrZyf5lDaRfEvpVmj) | 2017-10-28 | 27 |
| 5 | [glowclp.co.uk](https://www.glowclp.co.uk/product/clp-labels-for-fragrance-oils-pdf-or-word-digital-download/) | 2021-10-19 | 0 |
| 6 | [handylabels.co.uk](https://www.handylabels.co.uk/products/specialised-products/clp-labels.html?srsltid=AYCX9vJ190Zw2KJcCXLO4bvV-WuxhbNiTpBaQN4tQdaglXEM8S28Ukiw) | 2007-05-04 | 36 |
| 7 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 8 | [adobe.com](https://www.adobe.com/express/templates/label/candle) | 1986-11-17 | 96 |
### DE · CLP-Etiketten für Kerzen erstellen

含相关页面但混合模板/印刷/指南/工具；样本5条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [avery-zweckform.com](https://www.avery-zweckform.com/compliance/clp-etiketten?srsltid=AYCX9vKA-v_f0G0rJLJKli8EWhMRSAFNdzwC2brdiqIdLRFfYe5CrMCw) | 1998-10-27 | 63 |
| 2 | [candle-shack.com](https://candle-shack.com/de/pages/clp-label-design-tool?srsltid=AYCX9vKE6oChOAwzV9KvdWtLYuZo3Rgj4VGYcRY5M-gBVNhR2iVQU1Sq) | 2021-02-21 | 26 |
| 3 | [terre-de-bougies.com](https://www.terre-de-bougies.com/de/blogs/nachrichten/anleihen-verkauf-kerzen-fondant?srsltid=AYCX9vL-c-8uJwUgV1YywElwh5B5GshOfevojKMGgXEAbZWmUFco09AS) | 2012-03-09 | 40 |
| 4 | [kaisercandle.de](https://kaisercandle.de/blogs/kerzenwissen/clp-verordnung-fuer-duftkerzen-einfach-erklaert?srsltid=AYCX9vLeNCcxwn8t_9ZBAMK3jI-rLehdPOkAe4Ku7uhin5CVagDuLvy9) | 未找到 | 5 |
| 5 | [candle-shack.com](https://candle-shack.com/de/blogs/all-blogs/your-clp-questions-answered?srsltid=AYCX9vL6UsfgvnrIjCCsyaf752z4LLhqklYWY-2Apdy3PesrPuXqCQfG) | 2021-02-21 | 26 |
### DE · CLP-Etiketten Generator Duftkerzen

明显跑偏；样本10条；剔除竞争判断；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [amazon.de](https://www.amazon.de/Etiketten-Aufkleber/b?ie=UTF8&node=202801031) | 未找到 | 93 |
| 2 | [etikett.de](https://etikett.de/) | 未找到 | 33 |
| 3 | [vistaprint.de](https://www.vistaprint.de/etiketten-und-aufkleber/personalisierte-etiketten?srsltid=AYCX9vLbbOwDtGJmGniJXLAqFTa9UfWfRqSEeYeF4ro-t5MliwTAjfBc) | 未找到 | 69 |
| 4 | [etiketten.shop](https://etiketten.shop/?srsltid=AYCX9vLWIIagEkkeab3jQzH5zVGCABjl-ZCe1O1O5fojt6KuePdeMOZu) | 2016-09-01 | 23 |
| 5 | [youtube.com](https://www.youtube.com/watch?v=4xoJlHobKmM) | 2005-02-15 | 99 |
| 6 | [graphisoft.com](https://community.graphisoft.com/t5/Wunschliste/Etiketten-mit-mehr-Zeiger/idi-p/604183) | 1995-03-14 | 78 |
| 7 | [avery-zweckform.com](https://www.avery-zweckform.com/?srsltid=AYCX9vIAgWAfF8biXfkiOVWM-dQjR1VkE3R0gcOCi6yDANTxI-vvuqhP) | 1998-10-27 | 63 |
| 8 | [ardmediathek.de](https://www.ardmediathek.de/video/story/truegerische-etiketten-chinas-modemafia-in-europa/wdr/Y3JpZDovL3dkci5kZS9CZWl0cmFnLXNvcGhvcmEtZjA0MWFiNjctMjgxNi00MGRiLTlhMmMtNTVkNWU3M2JhNDgx) | 未找到 | 90 |
| 9 | [youtube.com](https://www.youtube.com/watch?v=ZuokOW_32jk) | 2005-02-15 | 99 |
| 10 | [libreoffice.org](https://ask.libreoffice.org/t/mehrere-seiten-bei-etiketten-vorlage/40800) | 2010-08-13 | 88 |
### FR · générateur étiquettes CLP bougies

含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [creacire.com](https://etiquette-clp.creacire.com/) | 2023-04-01 | 27 |
| 2 | [terre-de-bougies.com](https://www.terre-de-bougies.com/blogs/news/partenariat-avery-etiquette-bougie?srsltid=AYCX9vLo4FRzvdPBUoDNACjkZpowUrEnyPDlovFhRcgGNOM2RX0YnfZq) | 2012-03-09 | 40 |
| 3 | [candle-shack.com](https://candle-shack.com/fr/pages/clp-label-design-tool?srsltid=AYCX9vLwqw1p2WQzNdoT-R_LYBfI5MCngneGqD7RSUsuVtQAumuST8CB) | 2021-02-21 | 26 |
| 4 | [avery.fr](https://www.avery.fr/impression/etiquettes-personnalisees/clp) | 1999-08-16 | 50 |
| 5 | [etiqazur.com](https://etiqazur.com/blog/etiquettes/etiquette-clp-bougie) | 2000-10-03 | 5 |
| 6 | [youwish.nl](https://www.youwish.nl/fr/fabrication-de-bougies/creer-une-etiquette-clp/?srsltid=AYCX9vJOQfaIfTAvISCOJlCXutUGfGqN-Q6xDMCPirzKP6s0SumTNWYC) | 2009-12-08 | 28 |
| 7 | [formacire.com](https://www.formacire.com/) | 2026-03-21 | 4 |
| 8 | [pro-candles.com](https://pro-candles.com/blogs/les-actualites/etiquette-clp-bougie-mentions-obligatoires?srsltid=AYCX9vJaU2iNQGHyeXaeuxAALzQB-ZROY0oLbOTY5lKIwb-1GMsl0YwP) | 2025-06-03 | 5 |
### ES · generador etiquetas CLP velas

含相关页面但混合模板/印刷/指南/工具；样本10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [luxurycandlesupplies.eu](https://luxurycandlesupplies.eu/es/producto/impresion-de-etiquetas-clp/) | 未找到 | 5 |
| 2 | [avery.es](https://www.avery.es/blog/normativa-clp?srsltid=AYCX9vJajRzpe9IHa4DNSINYtPfrgyhiF5-m1dmAgjO7OWN4q30T106J) | 未找到 | 31 |
| 3 | [youwish.nl](https://www.youwish.nl/es/haciendo-velas/crear-etiqueta-clp/?srsltid=AYCX9vJj21wrdvRBq527Tf3qz5yvOEaSvsBNvW03kFD0DIEXvxiWothQ) | 2009-12-08 | 28 |
| 4 | [terre-de-bougies.com](https://www.terre-de-bougies.com/es/blogs/guias-y-recetas/bonos-venta-velas-fundidos?srsltid=AYCX9vJle9BAKugIqVTmKln0RbiXGugg1ZVBVeIbxojksS0Zj-PWfWR3) | 2012-03-09 | 40 |
| 5 | [cosyowl.com](https://cosyowl.com/es/guias/etiquetado-clp-lo-que-hay-que-saber?wmc-currency=EUR) | 2017-10-27 | 46 |
| 6 | [perlesandco.es](https://www.perlesandco.es/recursos/ft30181-normativa-y-obligaciones-relacionadas-con-la-venta-de-velas.html) | 未找到 | 21 |
| 7 | [etsy.com](https://www.etsy.com/es/listing/1019738820/plantilla-de-etiqueta-de-advertencia-de) | 2004-02-05 | 94 |
| 8 | [sdsmanager.es](https://sdsmanager.es/create-secondary-container-label/) | 未找到 | 4 |
| 9 | [nordiik.com](https://nordiik.com/clp/velas-fds/) | 2019-02-22 | 2 |
| 10 | [niimbots.com](https://niimbots.com/es/blogs/news/how-to-make-candle-labels?srsltid=AYCX9vKDskIrzHdzlS4VDTteH5Mqfbkie9jzAAwdZ5JaZHAel6tUrEQi) | 2021-11-03 | 41 |
### IT · generatore etichette CLP candele

含相关页面但混合模板/印刷/指南/工具；样本8条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [monterosawicks.store](https://www.monterosawicks.store/etichette/) | 2020-03-19 | 3 |
| 2 | [avery.it](https://www.avery.it/uso/etichette-candele?srsltid=AYCX9vK41gjTf6Jz-vAT9-beGakId-AdiQff0IsYXEok54H-1pb7PbCt) | 2000-01-23 | 41 |
| 3 | [terre-de-bougies.com](https://www.terre-de-bougies.com/it/blogs/notizia/partenariato-avery-etichetta-candela?srsltid=AYCX9vIz8j8eCQvUVpcDA0LMlBp0xSoRO5U9wLoDeKk2jKvP8SZZX4IM) | 2012-03-09 | 40 |
| 4 | [hobbyland.eu](https://crea.hobbyland.eu/le-etichette-per-le-candele-secondo-la-nuova-normativa-europea-guida-completa/) | 未找到 | 31 |
| 5 | [testo-unico-sicurezza.com](https://www.testo-unico-sicurezza.com/generatore-etichette-clp.html) | 2008-05-03 | 43 |
| 6 | [acnet.it](https://www.acnet.it/2022/06/06/clp-creare-e-stampare-etichette-conformi-per-candele-profumate/) | 2014-10-24 | 8 |
| 7 | [etsy.com](https://www.etsy.com/it/listing/1019772028/etichette-di-avvertenza-per-candele) | 2004-02-05 | 94 |
| 8 | [youwish.nl](https://www.youwish.nl/it/fare-candele/crea-letichetta-clp/?srsltid=AYCX9vILwg662B6-lSaDbC7IKBmD1JJk48H2pl1-lX91xBHMP1OBp2e6) | 2009-12-08 | 28 |
### NL · CLP etiketten maken voor geurkaarsen

含相关页面但混合模板/印刷/指南/工具；样本10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [yinzie.nl](https://yinzie.nl/clp-etiketten-maken/) | 2020-03-31 | 0 |
| 2 | [kaarsenwas.nl](https://www.kaarsenwas.nl/3101683_clp-label-kaarsen-alles-wat-je-moet-weten) | 2023-12-05 | 28 |
| 3 | [avery.nl](https://www.avery.nl/laten-drukken/etiketten/toepassingen/kaarsen?srsltid=AYCX9vKzVyDIySsOMhuWla9V0SGXeHDGoC9rRzG5fZ3pmKykl1n30uJe) | 1997-01-12 | 41 |
| 4 | [luxurycandlesupplies.eu](https://luxurycandlesupplies.eu/nl/product/clp-etiketten-afdrukken/) | 未找到 | 5 |
| 5 | [cosyowl.com](https://cosyowl.com/nl/gidsen/clp-etikettering-wat-u-moet-weten?wmc-currency=EUR) | 2017-10-27 | 46 |
| 6 | [chemischestoffengoedgeregeld.nl](https://chemischestoffengoedgeregeld.nl/de-helpdesk-van-bureau-reach) | 2015-09-15 | 57 |
| 7 | [youwish.nl](https://www.youwish.nl/kaarsen-maken/clp-label-maken/?srsltid=AYCX9vJQyQM9av3Vvmp8cjoMm5PaIStWKYvqB4SqOWrBqdIlXHnhXa7H) | 2009-12-08 | 28 |
| 8 | [danmas.nl](https://danmas.nl/clp-kaarsen-label-uitleg?srsltid=AYCX9vJL-4eGj5Ak-S9JPjWOn4UMzPCJIvoYSeZ-mdNmOdKDJi5g26v2) | 2020-08-24 | 0 |
| 9 | [lunimode.com](https://www.lunimode.com/product/cursus-clp-etiketten-maken-voor-geurkaarsen-en-waxmelts/) | 2026-08-17 | 0 |
| 10 | [tiktok.com](https://www.tiktok.com/@cozydesign.nl/video/7617009647505001761) | 1996-07-21 | 97 |
### JP · キャンドル CLPラベル 作成ツール

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [taobe.consulting](https://taobe.consulting/jp/service/sds/) | 2019-03-22 | 21 |
| 2 | [etsy.com](https://www.etsy.com/jp/market/clp_compliant_label) | 2004-02-05 | 94 |
| 3 | [kojima-label.co.jp](https://www.kojima-label.co.jp/blog/layer-label-clp-regulation/) | 未找到 | 27 |
| 4 | [ufiregistrierung.de](https://ufiregistrierung.de/ja/) | 未找到 | 0 |
| 5 | [reddit.com](https://www.reddit.com/r/candlemaking/comments/t16wfq/creating_sds_for_own_blend_candles/?tl=ja) | 2005-04-29 | 95 |
| 6 | [biorius.com](https://biorius.com/ja/%E3%81%9D%E3%81%AE%E4%BB%96%E3%81%AE%E8%A6%8F%E5%88%B6%E3%82%B5%E3%83%BC%E3%83%93%E3%82%B9/eu%E3%82%AD%E3%83%A3%E3%83%B3%E3%83%89%E3%83%AB%E8%A6%8F%E5%88%B6/) | 2008-10-14 | 55 |
| 7 | [reach24h.com](https://jp.reach24h.com/chemical/industry-news/eu-clp-2025-digital-labels) | 2009-07-23 | 56 |
| 8 | [or.jp](https://www.cerij.or.jp/service/10_risk_evaluation/clp.html) | 未找到 | 39 |
| 9 | [toishi.info](https://www.toishi.info/boueki/clp_label.html) | 2009-06-24 | 47 |
### KR · 캔들 CLP 라벨 생성기

含相关页面但混合模板/印刷/指南/工具；样本9条，不足10条；无SEO优先立项结论

| 排名 | 页面 | 注册日期（供应商快照） | DR（供应商快照） |
|---|---|---|---|
| 1 | [youtube.com](https://www.youtube.com/watch?v=4-Xq0TeKdcM) | 2005-02-15 | 99 |
| 2 | [nicandlesupplies.com](https://www.nicandlesupplies.com/blogs/news-and-updates/what-you-need-to-know-about-clp-labels-for-candles?srsltid=AYCX9vKeN1m0K-I5I-NdwxD49uzpjLuukEYjboteuUKnndrDQyhGB_D4) | 2017-10-28 | 27 |
| 3 | [labelic.com](https://labelic.com/ko/label-hwahak) | 2026-03-01 | 0 |
| 4 | [casscale.net](https://casscale.net/clp-label-printer-scale-related-delivery-case-collection/) | 2018-07-31 | 10 |
| 5 | [luxurycandlesupplies.co.uk](https://www.luxurycandlesupplies.co.uk/fragrance-oils/clp-label-maker.html) | 2018-05-22 | 35 |
| 6 | [naver.com](https://m.blog.naver.com/mipy228/221559504721) | 1997-09-12 | 93 |
| 7 | [candle-shack.co.uk](https://candle-shack.co.uk/pages/clp-label-design-tool) | 2010-07-22 | 37 |
| 8 | [pinterest.com](https://www.pinterest.com/pin/free-clp-label-design-template--441352832249199217/) | 2009-11-26 | 97 |
| 9 | [canva.com](https://www.canva.com/ko_kr/labels/templates/) | 2001-05-05 | 93 |

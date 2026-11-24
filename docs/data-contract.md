# 資料約定

這些內容是本地合成演練資料，不代表真實人物、機構、作品或交易。原始值按來源記錄；空值和待核狀態表示尚未確認，不等同否定、零或已完成。

藝術檔案目錄、研究需求、限制和整理批次資料。

- `collections.csv`：欄位 `collection_id, holding_unit, material_type, box_count, condition, rights_state`。
- `research_needs.csv`：欄位 `need_id, project, question, collection_id, priority_source, required_by`。
- `work_estimates.csv`：欄位 `collection_id, catalog_hours, scan_hours, preservation_hours, equipment, staff_group`。
- `batches.csv`：欄位 `batch_id, collection_id, state, approved_budget, planned_hours, open_access_scope`。

同一標識只在其對應資料域內使用；版本、時間和狀態欄位保留各自來源含義。

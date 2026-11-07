# Final pool — implemented tasks

All tasks marked **implemented** in the Notion **Task Tracker** ("Task Status Table") are collected here under `tasks/finalpool/<task-name>/`.
Files are copied unchanged from the developer branch that owns each task.

**77 tasks / 385 files.**

## Review basis

Reviewed the most recent task-adding commit on each of the 14 developer branches.
Requirements come from `tasks/examples/example-task`: `docs/task.md` and `docs/agent_system_prompt.md` must exist, be non-empty and be entirely English; the optional user prompt must also be English when present. The remaining task structure (preprocess, evaluation, initial/groundtruth workspaces) is checked for file existence.

Newly reviewed tasks: **29** → **23 implemented**, **6 implementing**.

Still `implementing`, therefore excluded from this pool:

| Task | Developer | Reason |
| --- | --- | --- |
| sitemap-generator | gyy | missing `evaluation/main.py` |
| customer-portal | junteng_dev | missing `evaluation/main.py` |
| currency-converter | junxian_dev | Chinese section in `docs/task.md` |
| insights-engine | lv | Chinese section in `docs/agent_system_prompt.md` |
| audit-logger | yuzhen-dev | Chinese section in `docs/agent_system_prompt.md` |
| resource-monitor | yuzhen-dev | Chinese section in `docs/agent_system_prompt.md` |

Note: `yuxuan-dev` also committed unnamed task scaffolding directly under `tasks/yuxuan/` (empty task name, no task docs/evaluation). Those malformed files were not treated as a task; `sync-service` from that commit is included below.

## Included tasks by source branch

- **fan-dev**: `coupon-manager`, `discount-calculator`, `loyalty-program`, `price-tracker`
- **gyy**: `blog-engine`, `cms-builder`, `content-scheduler`, `robots-handler`, `social-publisher`, `tag-manager`
- **haoze**: `media-organizer`, `streaming-service`, `subtitle-generator`, `video-trimmer`
- **jl_dev**: `canvas-grade-automation`, `customer-feedback-processor`, `email-classification-system`, `inventory-management`, `pdf-report-generator`
- **junteng_dev**: `booking-system`, `calendar-sync`, `contact-manager`, `help-desk`, `order-processor`, `product-catalog`, `reminder-service`, `shipment-tracker`
- **junxian_dev**: `qr-generator`, `social-connector`, `translation-api`
- **lueyang-dev**: `activity-logger`, `client-portal`, `crm-system`, `deal-manager`, `email-campaign`, `follow-up-reminder`, `sales-pipeline`, `territory-manager`
- **lv**: `analytics-dashboard`, `chat-bot`, `feedback-collector`, `personalization-service`, `sentiment-analyzer`, `survey-builder`, `voice-processor`
- **ruige**: `canvas-automation`, `data-analytics`, `expense-tracker`, `file-manager`, `log-analyzer`, `web-crawler`
- **wenshuo-dev**: `cache-optimizer`, `image-processor`, `scheduler`, `search-engine`
- **xiaochen_dev**: `backup-utility`, `deployment-tool`, `error-tracker`, `health-monitor`, `monitoring-agent`, `security-scanner`, `status-checker`
- **yuxuan-dev**: `asset-optimizer`, `content-manager`, `network-analyzer`, `sync-service`, `task-scheduler`
- **yuzhen-dev**: `alert-system`, `data-validator`, `form-builder`, `invoice-generator`, `payment-processor`, `permission-manager`
- **zhaochen**: `certificate-manager`, `load-balancer`, `storage-manager`, `template-engine`
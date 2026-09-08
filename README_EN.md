# Personal Work Cockpit

A lightweight, spreadsheet-based personal work-state system designed for **mental offloading, interruption recovery, and next-action prioritization**.

**Stable release: V1.0** · WPS/Excel · no macros · offline-first

The key idea is simple:

> Prioritize the task whose delay by one or two hours would cost the most.

The workbook tracks current work state, who holds the next action, when an item should re-enter your attention, and hard deadlines. Items waiting on others can stay quiet until their follow-up time. Historical events live in a separate work log.

Start with [`template/个人工作驾驶舱_V1.0_空白模板.xlsx`](template/个人工作驾驶舱_V1.0_空白模板.xlsx). For architecture and modification rules, see [`docs/DEVELOPER_GUIDE.md`](docs/DEVELOPER_GUIDE.md) and [`spec/tracker_spec.json`](spec/tracker_spec.json).

## License

Licensed under the [MIT License](LICENSE).

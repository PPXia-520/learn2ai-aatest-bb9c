# AATest

> 这个文件夹就是这门课的课程仓库。老师和学生的 AI 都从这里读取课程约定。

## 目录

- `materials/` — 课程资料（讲义、数据、图片等）
- `assignments/` — 作业，每份作业一个子文件夹：`assignments/<作业ID>/assignment.md`
- `work/` — 学生成果（按学生区分）
- `.learn2ai/feedback/` — 旧版反馈目录；新反馈保存在课程服务中
- `templates/assignment.md` — 出题模板（保留作业 ID，正文自由撰写）

## 历史课资料

本课程按历史课整理教学资料。现有[中国近代史教材与教学资料包](materials/china-modern-history/README.md)，以1840—1949年为主，包含分层书目、十单元学习导读、史料研读卡、大事年表和教学安排。学段及课时尚未明确，资料包暂按高中进阶至大学入门编排，教师可据实际班级调整。

## 约定

1. 资料和作业都通过 AI 对话整理，AI 会用 Git 同步到这门课。
2. 出题时按 `templates/assignment.md` 的格式写进 `assignments/<作业ID>/assignment.md`，并让 AI 登记这次作业。
3. 学生做完后提交成果并确认分享，老师就能在课程里看到这次的学习过程。
4. 资料和作业的手工改动使用应用内保存与发布；学生同步后可见。
5. 老师在提交详情里保存反馈，或让 AI 使用 feedback get / feedback save 命令保存；新反馈无需 Git 推送。

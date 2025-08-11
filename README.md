# Auto Green 使用指南

本项目可以自动为你的 GitHub 贡献图（绿点）每天生成提交记录，实现“每日自动刷绿”。

## 使用流程

### 1. 打开仓库页面
在浏览器访问： https://github.com/new/import

<img width="769" height="933" alt="image" src="https://github.com/user-attachments/assets/0add0f29-f020-4afd-937a-ea0fcf96f874" />

填入：https://github.com/eeSine/autoGreen

等待导入

### 2. 修改 Actions 配置

导入代码后，修改下图两个配置，点击save保存

<img width="2150" height="1285" alt="image" src="https://github.com/user-attachments/assets/52d2586c-82fd-46a6-a33c-b71488c6de26" />

### 3. 配置 CI 文件

仓库中 `.github/workflows/ci.yml` 第19、20行，改为自己的邮箱、用户名

<img width="922" height="457" alt="image" src="https://github.com/user-attachments/assets/f49bf22e-1a4f-49fe-ab47-4a5441fc8ae3" />

已经包含默认的定时任务配置，如需修改运行时间或提交信息，可直接编辑该文件。  

# Day 1 学习记录

## 🚀 今日学习计划回顾  
1. **准备环境**  
   - 下载并配置 GitHub 仓库  
   - 确认学习文件夹路径：  
     ```
     /Users/fanyizhe/Library/Mobile Documents/com~apple~CloudDocs/N2O-X/个人/tradingview/4.github/learning
     ```  

2. **建立学习仓库**  
   - 在本地 `learning` 文件夹初始化 Git  
   - 创建 GitHub 仓库并完成第一次推送  

3. **策略编写与运行**  
   - 在 TradingView（Plus 版）里新建 Pine Script 文件  
   - 编写了 **均线交叉策略**：  
     - 快速均线：9  
     - 慢速均线：21  
   - 添加了买卖箭头信号  

4. **币种回测**  
   - 运行 `SOLUSDT`，观察策略表现  
   - 运行 `ETHUSDT`，对比结果（ETH 更优）  
   - 尝试选择「过去 7 天」范围，但 Plus 版受限，只能用图表可见范围  

5. **总结心得**  
   - 学会了 GitHub 的同步流程  
   - 在 TradingView 中成功写了第一个策略  
   - 注意到：同一策略在不同币种上表现不同，ETH 的趋势更清晰  
   - 受限于 Plus 版，暂时不能自由选择「过去 7 天」回测  

---

## 📌 GitHub 上传步骤  
在 `learning` 文件夹下运行：  

```bash
git add day1.md
git commit -m "Day 1 学习记录：下载环境 + 策略编写 + 回测"
git push origin main

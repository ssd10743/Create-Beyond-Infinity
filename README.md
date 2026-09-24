# Create: Beyond Infinity
![alt text](Create_Beyond_Infinity.png)

## JVM設置
推薦按照以下JVM設定進行啟動
```powershell
-XX:+UseG1GC -XX:+ParallelRefProcEnabled -XX:MaxGCPauseMillis=200 -XX:+UnlockExperimentalVMOptions -XX:+AlwaysPreTouch -XX:G1NewSizePercent=30 -XX:G1MaxNewSizePercent=40 -XX:G1ReservePercent=15 -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=4 -XX:InitiatingHeapOccupancyPercent=15 -XX:G1MixedGCLiveThresholdPercent=90 -XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32 -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1
```
## 已知問題
AeroEngine的大型發動機風扇無法正常渲染，目前確定是IRIS所導致


所有模組皆來自於Modrinth、CurseForge與Github
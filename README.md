# Create: Beyond Infinity
![alt text](Create_Beyond_Infinity.png)

## 記憶體設置
最小記憶體用量推薦設置為1024MB

最大記憶體用量推薦設置為8192MB

## JVM設置
推薦按照以下JVM設定進行啟動
```powershell
-XX:+UseZGC -XX:+ZGenerational -XX:+PerfDisableSharedMem
```
## 已知問題
1.AeroEngine的大型發動機風扇無法正常渲染，目前確定是IRIS所導致

2.在高頻率的創建世界時，會遇到 Voxy World Gen 與 C2ME 產生衝突而引發遊戲崩潰


所有模組皆來自於Modrinth、CurseForge與Github
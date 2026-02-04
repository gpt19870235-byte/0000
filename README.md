# GCodeChecker

這個專案用 GitHub Actions 在 Windows 上打包成單一 EXE（Windows 不用裝 Python 也能直接開）。

## 產出 Windows EXE
1. 把整個專案 push 到你的 GitHub repo
2. GitHub → Actions → **Build Windows EXE**
3. 點 **Run workflow** → 再按一次 **Run workflow**
4. 跑完（綠色 ✅）→ 進入該次 run → 下方 **Artifacts**
5. 下載 **gcode_checker_windows_exe** → 解壓 → 執行 `GCodeChecker.exe`

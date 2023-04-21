**Android自動化測試程式（Python版）**
運行環境：
- appium server
- python3
- pytest
- git

配置文件：iAppium_python.json
- 將配置文件複制到本地磁盤
- 填入設備的 deviceName 與 udid


運行命令:
pytest -v test/cm_test.py --tc-file /full_path/iAppium_python.json --tc-format json

C:\iAppium_python_cp2> pytest -v test/cm_test.py --tc-file /iAppium_python_cp2/iAppium_python.json --tc-format json
<a href="https://colab.research.google.com/github/JeffersonQin/gdrive-integrity-checker/blob/master/checker.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

# Google Drive File Integrity Checker

本工具可以检查 Google Drive 上传的文件的完整性。

步骤：

1. 本地使用 7-zip 输出 SHA256 文件
2. 使用 `check(hash_file)` 进行校验

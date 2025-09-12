## 檔案與目錄操作

### 1. `ls` — 列出目錄內容

```bash
ls
ls -l       # 顯示詳細資訊 (long format) ls -a
ls -a       # 顯示所有檔案（包含隱藏檔）`
```

---

### 2. `cd` — 切換目錄

```bash
cd /home/user         # 切換到指定路徑 
cd ..                 # 回到上層目錄 
cd ~                  # 回到家目錄
```

---

### 3. `pwd` — 顯示目前所在目錄

```bash
pwd
```

---

### 4. `mkdir` — 建立新目錄

```bash
mkdir new_folder 
mkdir -p folder1/folder2  # 建立多層資料夾`
```

---

### 5. `rm` — 刪除檔案或目錄

```bash
rm file.txt 
rm -r folder_name     # 刪除資料夾及其內容 
rm -f file.txt        # 強制刪除
```
---

### 6. `cp` — 複製檔案或資料夾

```bash
cp file1.txt file2.txt              # 複製檔案 
cp -r folder1/ folder2/             # 複製資料夾`
```
---

### 7. `mv` — 移動或重新命名檔案

```bash
mv file.txt /home/user/Documents/   # 移動檔案 
mv oldname.txt newname.txt          # 重新命名`
```
---

### 8. `touch` — 建立空檔案

```bash
touch newfile.txt`
```
---

##  系統相關指令

### 9. `clear` — 清除螢幕內容

```bash
clear
```
---

### 10. `whoami` — 顯示目前登入的使用者

`whoami`

---

### 11. `uname` — 顯示系統資訊

`uname -a    # 顯示所有系統資訊`

---

### 12. `top` — 顯示系統即時執行狀況

`top`

---

##  檔案查看與編輯

### 13. `cat` — 查看檔案內容

`cat file.txt`

---

### 14. `more` / `less` — 分頁查看長檔案

```bash
less bigfile.txt 
more bigfile.txt`
```
---

### 15. `nano` — 簡單文字編輯器

`nano file.txt`

---

##  搜尋與權限

### 16. `find` — 搜尋檔案

`find / -name "file.txt"`

---

### 17. `grep` — 文字搜尋

`grep "keyword" file.txt`

---

### 18. `chmod` — 改變檔案權限

`chmod 755 script.sh`

---

### 19. `chown` — 改變檔案擁有者

`chown user:group file.txt`

---

##  套件與程式

### 20. `apt`（Ubuntu/Debian 系統）— 套件管理

```bash
sudo apt update 
sudo apt install 
git
```


在 Linux 中，執行 `ls -l` 會列出目錄中的檔案詳細資訊。最左邊那一串字符（例如：`-rw-r--r--`）代表 **檔案的權限與類型資訊**，總共有 **10 個字符**，各有特定意義。

---

###  範例說明

```bash
-rw-r--r--
```

這 10 個字元可以拆解成以下部分：

| 位置  | 字元範圍   | 意義說明                                |
|--------|------------|------------------------------------------|
| 第 1 位 | `-`        | **檔案類型**                            |
| 第 2–4 位 | `rw-`    | **檔案擁有者（user）的權限**           |
| 第 5–7 位 | `r--`    | **同群組使用者（group）的權限**        |
| 第 8–10 位 | `r--`   | **其他使用者（others）的權限**         |

---

##  詳細說明

### 第 1 位：檔案類型
| 字元 | 類型         |
|------|--------------|
| `-`  | 一般檔案     |
| `d`  | 目錄         |
| `l`  | 符號連結（類似捷徑） |
| `b`  | 區塊裝置檔案 |
| `c`  | 字元裝置檔案 |
| `s`  | 套接字 (socket) |
| `p`  | 管道 (pipe)  |

---

### 第 2–10 位：權限（每 3 位一組）

| 權限代碼 | 說明                   |
|----------|------------------------|
| `r`      | 讀取（read）           |
| `w`      | 寫入（write）          |
| `x`      | 執行（execute）        |
| `-`      | 無此權限               |

#### 例子拆解：
```bash
-rw-r--r--
```

- `-`：一般檔案
- `rw-`：擁有者可讀寫，無執行權限
- `r--`：群組只能讀取
- `r--`：其他人只能讀取

---

##  補充特殊權限（進階可略過）

在某些情況下，會看到像這樣的：
```bash
-rwsr-xr-x
drwxr-sr-x
-rwxrwxrwt
```

這些中有 `s`, `t` 等特殊權限，代表：

| 字元 | 含意                       |
|------|----------------------------|
| `s`  | setuid 或 setgid（設定 UID/GID） |
| `t`  | sticky bit（通常用在 `/tmp`） |

---

需要我幫你做「權限表練習題」或是「如何用 chmod 設定這些權限」的教學嗎？我可以幫你設計練習。

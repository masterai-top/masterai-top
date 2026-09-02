[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

# MasterAI 德州遊戲原始碼、德州俱乐部、德州金币大厅、撲克 AI 與周易占卜軟體專案導覽

MasterAI 開發並整理德州撲克平台、德州積分大廳、 撲克賽事系統、CFR 撲克 AI、多人釣魚遊戲及中國傳統文化軟體。
每個專案的功能、技術堆疊、運作條件和授權範圍以對應倉庫的程式碼與文件為準。


MasterAI develops and documents Texas Hold'em platforms, poker tournament systems, CFR poker AI, multiplayer fishing games and Chinese metaphysics software.


## 核心專案 | Featured Projects


| 專案 | 主要內容 | 技術方向 |

| --- | --- | --- |

| [德州撲克完整解決方案](https://github.com/masterai-top/TexasHoldem-Poker-Complete-Solution) | 俱樂部、私人房、好友局、SNG 與 MTT 流程 | Unity、C++ |

| [德州撲克賽事平台](https://github.com/masterai-top/Texas-Holdem-Poker-Tournament-Event-Platform) | 報名、牌桌、排名與錦標賽流程 | C++、Tars |

| [德州積分大廳](https://github.com/masterai-top/Texas-Hold-em-Points-Lobby) | 德州積分大廳、金幣大廳、俱樂部、聯盟、朋友局、SNG、MTT 和配套營運模組 | Unity、C++ |

| [CFR 德州撲克 AI](https://github.com/masterai-top/cfr-poker-ai-masterai) | CFR 策略訓練、評估與博弈研究 | C++ |

| [OceanRaid 釣魚遊戲平台](https://github.com/masterai-top/OceanRaid-Fishing-Game-Platform) | 用戶端、遊戲服務、比賽模式與營運後台 | Cocos/Lua、Python/C++、Node.js |

| [八字、紫微與奇門排盤系統](https://github.com/masterai-top/Bazi-Ziwei-Qimen-Dunjia-Divination-System-Source-Code) | 八字、紫微鬥數、奇門遁甲及相關排盤流程 | JavaScript |


## 德州撲克平台 | Texas Hold'em Platform


德州撲克主倉庫記錄 Unity 用戶端與 C++ 服務端相關模組，並涵蓋俱樂部、牌桌、好友局、SNG 和 MTT 等產品流程。
實際部署前請獨立驗證依賴、效能、安全性和合規性要求。
<table>
  <tr>
    <td width="50%"><img src="https://raw.githubusercontent.com/masterai-top/TexasHoldem-Poker-Complete-Solution/main/Screenshots/%E5%88%9B%E5%BB%BA%E4%BF%B1%E4%B9%90%E9%83%A8.jpg" alt="德州扑克俱乐部创建界面 Texas Hold'em poker club creation" width="100%"></td>
    <td width="50%"><img src="https://raw.githubusercontent.com/masterai-top/TexasHoldem-Poker-Complete-Solution/main/Screenshots/MTT%E8%B5%9B%E4%BA%8B.jpg" alt="德州扑克 MTT 锦标赛界面 Texas Hold'em MTT tournament" width="100%"></td>
  </tr>
</table>
- [查看德州撲克完整方案](https://github.com/masterai-top/TexasHoldem-Poker-Complete-Solution)

- [德州積分廳](https://github.com/masterai-top/Texas-Hold-em-Points-Lobby)

- [查看德州撲克賽事平台](https://github.com/masterai-top/Texas-Holdem-Poker-Tournament-Event-Platform)

- [查看 CFR 撲克 AI](https://github.com/masterai-top/cfr-poker-ai-masterai)


## 德州積分大廳 | Texas Hold'em Points Lobby

德州積分大廳專案涵蓋金幣/積分大廳、俱樂部、聯盟、好友局、SNG、MTT、短牌及多人牌桌相關流程。以下圖片來自該專案目前的線上 README。

<table>
  <tr>
    <td width="50%"><img src="https://github.com/user-attachments/assets/7da76d6b-c7fd-4e36-87e8-61f5bd504438" alt="德州積分大廳與俱樂部介面 Texas Hold'em points lobby and poker club" width="100%"></td>
    <td width="50%"><img src="https://github.com/user-attachments/assets/3dda8ea6-b7d1-4679-8ca1-8469e68b6c97" alt="德州積分大廳九人牌桌 Texas Hold'em nine-player table" width="100%"></td>
  </tr>
</table>

- [查看德州積分大廳專案](https://github.com/masterai-top/Texas-Hold-em-Points-Lobby)

## 德州撲克 AI | CFR Poker AI

MasterAI CFR 專案面向單挑無限注德州撲克策略研究，涵蓋 CFR、反事實價值計算、自我博弈、訓練和評估相關模組。效能與勝率應以可重現實驗和目前版本為準。

<table>
  <tr>
    <td width="50%"><img src="https://github.com/user-attachments/assets/66851632-7b29-4fc3-a35c-76dee4e5930d" alt="MasterAI 德州撲克 AI 運行介面 MasterAI poker AI interface" width="100%"></td>
    <td width="50%"><img src="https://github.com/user-attachments/assets/8cba978a-8a2f-4310-b650-d96adf1dd633" alt="德州撲克 AI 策略視覺化 Texas Hold'em AI strategy visualization" width="100%"></td>
  </tr>
</table>

- [查看 CFR 德州撲克 AI 專案](https://github.com/masterai-top/cfr-poker-ai-masterai)

## 釣魚遊戲平台 | Arcade Fishing Platform


OceanRaid 專案記錄 Cocos/Lua 用戶端、Python/C++ 服務端、Node.js 營運介面及捕魚比賽相關頁面。
圖片來自項目目前公開截圖目錄。
<table>
  <tr>
    <td width="50%"><img src="https://raw.githubusercontent.com/masterai-top/OceanRaid-Fishing-Game-Platform/main/docs/assets/screenshots/lobby.png" alt="OceanRaid 多人捕鱼游戏大厅 multiplayer fishing game lobby" width="100%"></td>
    <td width="50%"><img src="https://raw.githubusercontent.com/masterai-top/OceanRaid-Fishing-Game-Platform/main/docs/assets/screenshots/tournament-mode.png" alt="OceanRaid 多人捕鱼比赛模式 arcade fishing tournament" width="100%"></td>
  </tr>
</table>
- [查看 OceanRaid 釣魚遊戲平台](https://github.com/masterai-top/OceanRaid-Fishing-Game-Platform)


## 週易與命理軟體 | Chinese Metaphysics Software


綜合命理倉庫涵蓋八字、紫微鬥數、奇門遁甲及相關排盤展示。
內容用於軟體與傳統文化演算法研究，不應取代醫療、法律、財務或其他專業建議。
<table>
  <tr>
    <td width="50%"><img src="https://raw.githubusercontent.com/masterai-top/Bazi-Ziwei-Qimen-Dunjia-Divination-System-Source-Code/main/Screenshots/baizhipaipan.png" alt="八字排盘软件界面 Bazi Four Pillars chart" width="100%"></td>
    <td width="50%"><img src="https://raw.githubusercontent.com/masterai-top/Bazi-Ziwei-Qimen-Dunjia-Divination-System-Source-Code/main/Screenshots/wuxing.png" alt="五行分析软件界面 Five Elements analysis" width="100%"></td>
  </tr>
</table>
- [查看綜合命理排盤系統](https://github.com/masterai-top/Bazi-Ziwei-Qimen-Dunjia-Divination-System-Source-Code)

- [查看瀏覽器端週易排盤項目](https://github.com/masterai-top/Zhouyi-Divination-System-Source-Code)


## 下載與文件 | Downloads and Documentation


- [全部公開倉庫](https://github.com/masterai-top?tab=repositories)

- [MasterAI 專案網站](https://masterai-top.github.io/masterai-top/)

- 版本化下載應從對應專案的 GitHub Releases 頁面取得。

- 使用前請閱讀對應項目的 README、LICENSE、SECURITY 和已知限制。


## License and Responsible Use


各倉庫的許可證可能不同。
在使用、修改、散佈或部署前，請檢查對應倉庫的 `LICENSE`、第三方依賴和素材授權，並遵守所在地法律及平台規則。


Licenses may differ by repository. Review the applicable license, third-party notices and local requirements before use, modification, redistribution or deployment.


每個倉庫分別說明公開原始碼範圍、依賴、支援平台和授權。
商業部署、第三方資源、支付、遊戲規則、隱私、非法人保護及地區合規要求需依項目個別審查。
公開文件不取代書面商業協議和技術驗收清單。


## 聯絡方式

電報：@xuzongbin001

電子郵件：masterai918@gmail.com

網址：https://masterai-top.github.io/masterai-top/

核心方向：德州原始碼、德州大廳、德州賽事平台、德州俱樂部、德州AI、釣魚遊戲原始碼、週易軟體。

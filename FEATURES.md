
# Implementation Reference

Apps compliant with the **PhotoDiary Standard (PDS)** should include the following core features:

### 1. Record & Parsing
* **Mandatory Binding**: Each diary entry must be bound to at least one photo (supports both real-time capture and photo selection).
* **Live Read/Write**: The App itself does not maintain a private database for diary content. It should operate entirely based on real-time parsing and writing of photo EXIF metadata.

### 2. Presentation Dimensions
* **Timeline View**: Display photos and diary entries in chronological order.
* **Calendar View**: Display diary thumbnails within calendar cells for a monthly/daily overview.

### 3. Offline Support
* **Offline Operation**: Core functionalities must be fully operational without an internet connection.
* **Zero Upload Policy**: No user content data should be uploaded to any server, with the exception of basic, anonymized analytical data (if applicable).



# 功能实现参考

符合 PDS 标准的 App 应当具备以下核心功能：

### 1. 记录与解析
* **强制绑定**：每篇日记必须绑定在至少一张照片上（支持现拍或选图）。
* **即读即写**：App 本身不建立数据库存储日记内容，完全基于对照片 EXIF 信息的实时解析与写入。

### 2. 展示维度
* **时间轴视图**：按时间顺序排列照片和日记。
* **日历视图**：在日历单元格中展示当天的日记缩略图。

### 3. 离线支持
* **断网运行**：基本功能必须在无网络环境下完全可用。
* **零上报**：除统计分析数据外，不应上报任何用户内容数据。



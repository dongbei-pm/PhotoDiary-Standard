# PhotoDiary-Standard
A universal, decentralized standard for storing diary entries within photo EXIF metadata. "Keep your memories where your photos are."


# PhotoDiary Standard (PDS)

> **"Write your diary on the back of your photos."** —— As long as the photo exists, your memories will never be lost.

## 🌟 Project Vision
In the era of mobile internet, user data is often trapped within the proprietary servers of various apps. If an app stops its service, the user's precious diary entries often vanish forever.

**PhotoDiary Standard (PDS)** aims to establish a universal "Photo Diary" standard, much like Markdown:
* **Data Decoupling**: Content is completely decoupled from the App. Any application following this standard can seamlessly read and write your diary.
* **Decentralized**: No dependency on central servers or cloud storage providers.
* **Permanence**: By utilizing EXIF metadata to store text, PDS achieves the concept of "Data as a File."

## 🚀 Core Features
* **Serverless Architecture**: Apps act solely as parsers and writers, resulting in zero marginal operational costs.
* **Privacy by Design**: Supports offline operation and Zero-Knowledge encryption.
* **Anti-Deletion Mechanism**: Implements specific tags within metadata to prevent accidental deletion during photo library cleanup.


## 📖 Quick Start
Developers can refer to [SPECIFICATION.md](./SPECIFICATION.md) for detailed information on data structures and storage specifications.




# PhotoDiary Standard (PDS) | 照片日记标准

> **“把日记写在照片背面。”** —— 只要照片不丢，日记就不会丢。

## 🌟 项目愿景
在移动互联网时代，用户的数据往往被困在各个 App 的服务器中。一旦 App 停止服务，用户的日记数据往往会随之消失。

**PhotoDiary Standard (PDS)** 旨在建立一种像 Markdown 一样通用的“照片日记”标准：
* **数据脱钩**：数据与 App 完全解耦，任何遵循此标准的 App 都可以读取、写入日记。
* **去中心化**：不依赖服务器，不依赖云存储。
* **永久性**：利用照片的 EXIF 元数据存储文本，实现“数据即文件”。

## 🚀 核心特性
* **无服务器化**：App 仅作为解析器和写入器，运营边际成本为 0。
* **隐私保护**：支持断网运行，支持零知识加密。
* **防误删机制**：在照片元数据中添加特定标记，防止用户清理相册时误删。

## 📖 快速开始
开发者可以通过阅读 [SPECIFICATION.md](./SPECIFICATION.md) 来了解具体的数据结构和存储规范。

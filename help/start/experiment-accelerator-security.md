---
solution: Journey Optimizer
product: journey optimizer
title: Journey Optimizer Experimentation Accelerator
description: 透過Journey Optimizer Experimentation Accelerator在AI中使用資料
topic: Content Management
role: User
level: Beginner
keywords: 內容，實驗，多個，客群，處理
TQID: https://experienceleague.adobe.com/FaQ5-cPzhnIplEoL1HwVh390jot-EA8G5u6JP8CVneI
product_v2:
  - id: cb954087-f4fc-4456-afb9-e939cabcdc79
feature_v2:
  - id: b3538224-471e-4c63-a444-9b19d89ae29c
  - id: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04
  - id: dc22c819-3f29-4e91-8b7d-5c6719831141
subfeature_v2:
  - id: fb9a80eb-bebc-492f-a0e9-584595621ebb
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2:
  - id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
  - id: bcc5edb5-84c3-4940-9f84-ed88b6c16274
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
  - id: eb30f47f-d87a-400f-8f78-63ce7979ff56
source-git-commit: 659a4723ac8b7cbaf3ea06c34107bf876612ccb4
workflow-type: tm+mt
source-wordcount: 441
ht-degree: 2%

---

# 透過Journey Optimizer Experimentation Accelerator在AI中使用資料{#experiment-accelerator-security}

**Adobe Journey Optimizer Journey Optimizer Experimentation Accelerator**&#x200B;可讓您自動探索深入見解，並推薦機會以改善您的實驗與實驗計畫。 解決方案利用AI和機器學習來提供這些建議。 此陳述式說明您客戶的資料在&#x200B;**Journey Optimizer Experimentation Accelerator**&#x200B;中的使用方式。

## Journey Optimizer Experimentation Accelerator使用哪些資料？

目前&#x200B;**Journey Optimizer Experimentation Accelerator**&#x200B;使用的資料型別有三種：

* **實驗中繼資料**：實驗名稱、實驗中所使用對象的定義，以及實驗中的處理，例如名稱、分割百分比、提供實驗的位置或表面。

* **處理的效能**：人數、成功量度的平均值以及每個處理的標準差。

* **處理的內容**：呈現的HTML和處理的熒幕擷圖，如同使用者在您網站上看到的畫面。

## Journey Optimizer Experimentation Accelerator會如何處理這些資料？

**Journey Optimizer Experimentation Accelerator**&#x200B;會取得每項處理的內容，並建立內嵌（即內容的數學表示），然後將這些內嵌與處理的效能相互關聯。 此程式可擷取表現最佳以供日後使用的內容屬性。 這些屬性接著會傳入由Adobe託管的大型語言模型，再轉換為人類可讀的陳述式，用來產生深入見解及建議商機。

## Journey Optimizer Experimentation Accelerator對所使用的資料有何限制？

每個客戶都會指派至特定的組織和沙箱。 每個沙箱都會培訓專屬的模型。 刪除沙箱時，所有相關的資料、訊號和模型都會永久移除。

* 我們只會使用客戶資料來訓練或微調該客戶的模型。

* 我們絕不會混合客戶來訓練或微調模型。

## Adobe模型或AI會自動變更品牌的使用者體驗嗎？

不可以。 **Journey Optimizer Experimentation Accelerator**&#x200B;僅提供可變更的專案及變更方式的建議。 只有有權使用Journey Optimizer或Target變更體驗的使用者才能根據這些建議採取行動。 所有建議都可以在推出前進行檢閱和編輯。

## 他們的資料或系統穩定性是否有任何風險？

**Journey Optimizer Experimentation Accelerator**&#x200B;僅擷取和分析資料，產生見解和建議以供未來測試。 無法修改任何測試設定。 工具內產生的所有建議都會傳送至Target和Journey Optimizer進行實作，確保對客戶的目前活動沒有影響。

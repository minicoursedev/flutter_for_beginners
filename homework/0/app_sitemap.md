# App SiteMap

![AppSiteMap](../../imgs/app_sitemap.png)

```mermaid
flowchart TD
    A[開始頁面] --> B[主頁面] --> 隨機頁面
    
    subgraph menu [主選單]
        direction TB
        C
        D
        E
    end
    B --> menu  
    menu --> 底層導覽列

```
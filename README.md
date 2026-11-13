# 許詮個人網站 部署說明

1. 把 index.html、robots.txt、sitemap.xml 裡的 `https://YOUR-DOMAIN.com` 換成你的正式網址
   （macOS / Linux 終端機：`sed -i '' 's#https://YOUR-DOMAIN.com#https://你的網域#g' index.html robots.txt sitemap.xml`；
    Windows 可用記事本「取代全部」）。
2. 依照對話中的步驟推到 GitHub，再用 Vercel 匯入。

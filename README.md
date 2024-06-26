<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Seasurfing 后端</font></font></h1><a id="user-content-seatsurfing-backend" class="anchor" aria-label="永久链接：Seatsurfing 后端" href="#seatsurfing-backend"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://github.com/seatsurfing/backend/releases"><img src="https://camo.githubusercontent.com/620fa8a3bbad2cb4b0adc1b2889d5c10ba8b6711f4c2eb7b2fc756302511f55a/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f762f72656c656173652f7365617473757266696e672f6261636b656e64" alt="" data-canonical-src="https://img.shields.io/github/v/release/seatsurfing/backend" style="max-width: 100%;"></a>
<a href="https://github.com/seatsurfing/backend/releases"><img src="https://camo.githubusercontent.com/0f60d5ed71911ba77cc6d8b33ee5a4362b0a026dacb2becf7a91eabce7a30dbd/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f72656c656173652d646174652f7365617473757266696e672f6261636b656e64" alt="" data-canonical-src="https://img.shields.io/github/release-date/seatsurfing/backend" style="max-width: 100%;"></a>
<a href="https://hub.docker.com/r/seatsurfing/backend" rel="nofollow"><img src="https://camo.githubusercontent.com/fe8dd722ede189b84703616c6115eac323cd38176351ca17b775e422de5f4b0d/68747470733a2f2f696d672e736869656c64732e696f2f646f636b65722f762f7365617473757266696e672f6261636b656e64" alt="" data-canonical-src="https://img.shields.io/docker/v/seatsurfing/backend" style="max-width: 100%;"></a>
<a href="https://hub.docker.com/r/seatsurfing/backend" rel="nofollow"><img src="https://camo.githubusercontent.com/73597f6e46314221a06ef4897276a9567dc629400b1ff6e76ce2ceae4fea6c65/68747470733a2f2f696d672e736869656c64732e696f2f646f636b65722f696d6167652d73697a652f7365617473757266696e672f6261636b656e64" alt="" data-canonical-src="https://img.shields.io/docker/image-size/seatsurfing/backend" style="max-width: 100%;"></a>
<a href="https://github.com/seatsurfing/backend/actions"><img src="https://camo.githubusercontent.com/ffcd5fe4b1db3a25e5097bb41bab067a5cb484f830ee86ca97e7c3ac886f8f6c/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f616374696f6e732f776f726b666c6f772f7374617475732f7365617473757266696e672f6261636b656e642f72656c656173652e796d6c3f6272616e63683d6d6173746572" alt="" data-canonical-src="https://img.shields.io/github/actions/workflow/status/seatsurfing/backend/release.yml?branch=master" style="max-width: 100%;"></a>
<a href="https://github.com/seatsurfing/backend/blob/master/LICENSE"><img src="https://camo.githubusercontent.com/ba91e020391fab42eae19e12b68c2beb255dc37969d4b640bef058f29c0315a1/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f7365617473757266696e672f6261636b656e64" alt="" data-canonical-src="https://img.shields.io/github/license/seatsurfing/backend" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Seatsurfing 是一款软件，可让您组织的员工预订座位、办公桌和房间。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此存储库包含后端，其包括：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用 Go 编写的服务器（REST API 后端）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户自助预订网页界面（“预订 UI”），构建为渐进式 Web 应用程序 (PWA)，可安装在移动设备上</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">管理员 Web 界面 (“管理员 UI”)</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">两个 TypeScript/React Web 前端的通用 TypeScript 文件</font></font></li>
</ul>
<p dir="auto"><strong><a href="https://seatsurfing.app" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">访问项目网站以获取更多信息。</font></font></a></strong></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">截图</font></font></h2><a id="user-content-screenshots" class="anchor" aria-label="永久链接：截图" href="#screenshots"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Web 管理界面</font></font></h3><a id="user-content-web-admin-ui" class="anchor" aria-label="永久链接：Web 管理界面" href="#web-admin-ui"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/seatsurfing/backend/master/.github/admin-ui.png"><img src="https://raw.githubusercontent.com/seatsurfing/backend/master/.github/admin-ui.png" alt="Seatsurfing 网页管理界面" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网页预订用户界面</font></font></h3><a id="user-content-web-booking-ui" class="anchor" aria-label="永久链接：网页预订用户界面" href="#web-booking-ui"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/seatsurfing/backend/master/.github/booking-ui.png"><img src="https://raw.githubusercontent.com/seatsurfing/backend/master/.github/booking-ui.png" alt="Seatsurfing 网页预订用户界面" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速参考</font></font></h2><a id="user-content-quick-reference" class="anchor" aria-label="永久链接：快速参考" href="#quick-reference"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维护者：</font></font></strong> <a href="https://seatsurfing.app/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Seatsurfing.app</font></font></a></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取帮助的地方：</font></font></strong> <a href="https://seatsurfing.app/docs/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker 架构：</font></font></strong> <a href="http://hub.docker.com/r/seatsurfing/backend" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">amd64、arm64、arm v7</font></font></a></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">许可证：</font></font></strong> <a href="https://github.com/seatsurfing/backend/blob/master/LICENSE"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPL 3.0</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何使用 Docker 镜像</font></font></h2><a id="user-content-how-to-use-the-docker-image" class="anchor" aria-label="永久链接：如何使用 Docker 镜像" href="#how-to-use-the-docker-image"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.13 版中的重大变化</font></font></h3><a id="user-content-breaking-change-in-version-113" class="anchor" aria-label="永久链接：1.13 版中的重大变更" href="#breaking-change-in-version-113"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">直到版本 1.12，</font></font><code>backend</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker 映像才包含 Booking 和 Admin 界面的所有静态 Web 资源。在版本 1.13 中，我们将 Web 界面与后端服务器分开。因此，您需要分别启动</font></font><code>booking-ui</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>admin-ui</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker 映像。后端有一个集成的 HTTP 代理，它将传入的请求转发到相应的后端。如果您希望使用前置反向代理（例如 Traefik 或 nginx）来</font></font><code>/ui/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">处理</font></font><code>/admin/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请求路由，则可以通过设置环境变量来禁用代理功能</font></font><code>DISABLE_UI_PROXY=1</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开始使用 Docker Compose</font></font></h3><a id="user-content-start-using-docker-compose" class="anchor" aria-label="永久链接：开始使用 Docker Compose" href="#start-using-docker-compose"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>version: '3.7'

services:
  server:
    image: ghcr.io/seatsurfing/backend
    restart: always
    networks:
      sql:
      http:
    ports:
      - 8080:8080
    environment:
      POSTGRES_URL: 'postgres://seatsurfing:DB_PASSWORD@db/seatsurfing?sslmode=disable'
      JWT_SIGNING_KEY: 'some_random_string'
      BOOKING_UI_BACKEND: 'booking-ui:3001'
      ADMIN_UI_BACKEND: 'admin-ui:3000'
      PUBLIC_URL: 'https://seatsurfing.your-domain.com'
      FRONTEND_URL: 'https://seatsurfing.your-domain.com'
  booking-ui:
    image: ghcr.io/seatsurfing/booking-ui
    restart: always
    networks:
      http:
    environment:
      FRONTEND_URL: 'https://seatsurfing.your-domain.com'
  admin-ui:
    image: ghcr.io/seatsurfing/admin-ui
    restart: always
    networks:
      http:
    environment:
      FRONTEND_URL: 'https://seatsurfing.your-domain.com'
  db:
    image: postgres:16
    restart: always
    networks:
      sql:
    volumes:
      - db:/var/lib/postgresql/data
    environment:
      POSTGRES_PASSWORD: DB_PASSWORD
      POSTGRES_USER: seatsurfing
      POSTGRES_DB: seatsurfing

volumes:
  db:

networks:
  sql:
  http:
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="version: '3.7'

services:
  server:
    image: ghcr.io/seatsurfing/backend
    restart: always
    networks:
      sql:
      http:
    ports:
      - 8080:8080
    environment:
      POSTGRES_URL: 'postgres://seatsurfing:DB_PASSWORD@db/seatsurfing?sslmode=disable'
      JWT_SIGNING_KEY: 'some_random_string'
      BOOKING_UI_BACKEND: 'booking-ui:3001'
      ADMIN_UI_BACKEND: 'admin-ui:3000'
      PUBLIC_URL: 'https://seatsurfing.your-domain.com'
      FRONTEND_URL: 'https://seatsurfing.your-domain.com'
  booking-ui:
    image: ghcr.io/seatsurfing/booking-ui
    restart: always
    networks:
      http:
    environment:
      FRONTEND_URL: 'https://seatsurfing.your-domain.com'
  admin-ui:
    image: ghcr.io/seatsurfing/admin-ui
    restart: always
    networks:
      http:
    environment:
      FRONTEND_URL: 'https://seatsurfing.your-domain.com'
  db:
    image: postgres:16
    restart: always
    networks:
      sql:
    volumes:
      - db:/var/lib/postgresql/data
    environment:
      POSTGRES_PASSWORD: DB_PASSWORD
      POSTGRES_USER: seatsurfing
      POSTGRES_DB: seatsurfing

volumes:
  db:

networks:
  sql:
  http:" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这开始...</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一个 PostgreSQL 数据库，其数据存储在 Docker 卷“db”上</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一个公开端口 8080 的 Seatsurfing Backend 实例。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可通过以下后端实例访问的 Seatsurfing Booking UI 实例：:8080/ui/</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可通过以下地址的 Backend 实例访问 Seatsurfing Admin UI 实例：:8080/admin/</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Kubernetes 上运行</font></font></h3><a id="user-content-running-on-kubernetes" class="anchor" aria-label="永久链接：在 Kubernetes 上运行" href="#running-on-kubernetes"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅我们的</font></font><a href="https://docs.seatsurfing.app/kubernetes/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kubernetes 文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境变量</font></font></h2><a id="user-content-environment-variables" class="anchor" aria-label="永久链接：环境变量" href="#environment-variables"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请查看</font></font><a href="https://seatsurfing.app/docs/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以获取有关可用环境变量和进一步指导的最新信息。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">后端</font></font></h3><a id="user-content-backend" class="anchor" aria-label="永久链接：后端" href="#backend"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境变量</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;类型</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;默认</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;描述</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">布尔值</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;0</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发模式，设置为 1 以启用</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公共侦听地址</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;0.0.0.0:8080</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TCP/IP 监听地址和端口</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公共网址</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td>&nbsp;<a href="http://localhost:8080" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://本地主机:8080</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公共 URL</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">前端网址</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td>&nbsp;<a href="http://localhost:8080" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://本地主机:8080</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">前端 URL（通常与公共 URL 匹配）</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ADMIN_UI_BACKEND</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;本地主机：3000</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为管理界面前端提供服务的主机</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预订界面后端</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;本地主机：3001</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 Booking UI 前端提供服务的主机</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">禁用 UI 代理</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">布尔值</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;0</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">禁用管理员和预订 UI 的代理，设置为 1 以禁用代理</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">POSTGRES_URL</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;postgres://postgres:root @ localhost/seatsurfing?sslmode=disable</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PostgreSQL 连接</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JWT_SIGNING_KEY</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">随机字符串</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JWT 签名密钥</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SMTP_主机</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;127.0.0.1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SMTP 服务器地址</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SMTP_端口</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">整数</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;二十五</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SMTP 服务器端口</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SMTP_START_TLS</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">布尔值</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;0</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 SMTP STARTTLS 扩展，设置为 1 以启用</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SMTP_INSECURE_SKIP_VERIFY</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">布尔值</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;0</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">禁用 SMTP TLS 证书验证</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SMTP_身份验证</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">布尔值</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;0</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SMTP 身份验证，设置为 1 以启用</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SMTP_AUTH_USER</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td>&nbsp;</td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SMTP 身份验证用户名</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SMTP_AUTH_PASS</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td>&nbsp;</td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SMTP 认证密码</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SMTP_发件人_地址</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td>&nbsp;<a href="mailto:no-reply@seatsurfing.local"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无回复@seatsurfing.local</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SMTP 发件人地址</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模拟发送邮件</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">布尔值</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;0</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SMTP 模拟，设置为 1 以启用</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打印配置</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">布尔值</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;0</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启动时打印配置，设置为 1 以启用</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">初始化组织名称</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;样本公司</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您的组织名称</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">初始化组织域</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;座位冲浪.local</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您的组织的域</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">初始化组织用户</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;行政</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您组织的管理员用户名</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">初始化组织密码</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;12345678</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您组织的管理员密码</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">初始组织国家</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;德</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贵组织的 ISO 国家/地区代码</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">初始化组织语言</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;德</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您所在组织的 ISO 语言代码</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">已启用组织注册</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">布尔值</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;0</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">允许注册新组织，设置为 1 即可启用</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组织注册域名</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.on.seatsurfing.local</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注册域名后缀</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组织注册管理员</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;行政</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新注册用户的管理员用户名</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组织注册最大用户数</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">整数</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;50</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新组织的最大用户数</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组织注册删除</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">布尔值</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;0</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">允许管理员删除自己的组织</font></font></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">前端（管理界面、预订界面）</font></font></h3><a id="user-content-frontend-admin-ui-booking-ui" class="anchor" aria-label="永久链接：前端（管理界面、预订界面）" href="#frontend-admin-ui-booking-ui"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境变量</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;类型</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;默认</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;描述</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">前端网址</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td><code>req.url</code></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">前端 URL</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">港口</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">整数</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;3000（管理界面），3001（预订界面）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务器的 HTTP 端口</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监听地址</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细绳</font></font></td>
<td></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TCP/IP 监听地址（默认为 NextJS 的</font></font><code>hostname</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置）</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提示</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：在仅支持 IPV6 的 Docker/Podman 环境中运行时，如果前端容器绑定了多个网络接口，则</font></font><code>LISTEN_ADDR</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可能需要设置环境变量，因为 NextJS 默认只绑定到一个网络接口。将其设置为</font></font><code>::</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可绑定到任意地址。</font></font></p>
</article></div>

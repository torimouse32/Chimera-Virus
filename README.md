# Chimera Virus · Character Checkroll

**[中文](#中文) · [日本語](#日本語) · [English](#english)**

---

## 中文

### 奇美拉病毒 · 角色点名簿

一个私人的 OC 档案与灵感管理网站：角色档案、个人自设、世界观、关系图、灵感碎片、图片资料库、辅助工具链接，全部保存在你自己的浏览器里，无需账号，也没有服务器。

#### 功能

| 页面 | 内容 |
| --- | --- |
| 首页 | 极简入口；全局搜索（角色 / 世界观 / 碎片 / 资料库 / 工具）；开场动画与右下角「重播」 |
| 橱窗 | 把写好的内容陈列出来：角色卡、自设卡、世界观。只显示已填写的部分，点开查看大卡，并在这里导出 **图片 / Text / PDF** |
| 个人自设 | 简介；化名（可选细节备注）；人设图以堆叠相片展示，鼠标移上展开，点开可翻阅相册，每张图可加标签与备注 |
| 角色库 | 新建、编辑、删除角色；按模板填写；未上传人设图时用素材占位；档案编号自动生成（如 `OT-11-2026-01`：月份缩写-日-年-当天序号） |
| 世界观 | 大类：现代、古代、原创世界观。角色被分配后，页面才显示对应的大类与分支；分支类型可增加、改名、删除（英文、日文名称可选填，不填则不显示），并可与现代 / 古代自由组合。原创世界观有名称、设定、内容，可添加图片并翻阅相册 |
| 关系 | 多张关系图（按世界观或组别分开）；把角色放进图里并拖动；建立关系并给连线写备注；下方自动生成文字总结；可导出 |
| 灵感碎片 | 纯文字便签放在桌面上，可拖动堆叠、点一下编辑；也可「整齐排列」 |
| 资料库 | 胶片样式的图片框；标签与备注（点「＋」展开）；按标签或关键词搜索 |
| 辅助工具 | 输入网址按回车即加入列表；名称、标签、备注为可选；可按标签分类 |
| 管理员 | 语言（中 / English / 日本語，可单选或组合）；动效；背景音乐（添加、删除、改名、自动播放）；转场音效选择与音量；角色模板编辑器；JSON 备份与导入 |

#### 细节

- **多语言**：界面支持中文、English、日本語，默认中文为主、其他语言以小字显示。你自己填写的内容不会被翻译。
- **角色模板**：默认按「创建角色基础设定表」分组（基础信息、性格、外貌、职业与背景、生活、性相关、其他），可在管理员页的模板编辑器里增删字段与分组、改名、调整顺序。改名会迁移已填内容，删除只是隐藏。
- **声音**：转场音效可选「鸽群飞翔 / 飞走 / 乌鸦叫 / 乌鸦回声」，右上角唱片右边的小喇叭（标注「转场音效」）只控制转场音效，不影响背景音乐。背景音乐在开场动画结束后自动播放，可在管理员页关闭自动播放，或用唱片暂停。浏览器通常要等你第一次点击页面后才允许出声。
- **减少动态效果**：系统设置或管理员页开启后，转场改为短淡入淡出，并跳过开场动画。

#### 数据与隐私

- 数据保存在浏览器的 **IndexedDB**（数据库名 `cv1`）；偏好（语言、音量、开关等）保存在 `localStorage`（键名以 `cv-` 开头）。不会上传到任何服务器。
- 浏览器数据可能被清除，请定期在「管理员 → 数据与备份」导出 JSON。备份包含角色、世界观、碎片、资料库、关系图、工具、个人自设与模板；自定义导入的背景音乐不包含在内。

#### 导出

- **图片**：按页面真实显示截取，默认至少 2 倍分辨率。
- **Text**：纯文本，保留分组与字段顺序，未填写的字段不输出。
- **PDF**：整张图切页后放入 A4。
- 紫色线稿装饰属于 CSS 装饰，不会出现在导出文件里。
- 在 claude.ai 中发布的版本通过平台的下载能力保存；独立部署（本地、GitHub Pages）时使用浏览器的普通下载。

#### 文件结构

```
.
├── index.html   # 整个应用：HTML + CSS + JS + 内嵌的图片与音频
└── README.md
```

#### 素材与版权

素材由作者自行收集，文件名显示多数来自 Pixabay 等素材站。音频包括肖邦《第四叙事曲》钢琴版（背景音乐），以及转场音效 `freesound_community-pigeons-flying`、`lucadialessandro-sweet-transition`、`u_a4gfvwagf1-crow-sound-effect`、`dragon-studio-crow-caw-with-echoing-reverb`。

---

## 日本語

### キメラウイルス · キャラクター点呼簿

オリジナルキャラクター（OC）の設定資料と、思いつきやアイデアを管理するための個人用サイトです。キャラクター設定、自設、世界観、関係図、断片メモ、画像アーカイブ、便利ツールのリンクまで、すべてあなた自身のブラウザ内に保存されます。アカウントもサーバーも不要です。

#### 機能

| ページ | 内容 |
| --- | --- |
| ホーム | シンプルな入口。全体検索（キャラ / 世界観 / 断片 / アーカイブ / ツール）。オープニングと右下の「再生」 |
| ショーケース | 書き込み済みの内容を陳列：キャラカード、自設カード、世界観。入力済みの項目だけを表示し、開くと大きなカードが見られます。**画像 / テキスト / PDF** の出力もここから |
| 自設 | 紹介文、別名義（任意の詳細メモ付き）、キャラ絵は重なった写真で表示。マウスを乗せると広がり、クリックでアルバムとして閲覧。各画像にタグとメモを付けられます |
| キャラ一覧 | キャラの作成・編集・削除。テンプレートに沿って入力。画像が未設定なら素材で代用。整理番号は自動採番（例 `OT-11-2026-01`：月の略称-日-年-その日の連番） |
| 世界観 | 大分類：現代、古代、オリジナル世界観。キャラが割り当てられた分岐だけを表示。分岐の種類は追加・名前変更・削除ができ（英語・日本語名は任意で、未記入なら表示されません）、現代・古代と自由に組み合わせ可能。オリジナル世界観には名前・設定・内容を書け、画像の追加とアルバム閲覧もできます |
| 関係 | 世界観やグループごとに複数の関係図。キャラを置いてドラッグし、関係を作って線にメモを書けます。下に文章でのまとめを自動生成し、出力も可能 |
| 断片メモ | テキストだけの付箋を机の上に置き、ドラッグして重ねられます。クリックで編集、「整列」も可能 |
| アーカイブ | フィルム風の画像フレーム。タグとメモ（「＋」で展開）、タグやキーワードで検索 |
| ツール | URL を入力して Enter で追加。名前・タグ・メモは任意。タグで分類 |
| 管理者 | 言語（中文 / English / 日本語、単一または組み合わせ）、モーション、BGM（追加・削除・名前変更・自動再生）、トランジション音の選択と音量、キャラテンプレート編集、JSON のバックアップと読み込み |

#### 補足

- **多言語**：UI は中文・English・日本語に対応し、既定では中文が主、他の言語は小さな文字で併記します。入力した内容は翻訳されません。
- **キャラテンプレート**：既定は「キャラ基礎設定表」の区分（基本情報、性格、外見、職業と背景、生活、性に関すること、その他）です。管理者ページのテンプレート編集で項目やグループの追加・削除・名前変更・並べ替えができます。名前を変えると入力済みの内容も引き継がれ、削除は非表示になるだけです。
- **サウンド**：トランジション音は「鳩の群れ / 飛び去る / カラスの声 / カラス（エコー）」から選べます。右上のレコードの右にある小さなスピーカー（「トランジション」ラベル付き）はトランジション音だけを切り替え、BGM には影響しません。BGM はオープニング終了後に自動再生され、管理者ページで自動再生をオフにするか、レコードで一時停止できます。ブラウザの仕様上、最初のクリックまで音が出ないことがあります。
- **モーション軽減**：システム設定または管理者ページでオンにすると、遷移は短いフェードになり、オープニングは省略されます。

#### データとプライバシー

- データはブラウザの **IndexedDB**（データベース名 `cv1`）に保存され、設定（言語・音量・スイッチなど）は `localStorage`（キーは `cv-` で始まります）に保存されます。サーバーには一切送信されません。
- ブラウザのデータは消える場合があります。「管理者 → データとバックアップ」から定期的に JSON を書き出してください。バックアップにはキャラ、世界観、断片、アーカイブ、関係図、ツール、自設、テンプレートが含まれます。追加した BGM は含まれません。

#### エクスポート

- **画像**：画面表示どおりに取得し、既定で 2 倍以上の解像度。
- **テキスト**：プレーンテキスト。グループと項目の順序を保ち、未入力の項目は出力しません。
- **PDF**：全体の画像をページに分割して A4 に配置。
- 紫の線画の装飾は CSS による装飾のため、出力ファイルには含まれません。
- claude.ai で公開したバージョンではプラットフォームのダウンロード機能で保存し、独立してホストした場合（ローカル、GitHub Pages）はブラウザの通常のダウンロードを使います。

#### ファイル構成

```
.
├── index.html   # アプリ全体：HTML + CSS + JS + 埋め込みの画像・音声
└── README.md
```

#### 素材と著作権

素材は作者が各自集めたもので、ファイル名からその多くは Pixabay などの素材サイトのものと思われます。音声はショパン「バラード第4番」のピアノ演奏（BGM）と、トランジション音 `freesound_community-pigeons-flying`、`lucadialessandro-sweet-transition`、`u_a4gfvwagf1-crow-sound-effect`、`dragon-studio-crow-caw-with-echoing-reverb` です。

---

## English

### Chimera Virus · Character Checkroll

A private archive for original characters (OCs) and loose ideas: character files, a personal profile, worlds, relation maps, fragment notes, an image archive and a list of useful links. Everything is stored locally in your own browser — no account, no server.

#### Features

| Page | What it does |
| --- | --- |
| Home | A minimal entrance; global search (characters / worlds / fragments / archive / tools); the opening animation and a “replay” link at the bottom right |
| Showcase | Displays what you have written: character cards, the personal card and worlds. Only filled-in parts appear; open an item for the full card. **Image / Text / PDF** export lives here |
| Personal profile | A short description; aliases (with optional detail notes); portraits shown as a stack of photos that fans out on hover and opens as an album. Every picture can carry tags and a note |
| Characters | Create, edit and delete characters using the template; a placeholder image is used when no portrait is uploaded; file numbers are generated automatically (e.g. `OT-11-2026-01`: month code – day – year – daily sequence) |
| Worlds | Three categories: Modern, Ancient and Original worlds. A category or branch only appears once a character is assigned to it. Branch types can be added, renamed and deleted (English / Japanese names are optional and hidden when empty), and combine freely with Modern / Ancient. Original worlds have a name, a setting and content, and can hold images with an album |
| Relations | Multiple relation maps (per world or group); place characters, drag them, create relations and write a note on each line; a text summary is generated below; exportable |
| Fragments | Text-only slips on a desk: drag to move and stack them, click to edit, or tidy them into a grid |
| Archive | Film-strip style image frames; tags and notes (open with “＋”); search by tag or keyword |
| Tools | Type a URL and press Enter to add it; name, tags and notes are optional; filter by tag |
| Admin | Language (中文 / English / 日本語, single or combined), motion, background music (add, delete, rename, autoplay), transition-sound choice and volume, character template editor, JSON backup and import |

#### Details

- **Languages**: the UI supports Chinese, English and Japanese; by default Chinese is primary and the other languages appear as small text. Content you write is never translated.
- **Character template**: groups follow the “basic character sheet” by default (Basic info, Personality, Appearance, Career & background, Daily life, Intimacy, Other). In the admin page’s template editor you can add, delete, rename and reorder fields and groups. Renaming carries filled-in data over; deleting only hides it.
- **Sound**: choose the transition sound from pigeons, whoosh, crow caw or crow echo. The small speaker to the right of the record at the top right (labelled “Transition”) only toggles the transition sound, not the background music. Background music starts automatically after the opening animation; turn autoplay off in the admin page or pause with the record. Browsers usually stay silent until your first click on the page.
- **Reduced motion**: when enabled in the system or the admin page, transitions become short fades and the opening animation is skipped.

#### Data and privacy

- Data lives in the browser’s **IndexedDB** (database `cv1`); preferences (language, volume, switches) live in `localStorage` (keys start with `cv-`). Nothing is sent to any server.
- Browser data can be cleared, so export a JSON backup regularly from “Admin → Data & backup”. Backups contain characters, worlds, fragments, the archive, relation maps, tools, the personal profile and the template; imported background music is not included.

#### Export

- **Image**: captured as displayed, at 2× resolution or higher by default.
- **Text**: plain text keeping group and field order; empty fields are omitted.
- **PDF**: the full image is sliced into A4 pages.
- The purple line-art decorations are CSS decorations and do not appear in exported files.
- The version published on claude.ai saves files through the platform’s download capability; when hosted independently (locally, GitHub Pages) it uses the browser’s regular download.

#### Files

```
.
├── index.html   # the whole app: HTML + CSS + JS + embedded images and audio
└── README.md
```

#### Assets and copyright

The assets were collected by the author; their file names suggest most come from Pixabay and similar sites. Audio includes a piano version of Chopin’s Ballade No. 4 (background music) and the transition sounds `freesound_community-pigeons-flying`, `lucadialessandro-sweet-transition`, `u_a4gfvwagf1-crow-sound-effect` and `dragon-studio-crow-caw-with-echoing-reverb`.

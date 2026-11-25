# 醫方內外集（RB00001162） / Ihō naigaishū: Transcription Dataset

京都大學附屬圖書館富士川文庫藏一冊和裝中本抄本，館目原題為「医方内外集」。底本索書號 イ/296，登錄號 183698。 [館目](https://rmda.kulib.kyoto-u.ac.jp/item/rb00001162) · [館藏 IIIF](https://rmda.kulib.kyoto-u.ac.jp/iiif/metadata_manifest/RB00001162/manifest.json)

《醫方內外集》是京都大學富士川文庫所藏的醫方抄本（RB00001162）。書中並列歷史病證、藥名及分量，收錄湯、丸與外用膏等方文，夾有片假名，末段可見較多日語敘述。開卷部分醫方亦見於《外科正宗》，本冊保留自己的方次、略錄方式及和漢混寫，可供研究日本醫方彙抄與漢文醫學知識的流通。本資料集對應館方 44 幅書影，其中 39 幅有正文，提供 JSON、TXT、TEI 和逐項校讀紀錄。此版為 AI 校讀稿，原逐項校讀保留 272 項未解。人工全文二校待完成。

Ihō naigaishū is a manuscript collection of medical prescriptions held in the Fujikawa Collection at Kyoto University (RB00001162). It records historical medical conditions, ingredients, and quantities in entries for decoctions, pills, and topical preparations. Katakana appears alongside literary Chinese, with more extended Japanese passages near the end. Some opening prescriptions also appear in Waike zhengzong. The manuscript preserves its own sequence, abridgments, and mixed writing, offering material for studying Japanese prescription collections and the transmission of Chinese medical knowledge. The dataset maps to 44 official images, including 39 images bearing the main text, and provides JSON, TXT, TEI, and an item-level review ledger. The AI-reviewed edition records 272 unresolved comparison items in the primary review. Full human collation is outstanding.

館目未列原書作者、抄者或抄寫年代。2016 年是館方數位化年度。

The catalogue gives no author, copyist, or copying date. Fiscal year 2016 is the library’s digitization date.

開卷有與陳實功《外科正宗》卷二重疊的個別醫方。其方次、略錄形式與後段日語材料仍以京都抄本原圖為準。已查公開索引未見本冊的獨立其他傳本、另行影印、翻刻或整冊文字。 [《外科正宗》卷二](https://jicheng.tw/tcm/book/%E5%A4%96%E7%A7%91%E6%AD%A3%E5%AE%97/index.html)

Some opening prescriptions overlap with juan 2 of Chen Shigong’s Waike zhengzong. The transcription follows the Kyoto manuscript’s sequence, abridged entries, and later Japanese-language material. The public catalogues searched yielded no independent witness, separate facsimile, printed transcription, or full machine-readable text for this copy.

[p003 原冊前封](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00001162%2FRB00001162_00003_0.ptif/full/2000,/0/default.jpg) · [p005 正文起首與藏印](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00001162%2FRB00001162_00005_0.ptif/full/2000,/0/default.jpg) · [p006 兩面方文](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00001162%2FRB00001162_00006_0.ptif/full/2000,/0/default.jpg) · [p040 正文後段](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00001162%2FRB00001162_00040_0.ptif/full/2000,/0/default.jpg) · [p043 末幅正文](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00001162%2FRB00001162_00043_0.ptif/full/2000,/0/default.jpg)

## 資料與校讀

- `data/document.json` 保留歷史文字、原圖定位、疑讀及缺口。
- `data/text.txt`、`data/text.tei.xml` 及 sidecar 提供全文與逐文字單位對應。
- `data/review.json` 保留逐項校讀、未解 ID 及修訂採用狀態。
- `data/manifest.json` 與 `PACKAGE-SHA256SUMS.txt` 記錄固定發行檔案的雜湊。

44 幅官圖均保留定位。正文自第 5 幅左面起，至第 43 幅左面止，共有 39 幅正文影像。外書套同一大題籤錄一次，脊籤、原冊題籤及第 5 幅可辨藏印各依實見分層。封裏、空白與原後封仍保留版面定位。

The dataset retains the locations of all 44 official images. The main text runs from the left side of image 5 to the left side of image 43, spanning 39 text-bearing images. The repeated case label is recorded once. The spine label, original cover title, and legible historical seals in image 5 are recorded by location. The pastedown, blank surfaces, and back cover retain their locations.

初錄與第二路讀稿各以同一批固定原圖為據。Claude 完成第 1–9 幅初錄與第 1–9 幅第二路讀稿。Codex 完成第 10–44 幅初錄與第 10–44 幅第二路讀稿。Codex 依原圖覆核 1536 項比對。全冊共有 1536 項比對，採用 113 項有原圖依據的修訂，最終保留 272 項未解。另有 69 項未套用的替代讀法，保存在逐項紀錄。JSON、TXT 和 TEI 的逐欄內容通過程式回讀，TEI 通過 P5 4.12.0 Relax NG 驗證。人工全文二校、專家審定與準確率量測尚待進行。

The two independent readings used the same fixed source images. Claude produced the first reading for images 1–9 and the second reading for images 1–9. Codex produced the first reading for images 10–44 and the second reading for images 10–44. Codex reviewed 1536 comparison items against the images. The ledger records 1536 comparison items, 113 corrections supported by the images, and 272 remaining unresolved items. The ledger retains 69 alternate readings without applying them. Automated checks confirmed column-by-column agreement across JSON, TXT, and TEI. The TEI passed P5 4.12.0 Relax NG validation. Full human collation, expert assessment, and accuracy measurement are outstanding.

## 權利與引用

歷史原文、館藏影像、新增說明與資料編排依各自的權利條件處理。書影請由京都大學來源連結取用。 [權利說明](LICENSE.md)

曲宸宇（Chu, Chen-Yu）。2026。醫方內外集（RB00001162） / Ihō naigaishū: Transcription Dataset。v0.1.0。資料集。 [固定發行](https://github.com/poplolioi11/iho-naigai-shu/releases/tag/v0.1.0) · [ORCID](https://orcid.org/0009-0003-9738-6914)

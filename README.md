# Vanilla compatible 1.21

This is a packwiz pack that for me to play with friends. This is a vanilla compatible pack that able to let your map can be upgraded along with Minecraft version. Currently focus on client-side cause I'm not hosting the server this time/

## Installation

Use [MultiMC](https://multimc.org/) and put the link below when importing zip.

```plain
https://github.com/Small-Ku/packwiz-packs/releases/download/v0.2.0/1.18.2.zip
```

Change pre-launch command to:
```
"$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://raw.githubusercontent.com/Small-Ku/packwiz-packs/refs/heads/vanilla/1.21.10/pack.toml
```

## Usage

Launch the game from MultiMC. Select the mods you want.

## Contributing

Pull requests are welcome for bug fixes. For major changes, please open an issue first to discuss what you would like to change.

While `packwiz serve -p 25566`, change pre-launch command to:
```
"$INST_JAVA" -jar packwiz-installer-bootstrap.jar http://127.0.0.1:25566/pack.toml
```

## License

[Unlicense](http://unlicense.org/)

## Mod List
<!-- MODS_START -->
### Library

| Mod | Description |
|---|---|
| [bad packets](https://modrinth.com/mod/ftdbN0KK) | A library mod enabling cross-platform communication between Fabric and Forge mods—requires developers to manually integrate its API. Does not auto-fix mod compatibility issues.<br>跨平台通訊函式庫模組，讓Fabric與Forge版模組能互相傳訊。需開發者手動整合API，無法自動解決模組相容性問題。 |
| [Cloth Config API](https://modrinth.com/mod/9s6osm5g) | A library mod providing API for in-game configuration screens.<br>提供遊戲內設定選單API的函式庫模組。 |
| [Daisy](https://modrinth.com/mod/s6dgwBzy) | A library mod providing shared utilities (collection factors, Catheter) for Cao awa's mods like Sepals and Annuus—open for integration in other mods.<br>提供共用工具（集合因數、Catheter）的函式庫模組，供 Cao awa 的模組（如 Sepals、Annuus）使用，亦開放其他開發者整合至其模組。 |
| [Fabric API](https://modrinth.com/mod/P7dR8mSH) | <br><br>A library mod providing essential hooks and APIs for Fabric mod development—including particle/biome access, registry sync, crash report enhancements, and rendering compatibility.<br>Fabric模組開發必備函式庫，提供粒子/生態域存取、註冊表同步、當機報告增強及渲染相容性等核心功能。 |
| [Fabric Language Kotlin](https://modrinth.com/mod/Ha28R6CL) | <br><br>A dependency mod enabling Fabric mods to be developed in Kotlin—adds no gameplay content and works with any Minecraft version via Fabric Loader.<br>供Fabric模組使用Kotlin語言開發的依賴項，不添加遊戲內容，透過Fabric Loader支援所有Minecraft版本。 |
| [MaLiLib](https://modrinth.com/mod/GcWjdA9I) | <br><br>A client-side library mod providing shared config, keybinds, and GUI systems for masa's mods—reduces code duplication across dependent mods.<br>masa 系列客戶端模組的共用函式庫，整合設定管理、按鍵綁定與介面系統，有效降低相依模組的程式碼重複。 |
| [Mod Menu](https://modrinth.com/mod/mOgUt4GM) | A mod providing an in-game menu to view installed mods and access their config screens—supports update checks and filters library mods.<br>遊戲內模組管理選單，一覽所有已安裝模組並快速進入設定介面，自動檢查更新並分類核心函式庫模組。 |
| [Text Placeholder API](https://modrinth.com/mod/eXts2L7r) | A library mod enabling placeholder syntax (%modid:type%) and text formatting for Minecraft mods.<br>Minecraft模組開發專用佔位符API，支援%modid:type%語法與文字格式化功能。 |
| [Resourceful Config](https://modrinth.com/mod/M1953qlQ) | A developer library enabling cross-platform configs with in-game UI and hot reloading—supports Forge/Fabric with JSONC fallback.<br>開發者函式庫，提供跨平台設定檔支援，內建遊戲設定介面與即時生效功能，相容Forge/Fabric平台。 |
| [YetAnotherConfigLib (YACL)](https://modrinth.com/mod/1eAoo2KR) | YetAnotherConfigLib<br><br>A modern config library for Fabric mods with intuitive UI controls, rich descriptions, and keyboard-friendly tabs—designed to replace outdated alternatives.<br>Fabric模組專用設定函式庫，提供直覺化介面控制項、多媒體描述文字與鍵盤友好分頁，取代過時的現有方案。 |

### Client

| Mod | Description |
|---|---|
| [Audio Engine Tweaks](https://modrinth.com/mod/DZ81JNQ1) | <br><br>A mod that prevents Minecraft's sound pool from overflowing by intelligently prioritizing audio—stops all audio cutting out during intense moments. Fully configurable sound categories and thresholds.<br>防止Minecraft音效池溢出的模組，透過智能音效優先級管理，杜絕激烈戰鬥或大型場景中的音效中斷問題。所有音效類別與閾值皆可自訂調整。 |
| [Auto HUD](https://modrinth.com/mod/temczoTQ) | A mod that auto-hides static HUD elements like permanent status effects—keeps hands, names, and chat visible while allowing full customization. Requires YetAnotherConfigLib for in-game settings.<br>自動隱藏靜態遊戲介面元素（如永久狀態效果）的模組：手持物品、玩家名字、聊天訊息始終可見，介面高度可調。需YetAnotherConfigLib支援遊戲內設定。 |
| [Better Mount HUD](https://modrinth.com/mod/kqJFAPU9) | A client-side mod that shows both your food bar and mount's health while riding—keeps the XP bar visible except during jumps.<br>客戶端模組，騎乘坐騎時同時顯示玩家飽食度與坐騎生命值，僅跳躍瞬間替換經驗條。 |
| [BetterGrassify](https://modrinth.com/mod/m5T5xmUy) | <br><br>A Fabric mod that replaces grass block side textures with top textures when surrounded by grass—eliminates distracting dirt streaks on hills and plains for cleaner terrain visuals.<br>Fabric模組，當草方塊被其他草方塊包圍時，自動將側面紋理替換為頂部紋理，消除丘陵與平原上的泥土條紋，打造更乾淨的地形視覺效果。 |
| [Boat Item View](https://modrinth.com/mod/BdKIyOLe) | A client-side mod that displays your held item while riding a boat—purely visual, doesn't enable item usage during movement.<br>客戶端模組，乘船時可見手持物品。純視覺效果，移動中仍無法使用物品。 |
| [caramelChat](https://modrinth.com/mod/M4vJe1FJ) | A mod enhancing CJK (Chinese/Japanese/Korean) IME support in Minecraft—fixes input field synchronization and provides seamless chat/naming experiences.<br>強化 Minecraft 中文/日文/韓文輸入法支援的模組，修復輸入框同步問題，讓聊天與命名操作流暢無礙。 |
| [Chat Heads](https://modrinth.com/mod/Wb5oqrBJ) | A client-side mod displaying player heads next to chat messages for better readability and visual appeal.<br>客戶端模組，在聊天訊息旁顯示玩家頭像以提升辨識度與視覺效果。 |
| [Collision Fix](https://modrinth.com/mod/CBtq0jWL) | A client-side mod that prevents mobs from pushing you when nearby—retains normal attack knockback.<br>客戶端模組，防止附近生物推擠玩家，但保留攻擊擊退效果。 |
| [Continuity](https://modrinth.com/mod/1IjD5062) | <br><br>A client-side mod enabling OptiFine-style connected/emissive textures and custom block layers without OptiFine. Includes built-in packs for glass/bookshelves and glass pane culling. Works on Fabric/Forge/NeoForge via compatibility layers.<br>客戶端模組，無需OptiFine即可支援OptiFine格式的連鎖紋理/發光紋理與自訂方塊層。內建玻璃/書架連鎖紋理及玻璃板縫隙修復資源包。透過相容層支援Fabric/Forge/NeoForge。 |
| [Entity Culling](https://modrinth.com/mod/NNAgCjsB) | <br><br>A mod that skips rendering hidden mobs and block entities behind walls using real-time multithreaded visibility checks—reduces GPU load while preserving visuals.<br>利用多執行緒即時偵測視野外實體的模組，自動跳過牆後生物與區塊實體渲染，降低GPU負載且不影響畫面品質。 |
| [Fabrishot](https://modrinth.com/mod/3qsfQtE9) | A mod for capturing ultra-high-resolution screenshots up to 4K (3840x2160) by default—customize resolution via Mod Menu.<br>超高解析度螢幕截圖模組，預設支援4K (3840x2160)，可透過模組選單調整截圖解析度。 |
| [Fast IP Ping](https://modrinth.com/mod/9mtu0sUO) | <br><br>A client-side mod that skips reverse DNS lookups for IP-only servers—cuts ping/connection delay by 1-5 seconds on Fabric/Forge/NeoForge.<br>客戶端模組，跳過純IP伺服器的反向DNS查詢，減少1-5秒連線延遲。支援Fabric/Forge/NeoForge環境。 |
| [Iris Shaders](https://modrinth.com/mod/YL57xq9U) | A modern shader loader mod compatible with existing OptiFine shader packs for Minecraft.<br>現代化光影載入器模組，完全相容現有OptiFine光影包，為Minecraft提供流暢體驗。 |
| [Language Reload](https://modrinth.com/mod/uLbm7CG6) | A Fabric mod enabling instant language switching without reloading resources—adds multilingual search, fallback systems, and keyboard shortcuts (F3+J).<br>Fabric模組，實現無需重載資源包的即時語言切換，支援多語言搜尋、自動備援機制及快捷鍵操作(F3+J)，大幅減少加載延遲。 |
| [Litematica Enderchest Materials](https://modrinth.com/mod/oBzw5QUs) | A Litematica addon that includes ender chest contents in material lists—open your ender chest once per session to sync items automatically.<br>Litematica 附加模組，將末影箱物品納入材料清單。每次進入世界開啟末影箱一次，即可自動同步內容。 |
| [Logarithmic Volume Control](https://modrinth.com/mod/fPJLcvRR) | Fixes Minecraft's linear volume sliders to follow human logarithmic perception—makes low-volume adjustments precise. Minimal mod with high cross-version compatibility.<br>修正 Minecraft 線性音量滑桿，改用符合人耳感知的對數刻度——低音量調節更精準。極簡設計，跨版本相容性高。 |
| [More Leaf Particles](https://modrinth.com/mod/HwWDzPBa) | <br><br>A client-side mod that replaces generic leaf particles with type-specific falling foliage—spruce needles, birch leaves, and azalea petals. Fully configurable particle behavior.<br>客戶端模組，將通用樹葉粒子替換為符合樹種的飄落效果：雲杉針葉、樺木葉片與杜鵑花瓣。可完整自訂粒子物理參數。 |
| [No Double Sneak](https://modrinth.com/mod/TkeWvQw9) | A Fabric mod that fixes camera bounce when rapidly toggling sneak—minimal design ensures easy updates.<br>Fabric 模組，修復快速切換潛行時相機彈跳問題。極簡設計確保版本更新無縫銜接。 |
| [No Jump Delay Enhanced](https://modrinth.com/mod/4XFSzxty) | No Jump Delay: Enhanced<br><br>A client-side Fabric mod that removes jump cooldown for continuous jumping—configurable toggle and server rule warning included.<br>客戶端Fabric模組，移除跳躍冷卻時間實現連續跳躍。提供開關設定並提醒伺服器規則限制。 |
| [Pickup HUD](https://modrinth.com/mod/AOSTym6m) | A lightweight mod that displays newly picked-up items and experience orbs on your HUD—fully customizable with rarity indicators.<br>輕量模組，在遊戲介面即時顯示新拾取物品與經驗球，支援稀有度提示與完整自訂設定。 |
| [Ping View](https://modrinth.com/mod/gvl7lVcV) | <br><br>A client-side mod showing player ping in the tab list with color-coded latency—keeps vanilla UI appearance while lightweight.<br>客戶端模組，在玩家列表中以顏色區分延遲數值，輕量設計且維持原版介面外觀。 |
| [Raised](https://modrinth.com/mod/nCQRBEiR) | A GUI customization mod that repositions vanilla and modded interfaces with pixel precision—fixes hotbar selection texture and syncs elements for optimal screen layout on Fabric/Forge/NeoForge.  <br>GUI自訂模組，精確調整原版與模組介面位置，修復快捷列選取紋理瑕疵。支援Fabric/Forge/NeoForge平台，可同步移動多層介面以達最佳畫面配置。 |
| [Reese's Sodium Options](https://modrinth.com/mod/Bh37bMuy) | <br><br>A mod overhauling Sodium's UI with search bar, scrollable tabs/pages, precise SHIFT-scroll slider control, and Iris shader access.<br>全面改造Sodium介面，加入搜尋列、可捲動分頁/頁面、按住SHIFT滾動精細調整滑桿，以及Iris光影快速按鈕。 |
| [Riding Mouse Fix](https://modrinth.com/mod/kwS02byl) | A mod fixing sluggish mouse control when riding minecarts/entities—alpha version may cause cursor jumps on high-ping servers. Boats unaffected.<br>修復乘坐礦車/生物時滑鼠操作遲鈍的模組，Alpha版本在高延遲伺服器可能導致游標跳動，不影響船隻操作。 |
| [Server Resourcepack Checker](https://modrinth.com/mod/fCpuZIcM) | A client-side Fabric mod that skips redundant server resource pack downloads by comparing file hashes—eliminates annoying loading screens when joining servers.<br>客戶端Fabric模組，透過比對檔案雜湊值跳過重複的伺服器資源包下載，消除進出伺服器時惱人的加載畫面。 |
| [ServerAddressSpaceFix](https://modrinth.com/mod/NJGSUuLp) | A client-side mod that auto-strips spaces from server addresses to prevent "unknown host" errors when connecting.<br>客戶端模組，自動移除伺服器地址空格，避免連線時出現「未知的主機」錯誤。 |
| [shut up realms](https://modrinth.com/mod/esvER4Ln) | A client-side mod that removes the Realms notification dot and news icon—keeps the button fully functional.<br>客戶端模組，移除 Realms 按鈕的通知紅點與新聞圖示，完整保留按鈕功能。 |
| [Smooth Scrolling Refurbished](https://modrinth.com/mod/trr0scVt) | A client-side mod that replaces all in-game scrollbars with smooth animations—direct replacement for the abandoned Smooth Scrolling Everywhere mod.<br>客戶端模組，將遊戲內所有捲動條替換為平滑滾動效果，作為已停止維護的Smooth Scrolling Everywhere模組的現代替代方案。 |
| [Stack to Nearby Chests](https://modrinth.com/mod/HtGckJVc) | A client-side mod importing Terraria-style quick stacking/restocking—organize items into nearby chests/barrels with one keypress. Customizable hotkeys and favorite items.<br>客戶端模組，移植泰拉瑞亞式快速整理/補充功能：一鍵將物品分類至附近儲物箱、木桶，支援自訂快捷鍵與收藏特定物品。 |
| [Tweakeroo](https://modrinth.com/mod/t5wuYk45) | <br><br>A client-side mod adding practical tweaks like hand restock, flexible block placement, and free camera mode. Config accessible via X+C.<br>客戶端模組，提供手持物品自動補充、靈活方塊放置、自由相機等實用功能。按 X+C 開啟設定選單。 |
| [ViaFabricPlus](https://modrinth.com/mod/rIC2XJV4) | <br><br>A Fabric mod enabling connections to servers from all Minecraft versions (Classic to Bedrock) with fixed movement/block interactions—client-only, latest version required.<br>Fabric 模組，支援連接全版本 Minecraft 伺服器（從經典版至基岩版），修正移動/方塊互動以重現原始體驗。僅限最新版客戶端使用，多人遊戲專用。 |
| [Zume](https://modrinth.com/mod/o6qsdrrQ) | A simple zoom mod that temporarily narrows your field of view with a keybind—adjust zoom levels on the fly for better distant visibility.<br>簡易縮放模組，按住按鍵即可縮小視野範圍，動態調整縮放程度以清晰觀察遠方景物。 |

### Performance

| Mod | Description |
|---|---|
| [Alternate Current](https://modrinth.com/mod/r0v8vy1s) | A mod that drastically reduces redstone lag by optimizing power calculations—makes redstone networks run smoother while keeping vanilla behavior intact.<br>大幅降低紅石延遲的模組，透過電力計算優化使紅石電路流暢運作，完全保留原版行為。 |
| [Async](https://modrinth.com/mod/vEC2jm6I) | A Fabric mod that maintains stable TPS during massive mob spawns by spreading entity processing across CPU cores. Experimental async random ticks included.<br>Fabric模組，透過多核心分擔運算，在大量生物生成時維持每秒遊戲刻穩定。含實驗性非同步隨機刻功能。 |
| [AsyncParticles](https://modrinth.com/mod/c3onkd5k) | A client-side mod that speeds up particle effects and weather rendering through async processing—reduces lag during storms and complex machinery scenes. Supports 1.21.5+ and mod interactions.<br>客戶端模組，透過非同步技術加速粒子與天氣渲染，暴雨或大型機械場景不卡頓。支援1.21.5+版本及多模組交互運作。 |
| [BadOptimizations](https://modrinth.com/mod/g96Z4WVZ) | <br><br>A client-side mod that skips unnecessary lightmap updates, simplifies sky color calculations in single-biome areas, and skips unused debug renders—improves FPS with configurable optimizations.<br>客戶端模組，自動跳過無效亮度貼圖更新、簡化單一生態域天空運算、略過未啟用除錯渲染。可透過設定檔調整，有效提升遊戲幀率。 |
| [BlueMap](https://modrinth.com/mod/swbUV1cr) | A Minecraft mod that generates interactive 3D web maps of your worlds with asynchronous rendering—zero server lag during map updates.<br>Minecraft 模組，生成可互動的 3D 網頁地圖，採用非同步渲染技術確保地圖更新時伺服器運行不受影響。 |
| [Concurrent Chunk Management Engine (Fabric)](https://modrinth.com/mod/VSNURh3q) | <br><br>A Fabric mod that accelerates world loading and chunk generation via multi-core CPU usage—maintains vanilla behavior and pairs optimally with Lithium/ScalableLux.<br>Fabric模組，透過多核心CPU加速世界加載與區塊生成，完全保留原版行為，推薦搭配Lithium/ScalableLux使用。 |
| [Client Maps](https://modrinth.com/mod/K7BL4mb2) | A mod that saves server map data locally—keeps maps intact when disconnected and fills gaps during server lag. Complements Map In Slot and Minihud mods.<br>本地儲存伺服器地圖數據的模組，斷線時保留地圖完整性，伺服器延遲時自動填補空白，完美搭配Map In Slot與Minihud等模組。 |
| [Distant Horizons](https://modrinth.com/mod/uCdwusMi) | <br><br>A mod extending view distance with simplified terrain beyond default limits—maintains performance while revealing landscapes from mountaintops. Compatible with specific shaders (OptiFine/Iris 1.7+). Strict version requirements.<br>延伸視距的模組，在預設範圍外生成簡化地形，登上高山可俯瞰遼闊地景而不影響流暢度。相容特定光影（OptiFine/Iris 1.7+），需嚴格對應Minecraft版本。 |
| [Express Carts](https://modrinth.com/mod/Xog4t7Fl) | A server-side Fabric mod adding Express Minecarts with 2x speed and improved physics—no client mods needed, fully compatible with vanilla systems and technical builds.<br>伺服器端Fabric模組，添加速度兩倍且物理效果更佳的特快礦車。無需客戶端模組，完全相容原版系統與礦車機關建築。 |
| [Ixeris](https://modrinth.com/mod/p8RJPJIC) | <br><br>A client-side mod that eliminates FPS drops during camera movement by offloading mouse event polling from the render thread—most effective on Windows with high-polling-rate mice.<br>客戶端模組，將滑鼠事件輪詢移出渲染執行緒，消除轉動視角時的幀率下降，高回報率滑鼠的Windows系統效果最顯著。 |
| [KryptonFNP Patcher](https://modrinth.com/mod/yzkasIPx) | FNP Patcher<br><br>A Krypton Fabric extension mod adding RecastLib support (Windows x64/arm64) and extra optimizations.<br>Krypton Fabric 擴充模組，新增 RecastLib 支援（Windows x64/arm64）及基礎優化。 |
| [lazy-language-loader](https://modrinth.com/mod/Nz0RSWrF) | A mod that speeds up language switching by reloading only language resources instead of all game assets.<br>加速遊戲內語言切換的模組，僅重載語言資源而非全部遊戲素材，大幅減少切換延遲。 |
| [Leaves Us In Peace](https://modrinth.com/mod/IIpWIe1o) | <br><br>A server-side mod that makes leaf decay smarter and faster—ignores different leaf/log types, configurable decay speed, with optional particles/sounds.<br>伺服器端模組，智能化樹葉衰減系統：自動忽略不同樹種的樹葉與原木，可調整衰減速度，並支援衰減時的粒子與音效效果。 |
| [Lithium](https://modrinth.com/mod/gvQqBUqZ) | <br><br>A general-purpose optimization mod that improves physics, AI, and block ticking without altering vanilla mechanics. Works client/server independently; boosts TPS on servers and FPS in singleplayer.<br>通用優化模組，強化物理/AI/方塊更新系統，完全保留原版機制。客戶端與伺服器可獨立安裝，多人遊戲提升每秒遊戲刻，單人模式增加畫面幀率。 |
| [ModernFix-mVUS](https://modrinth.com/mod/TjSm1wrD) | ModernFix<br><br>An all-in-one optimization mod for Minecraft 1.16+ that drastically speeds up modpack launches and cuts memory usage without compromising gameplay.<br>全方位優化模組，大幅提升1.16以上版本模組包啟動速度並降低記憶體用量，完全保留原版遊戲體驗。 |
| [More Culling](https://modrinth.com/mod/51shyZVL) | A performance mod that optimizes multiple culling types (block/item frame/leaves) to reduce GPU load and fix vanilla culling bugs.<br>效能優化模組，強化方塊/物品展示框/樹葉等多種剔除技術，降低GPU負載並修復原版剔除錯誤。 |
| [NoisiumForked](https://modrinth.com/mod/hasdd01q) | Noisium Forked<br><br>A maintained fork of Noisium optimizing world generation speed—directly sets block states in palette storage and accelerates biome population/chunk unlocking. 100% vanilla worldgen parity.<br>Noisium 維護分支，透過直接操作調色盤存儲加速世界生成，提升生物群系生成與區塊解鎖效率。100% 原版世界生成相容性。 |
| [RecipeCooldown](https://modrinth.com/mod/7LEWYKTV) | A server-side Fabric/Quilt mod adding cooldowns to recipe book requests—prevents packet spam from lagging servers on Minecraft 1.16+.<br>伺服器端 Fabric/Quilt 模組，為合成配方書請求添加冷卻時間，防止封包濫用導致 1.16+ 版本伺服器延遲。 |
| [RenderScale](https://modrinth.com/mod/Va8PJBFX) | A mod that independently adjusts Minecraft's render resolution from HUD elements—toggle via 'O' key for better visuals or performance on Retina displays.<br>獨立調整Minecraft渲染解析度(不影響介面元素)的模組。透過O鍵快速切換，為Retina螢幕提升畫質或遊戲效能。 |
| [ScalableLux](https://modrinth.com/mod/Ps1zyz6x) | A Fabric mod inheriting Starlight's legacy to accelerate light updates—maintains 100% faster performance than vanilla with parallel processing for busy servers.<br>繼承Starlight的Fabric模組，加速光照更新速度。維持比原版快100%的效能，透過平行處理技術優化多人伺服器負載。 |
| [Sepals](https://modrinth.com/mod/hH1OHXZD) | An experimental server-side mod that drastically optimizes entity-heavy scenarios (villagers/frogs) when combined with Lithium/Async. May alter vanilla behavior.<br>實驗性伺服器模組，搭配Lithium/Async時大幅優化村民/青蛙等高密度實體場景，可能改變原版行為。 |
| [ServerCore](https://modrinth.com/mod/4WWQxlQP) | A server optimization mod that reduces lag spikes and improves tick performance while preserving vanilla behavior by default. Features configurable entity activation ranges, dynamic resource adjustments, and villager processing optimizations. Works on dedicated servers and singleplayer worlds.<br>伺服器優化模組，大幅減少延遲尖峰並提升遊戲刻效能，預設維持原版行為。提供可調整的實體激活範圍、動態資源分配與村民處理優化。適用於專用伺服器及單人世界。 |
| [Server Pinger Fixer](https://modrinth.com/mod/iqK5uv72) | A mod that speeds up server list refreshes by optimizing ping threads and clearing overloaded pools.<br>透過優化延遲測試執行緒與清理過載池，加速伺服器清單重新整理速度。 |
| [Stfu](https://modrinth.com/mod/Rg9WdvvR) | A mod silencing notifications (Realms/telemetry/chat warnings) and speeding up loading—customizes UI/HUD with key rebinding. Requires Fabric API/Mod Menu/YACL.<br>消除通知干擾（Realms/遙測/聊天警告）並加速載入的模組，可自訂介面/HUD元素及按鍵綁定。需Fabric API/Mod Menu/YACL支援。 |
| [Smoke Suppression](https://modrinth.com/mod/nKcekY2P) | A client-side mod that suppresses campfire smoke when specific blocks are placed underneath—prevents lag and visual clutter in large farms. Works for both regular and soul campfires.<br>客戶端模組，當特定方塊置於營火下方時抑制煙霧，避免大型營火農場造成的延遲與視覺干擾。適用於普通及靈魂營火。 |
| [Sodium](https://modrinth.com/mod/AANobbMI) | <br><br>A rendering optimization mod that boosts FPS and fixes visual glitches—maintains authentic blocky visuals with wide mod compatibility on Fabric/NeoForge.<br>渲染優化模組，大幅提升幀率並修復畫面錯誤，完整保留方塊風格原貌。支援Fabric/NeoForge平台，相容絕大多數模組。 |
| [spark](https://modrinth.com/mod/l6YH9Als) | A lightweight mod for CPU/memory profiling and server health monitoring—generates instant performance insights with minimal impact.<br>輕量級效能分析模組，提供CPU/記憶體剖析與伺服器健康監控，即時生成洞察報告且不影響運行效能。 |
| [Substrate](https://modrinth.com/mod/zNuzb72d) | <br><br>A Sodium add-on mod that removes hidden block faces on world boundaries—boosts FPS on Overworld floor and Nether ceilings without visual changes.<br>Sodium附加模組，移除世界邊界層不可見方塊面，提升主世界底層與下界頂底層幀率，無視覺差異。 |
| [TT20 (TPS Fixer)](https://modrinth.com/mod/YS3ZignI) | TT20<br><br>A server-side mod that reduces perceived lag during low TPS by dynamically adjusting game timings—preserves player experience when servers struggle.<br>伺服器端模組，當TPS降低時動態調整遊戲時間參數，減少玩家感知延遲。在伺服器負荷過重時維持流暢遊戲體驗。 |
| [voxy](https://modrinth.com/mod/fxxUqruK) | A Level of Detail rendering mod that dynamically adjusts visual detail based on distance to optimize performance.<br>階層式細節渲染模組，依據距離動態調整畫面細節以優化效能。 |

### Server

| Mod | Description |
|---|---|
| [Disconnect Packet Fix](https://modrinth.com/mod/rd9rKuJT) | A minimal Fabric/NeoForge mod that silences MC-271325 console spam caused by disconnect packet errors—temporary fix until Mojang resolves the bug.<br>極簡Fabric/NeoForge模組，消除MC-271325漏洞導致的斷線封包錯誤主控台刷屏。Mojang修復前的臨時解決方案。 |
| [Harvester](https://modrinth.com/mod/jLBC4JG7) | A lightweight right-click crop harvesting mod working with vanilla crop mechanics—tag-configurable, only on server or singleplayer.<br>輕量級右鍵收穫模組，基於原版作物生長機制運作。僅作用於伺服器或單機中，標記為可收穫的作物。 |
| [No Crop Trample](https://modrinth.com/mod/TEL2rIgj) | A simple mod that prevents crops from being destroyed when walked over by players or mobs.<br>簡單模組，防止玩家或生物走過時摧毀農作物。 |
| [Servux](https://modrinth.com/mod/zQhsx8KF) | <br><br>A server-side mod enabling MiniHUD's structure boundary rendering in multiplayer—no client install needed except for LAN hosts.<br>伺服器端模組，使MiniHUD在多人遊戲中顯示建築結構邊界框，客戶端無需安裝（區域網路主機除外）。 |
| [Structure Layout Optimizer](https://modrinth.com/mod/ayPU0OHc) | A server-side mod accelerating jigsaw structure generation by optimizing collision checks and NBT loading—preserves vanilla visuals but may alter layout seeds.<br>伺服器端模組，透過優化碰撞檢測與NBT載入加速拼圖結構生成，維持原版外觀但可能改變結構生成樣式。 |

### Other

| Mod | Description |
|---|---|
| [Annuus](https://modrinth.com/mod/kIfxYoGs) | A server-side mod that compresses network traffic for large Minecraft servers—reduces chunk/block update data by up to 90% while remaining compatible with vanilla clients.<br>針對大型伺服器的網路流量壓縮模組：區塊與方塊更新數據量減少達90%，客戶端不裝模組也能正常連線。 |
| [AppleSkin](https://modrinth.com/mod/EsAfCjCV) | A client-focused mod that visualizes hidden hunger mechanics—shows food values, saturation bars, and health restoration previews. Requires server installation for accurate stats.<br>專注客戶端的模組，可視化隱藏飢餓機制：顯示食物數值、飽食度條、生命恢復預覽。需伺服器安裝才能取得精準數據。 |
| [BadStdOut](https://modrinth.com/mod/9Y8sMRVG) | A diagnostic mod that tags all STDOUT log entries with their source mod name—simplifies debugging when multiple mods output errors simultaneously.<br>偵錯輔助模組，自動標註每條標準輸出日誌的來源模組名稱。當多個模組同時報錯時，快速定位問題根源。 |
| [BoatView360](https://modrinth.com/mod/vqnOCHgM) | A mod that enables full 360° head rotation while riding boats—requires client installation; for multiplayer sync, all players and server must have it.<br>解除船隻乘客視角限制的模組，乘船時可自由環顧四周。客戶端必裝，多人遊戲需全員與伺服器安裝才能同步顯示。 |
| [Chunky](https://modrinth.com/mod/fALzjamp) | A server-side mod for pre-generating world chunks efficiently—pause/resume tasks, track progress with ETAs, and shape generation areas to match world borders. Requires operator permissions.<br>伺服器端模組，高效預生成世界區塊。支援暫停/繼續任務、追蹤進度與預估時間，並可依世界邊界塑造生成範圍。需操作員權限才能使用。 |
| [Discerning Furnace](https://modrinth.com/mod/G3Nz6HN4) | A minimal mod preventing non-smeltable items from entering furnace input slots—blocks invalid items from players (client) and hoppers (server). Works with vanilla and compatible modded furnaces.<br>精簡模組，阻止不可熔煉物品進入熔爐輸入格。客戶端防止玩家放入無效物品，伺服器端阻擋漏斗輸入。適用於原版熔爐及相容的模組熔爐。 |
| [FerriteCore](https://modrinth.com/mod/uXXizFIs) | A mod that reduces Minecraft memory usage by up to 45%—install on both server and client. Incompatible with Hydrogen on Minecraft 1.18+.<br>降低 Minecraft 記憶體用量最高 45% 的模組，伺服器與客戶端均需安裝。Minecraft 1.18+ 版本與 Hydrogen 模組不相容。 |
| [Krypton](https://modrinth.com/mod/fQEb0iXm) | A Fabric mod optimizing Minecraft's networking stack with Velocity-derived handlers—reduces server CPU load and memory usage.<br>Fabric模組，透過Velocity優化技術強化Minecraft網路效能，降低伺服器CPU負載與記憶體用量。 |
| [MixinTrace](https://modrinth.com/mod/sGmHWmeL) | A mod that appends mixin lists to crash report stack traces for precise debugging.<br>將 mixin 清單附加至當機報告堆疊追蹤的模組，精準定位錯誤根源。 |
| [No Prying Eyes](https://modrinth.com/mod/LoXPgYhm) | No Chat Reports<br><br>A client-side mod that removes cryptographic signatures from chat messages (1.19+) to prevent message tracking—also disables chat reporting. Server-side enforcement may override this.<br>客戶端模組，移除1.19+聊天訊息加密簽名以防追蹤，並禁用檢舉功能。伺服器強制設定時本模組無效。 |
| [NoExpensive](https://modrinth.com/mod/2nz0kJ1N) | A lightweight mod that removes anvil cost limits and allows any enchantment combinations—fully configurable with cross-version compatibility.<br>輕量級模組，移除鐵砧成本限制並允許任意附魔組合。可完整自訂設定，相容新舊Minecraft版本。 |
| [Raknetify](https://modrinth.com/mod/5IovSY3u) | <br><br>A Fabric mod using RakNet to reduce latency on unstable/rate-limited connections—supports ViaVersion client/server.<br>Fabric模組，透過RakNet協議降低不穩定/限速網路下的延遲，相容ViaVersion客戶端與伺服器端。 |
| [Sound Physics Remastered](https://modrinth.com/mod/qyVF9oeo) | A mod adding realistic sound physics.<br>實現真實空間音效的模組。 |
| [Very Many Players (Fabric)](https://modrinth.com/mod/wnEe9KBa) | Very Many Players<br><br>A Fabric mod optimizing high-playercount servers with intelligent caching and responsive networking—early development, pair with Lithium.<br>Fabric 模組，透過智慧快取與響應式網路優化高人數伺服器。早期開發階段，建議搭配 Lithium 使用。 |
| [Your Options Shall Be Respected (YOSBR)](https://modrinth.com/mod/WwbubTsV) | A Fabric mod that auto-copies your predefined default configs from /config/yosbr/ when files are missing—no manual setup after mod updates.<br>Fabric 模組，當設定檔遺失時自動從 /config/yosbr/ 複製預先定義的預設設定，模組更新後無需手動重新配置。 |

### Tools

| Mod | Description |
|---|---|
| [Bridging Mod](https://modrinth.com/mod/lO3s8hjs) | A building assist mod that lets you place blocks in hidden gaps (up/down/horizontal) with visual crosshair guidance. Use only in singleplayer or trusted small servers—bannable on public networks.<br>建築輔助模組，可在隱形縫隙（上下/水平）放置方塊，並以準心提示位置。僅限單人遊戲或受信任的小型伺服器使用，公開網路使用將遭封鎖。 |
| [Cesium Storage Format](https://modrinth.com/mod/2fspKUWt) | An experimental mod replacing Minecraft's Anvil storage with LMDB database and zstd compression—reduces disk space usage while ensuring data consistency. Converts existing worlds with in-game tool.<br>實驗性模組，以LMDB資料庫和zstd壓縮技術取代Minecraft原生儲存格式，有效減少硬碟空間佔用並確保資料一致性。支援透過遊戲內工具轉換現有世界。使用前務必備份世界。 |
| [Component Viewer](https://modrinth.com/mod/P9vIqP8R) | <br><br>A client-side mod displaying and copying item stack components via tooltips—press J to configure. Data exports in clean SNBT/JSON format; pairs well with Tooltip Scroll for large datasets.<br>客戶端模組，透過提示框顯示並複製物品組件數據，按 J 鍵即可設定。支援乾淨格式的 SNBT/JSON 輸出，搭配 Tooltip Scroll 模組可處理大型數據集。 |
| [Dynamic Crosshair](https://modrinth.com/mod/ZcR9weSm) | A mod that hides the crosshair when idle or holding tools, and changes its style based on targets—fully customizable per situation.<br>根據情境自動隱藏或切換準星樣式的模組：閒置/手持工具時隱藏，瞄準目標時切換樣式，所有設定皆可自訂調整。 |
| [Litematica Printer](https://modrinth.com/mod/3llatzyE) | <br><br>A Litematica addon that auto-places correct blocks around you for rapid large-scale builds. Toggle with CAPS_LOCK; hold V to force-place. Skips unsupported blocks.<br>Litematica 附加模組，自動放置周圍方塊加速大型建築的模組。按CAPS_LOCK開關，按住V強制放置，跳過不支援方塊。 |
| [Litematica](https://modrinth.com/mod/bEpr0Arc) | <br><br>A modern schematic mod for Fabric/LiteLoader/Rift with Schematica's core features—printer functionality available via extensions.<br>現代化方塊結構模組，支援Fabric/LiteLoader/Rift平台，完整繼承Schematica核心功能（不含自動放置），自動放置需搭配擴充模組使用。 |
| [Map In Slot](https://modrinth.com/mod/EpKz6cxj) | A minimal mod that displays map previews directly in hotbar/inventory slots—no more opening each map individually while organizing.<br>極簡模組，在熱鍵欄與物品欄中直接顯示地圖內容預覽，整理地圖時無需逐張點開查看。 |
| [MiniHUD](https://modrinth.com/mod/UMxybHE8) | <br><br>A client-side mod providing customizable mini F3 info lines and overlay renderers—including light levels, slime chunks, world spawn regions, structure boundaries, and shape tools.<br>客戶端模組，提供可自訂的迷你F3資訊列及疊加渲染功能：光照等級、黏液方塊生成區、世界重生點區域、建築結構邊界與幾何形狀工具。 |
| [Replanter Plus](https://modrinth.com/mod/is7374ZC) | A client-side mod that automatically harvests and replants crops with right-click—auto-switches to Fortune tools and applies bone meal. Supports wheat, carrots, cocoa beans, nether warts, and modded crops.<br>客戶端模組，右鍵自動收穫並重種作物，智慧切換幸運附魔工具與骨粉使用。支援小麥、胡蘿蔔、可可豆、地獄疙瘩及自訂模組作物。 |
| [WorldEdit](https://modrinth.com/mod/1u6JkXh5) | An in-game map editor with region selection, schematics, copy/paste, brushes, and scripting—usable in creative or temporarily in survival mode.<br>遊戲內地圖編輯器，支援區域選取、結構存檔、複製貼上、筆刷與腳本功能，適用於創造模式或生存模式臨時使用。 |
| [WTHIT](https://modrinth.com/mod/6AQIaxuO) | <br><br>A Hwyla/WAILA fork displaying block/fluid tooltips with server-side support for NBT data inspection. Extendable via API and Megane for tech mod compatibility.<br>Hwyla/WAILA 分支模組，顯示方塊/流體提示資訊，進階功能需伺服器安裝以讀取NBT數據。透過API與Megane擴充支援科技模組相容性。 |
| [Xaero's Minimap](https://modrinth.com/mod/1bokaNcj) | A minimap mod showing terrain/players/mobs with customizable waypoints and automatic cave mode.<br>顯示地形/玩家/生物的迷你地圖模組，支援自訂路標點與洞穴自動切換。 |
| [Xaero's World Map](https://modrinth.com/mod/NcUtCpym) | A full-screen auto-mapping mod that records explored terrain with cave dimension support—fully integrates with Xaero's Minimap.<br>全螢幕自動地圖模組，記錄探索區域並支援洞穴維度，與Xaero's Minimap深度整合。 |


<!-- MODS_END -->

## ShaderPacks
<!-- SHADERS_START -->
## ShaderPacks

| Name | Description |
|---|---|
| [Bliss Shaders](https://modrinth.com/mod/ZvMtQlho) | <br><br>A shaderpack reborn from Chocapic13 with plug-and-play simplicity. Creates magical water reflections, glowing plants in jungles, and dreamy End skies—all while running smoothly on mid-tier hardware.<br>源自Chocapic13的即裝即用光影包，讓叢林植物泛起柔光、終界天空如夢似幻，水面倒影流光溢彩。中階電腦可流暢運行的精緻光影效果。<br><br>See more at https://github.com/X0nk/Bliss-Shader/ |
| [BSL Shaders - Classic](https://modrinth.com/mod/pgzM6RBY) | A shaderpack honoring vanilla aesthetics with subtle dreamy enhancements. Continuously updated since its inception, it has witnessed Minecraft's shader evolution. Cherished for buttery-smooth performance and masterful optimization despite forgoing extreme visual effects.<br>一款忠於原版美學、細膩融入夢幻質感的光影包。從早期持續更新至今，見證 Minecraft 光影的演進歷程。雖捨棄極致視效，卻以絲滑流暢度與精湛優化贏得眾多玩家青睞。  <br><br>See more at https://bitslablab.com/bslshaders/ |
| [BSL Shaders](https://modrinth.com/mod/Q1vvjJYV) | A shaderpack delivering a vibrant cartoony atmosphere while retaining dreamy softness. Continuously updated since its inception, it has witnessed Minecraft's shader evolution. Beloved for exceptional optimization and fluid performance despite not featuring cutting-edge visuals.<br>散發鮮活卡通氛圍且保有夢幻柔美的光影包。從早期持續更新至今，見證 Minecraft 光影的演進歷程。雖無頂級畫面特效，卻憑藉卓越的流暢度與優化深受玩家喜愛。<br><br>See more at https://bitslablab.com/bslshaders/ |
| [Complementary Shaders - Reimagined](https://modrinth.com/mod/HVnmMxH1) | A shaderpack where Minecraft's soul shines brighter: torches dance with playful sparks, cobblestone paths whisper nostalgia, and sunsets paint the sky in pixel-perfect watercolors. Smooth performance on entry-level systems.<br>讓Minecraft靈魂綻放的光影包：火把躍動俏皮星火，鵝卵石小徑喚起童年回憶，夕陽以像素水彩浸染天際。低階設備也能享受的流暢光影體驗。<br><br>See more at https://www.complementary.dev/ |
| [Complementary Shaders - Unbound](https://modrinth.com/mod/R6NEzAwj) | A shaderpack that turns Minecraft into a nature documentary: sunlight filters through leaves like stained glass, stone caves glow with hidden warmth, and raindrops leave trails on your screen. Balanced visuals and performance for modest hardware.<br>將Minecraft化作自然紀錄片的光影包：陽光穿透樹葉如彩繪玻璃，石礦洞穴泛著溫潤微光，雨滴在螢幕滑落痕跡。低階設備也能享受的流暢光影體驗。<br><br>See more at https://www.complementary.dev/ |
| [Ebin Resurrected](https://modrinth.com/mod/VP9picRm) | A shaderpack that makes Minecraft visuals pop with vibrant colors and smooth performance. Rain makes stones look wet, torches cast colorful glows, and grass moves naturally—runs well even on older PCs. Perfect for survival players who want eye candy without lag.<br>以鮮豔色彩與流暢效能強化 Minecraft 視覺的光影包。下雨時石頭會反光、火把散發彩色光芒、草地自然搖曳，舊電腦也能順暢運行。專為生存玩家設計：享受華麗畫面，告別卡頓延遲。<br><br>See more at https://github.com/jbritain/Ebin-Shaders-Resurrected/ |
| [Eclipse Shader](https://modrinth.com/mod/) | Eclipse - A Bliss Edit<br><br>A Bliss-based shaderpack adding celestial events with guaranteed eclipses, player water ripples, auroras, handheld shadows, and dynamic weather systems—enhanced mod support for Voxy/Colorwheel.<br>基於Bliss深度改版的光影包，加入保證每年發生的日月蝕、玩家水面漣漪、極光效果、手持物陰影與動態天氣系統，強化Voxy/Colorwheel等模組相容性。<br><br>See more at https://github.com/Merlin1809/Eclipse-Shader/ |
| [FastPBR](https://modrinth.com/mod/ygChbn8J) | Shaders<br><br>A lightweight shaderpack that renders lifelike clouds, fog, and soft shadows—runs full speed even on decade-old laptops without sacrificing visual quality.<br>輕量級光影包，雲層霧氣如臨實境，陰影過渡自然柔和。十年老電腦也能全速運行，畫面精緻不減，下雨天探索洞穴依然流暢。<br><br>See more at https://rre36.com/ |
| [Glimmer](https://modrinth.com/mod/PgdT4v4a) | <br><br>A shaderpack that runs smoothly on any PC while adding vibrant colored torchlight, endless oceans, and realistic water reflections—no complex settings needed.<br>為任何電腦量身打造的流暢光影包，火把散發彩色光芒，海洋延伸至視野盡頭，水面倒影清晰真實。一鍵啟用，無需繁瑣設定。<br><br>See more at https://github.com/jbritain/glimmer-shaders/ |
| [Helian-MMCO](https://modrinth.com/mod/) | (Sundial Lite edit)<br><br>A personal Sundial Lite modification featuring refined cloud patterns, balanced color grading, and custom AGX filters—adds dynamic atmospheric lighting with enhanced dimension support.<br>Sundial Lite個人修改版，提供精緻雲層樣式、平衡色調與自訂AGX濾鏡，強化動態大氣光照並完善下界/末地支援。<br><br>See more at https://github.com/MoAoXnX/Helian-mmco_Sundial-Lite_edit |
| [Kappa Shader](https://modrinth.com/mod/Y8161YLz) | A shaderpack that paints Minecraft with real-world light: where shadows breathe, fog hugs the valleys at dawn, and every material feels tangible. Premium visuals requiring high-end hardware for optimal performance.<br>以現實光影重塑Minecraft的光影包：陰影會呼吸、晨霧輕擁山谷，方塊材質觸手可及。需要高階硬體才能流暢運行的頂級光影效果。<br><br>See more at https://rre36.com/kappa-shader/ |
| [MakeUp - Ultra Fast](https://modrinth.com/mod/izsIPI7a) | <br><br>A highly customizable shaderpack focused on optimal performance-to-quality ratio—with every effect toggleable to match your hardware. Compatible with OptiFine and Iris.<br>專為性能與畫質平衡打造的可定制光影包，所有效果皆可獨立開關以適配不同硬體等級。相容OptiFine與Iris載入器。<br><br>See more at https://github.com/javiergcim/MakeUpUltraFast/ |
| [Miniature Shader](https://modrinth.com/mod/UaS8ROxa) | s<br><br>A shaderpack that keeps Minecraft’s iconic blocky charm with crisp water/ice reflections and brighter glowing blocks—runs buttery-smooth even on decade-old laptops.<br>保留 Minecraft 標誌性方塊美學的光影包：水面冰面倒影清晰，發光方塊效果更明顯。輕量設計，十年老電腦也能流暢運行。<br><br>See more at https://github.com/mateuskreuch/minecraft-miniature-shader |
| [Noble Shaders](https://modrinth.com/mod/sclYVqbt) | A shaderpack that adds realistic torchlight on tools, dynamic water ripples, and detailed rain/stars—optimized to run smoothly on mid-to-low-end PCs without frame drops during mining.<br>為工具增添真實火把光效、水面波紋動態變化、雨雪與星空細節強化的光影包。針對中低階電腦優化，挖礦時畫面依然流暢穩定。<br><br>See more at https://github.com/BelmuTM/Noble/ |
| [Nostalgia Shader](https://modrinth.com/mod/xEItlMn3) | A shaderpack that revives Minecraft's classic blocky clouds and dreamy color tones while adding modern effects like realistic lighting and reflections—optimized for mainstream systems.<br>重現Minecraft經典方塊雲與夢幻色調的光影包，同時加入真實光影反射等現代特效。中階電腦可流暢運行的精緻光影效果。<br><br>See more at https://rre36.com/nostalgia-shader/ |
| [Oct-Path](https://modrinth.com/mod/KOQHPy4R) | Shaders<br><br>A shaderpack that extends ray tracing to the full 64x64 chunk render distance with accurate water reflections and visible mob/player shadows—completes Octray Rewrite's unfinished features while maintaining smooth gameplay.<br>基於光線追蹤技術的光影包，支援完整64x64區塊渲染距離，修復水體倒影與玩家/生物陰影缺失問題。繼承八叉樹加速結構，大幅減少計算負載，確保遊戲流暢不中斷。 |
| [Octray Rewrite](https://modrinth.com/mod/) | An experimental raytraced shader optimized with sparse octree allocation and branchless path-tracing—extends lighting range across vast landscapes.<br>實驗性光追光影，透過稀疏八叉樹配置與無分支路徑追蹤技術，實現超遠距離照明效果，為廣闊地景帶來真實光影。<br><br>See more at https://github.com/BruceKnowsHow/OctrayRewrite/ |
| [Photon Shaders](https://modrinth.com/mod/lLqFfGNs) | Proton Shaders<br><br>A buttery-smooth shaderpack that transforms Minecraft into a living painting—breathtaking sunsets, dynamic weather, and water that feels alive. Outperforms BSL in beauty while maintaining accessibility on lower-end machines.<br>讓Minecraft化身流動畫卷的流暢光影包，醉人夕陽、會呼吸的天氣、波光粼粼的水面。畫面精緻度超越BSL，低階設備也能享受的流暢光影體驗。<br><br>See more at https://github.com/sixthsurge/photon/ |
| [Potato Shaders](https://modrinth.com/mod/WX4iF5Cj) | Potato Shader<br><br>A shaderpack designed for extremely low-end PCs—adds subtle bloom, water effects, and color depth without dynamic shadows. Fully customizable via in-game settings for smooth performance.<br>專為超低階電腦設計的輕量光影包：提供泛光效果、動態水體、色彩增強，無動態陰影。遊戲內設定完整自訂，確保流暢運行。  <br><br>See more at https://rre36.com/potato-shader/ |
| [Rethinking Voxels](https://modrinth.com/mod/kmwfVOoi) | A shaderpack where torchlight dances as colored shadows on cave walls, stained-glass windows paint rainbows on stone floors, and every mob blocks light like real matter. Still in development—but for strong PCs, it already turns Minecraft into a breathing diorama.<br>讓火把在岩壁躍動彩影、彩繪玻璃為石地灑落虹光的光影包。每隻生物都如實物阻擋光線，晨霧中透出的陽光如金縷般真實。雖處開發階段且需高階硬體，已能將方塊世界化作會呼吸的立體劇場。  <br><br>See more at https://github.com/gri573/rethinking-voxels/ |
| [Revelation](https://modrinth.com/mod/) | A physically based shaderpack built from scratch with heuristic optimizations—delivers impressive visuals while maintaining low system requirements.<br>基於物理渲染的原創光影包，採用啟發式優化技術，在低階設備上也能呈現出色畫質與流暢體驗。<br><br>See more at https://github.com/HaringPro/Revelation/ |
| [Scrumptious Shayders](https://modrinth.com/mod/) | <br><br>A BSL Shaders fork adding Voxy support.<br>BSL光影的分支版本，專為支援Voxy而設計。<br><br>See more at https://github.com/LordChrom/ScrumptiousShayders |
| [SEUS PTGI GFME](https://modrinth.com/mod/) | SEUS PTGI GeForceLegend's Modified Edition<br><br>A performance-optimized PTGI variant featuring per-pixel path tracing with PBR support, enhanced vanilla lighting colors, auto texture resolution for incomplete packs, and metal sunlight caustics. Requires powerful hardware to showcase its full potential.<br>Installation: Execute the JAR file with PTGI HRR 2.1 file<br><br>深度優化的PTGI改版光影，搭載PBR材質支援的逐像素光線追蹤、強化原版光源色彩、自動適配不完整材質包，並新增金屬陽光焦散效果。需要高階硬體才能流暢運行的頂級光影效果。<br>安裝: 請同時勾選 SEUS PTGI HRR 2.1，並進入光影包資料夾執行此JAR檔案<br><br>See more at https://github.com/GeForceLegend/SEUS_PTGI_GFME |
| [SEUS PTGI HRR 3](https://modrinth.com/mod/) | A next-generation path-traced shader delivering cinematic lighting and realistic material interactions without requiring RTX hardware—evolved from SEUS PTGI's custom software ray tracing foundation. <br>次世代路徑追蹤光影包，提供電影級光照與真實材質互動效果，無需RTX顯示卡即可運作—基於SEUS PTGI自研軟體級光追架構全面進化。<br><br>See more at https://www.patreon.com/posts/download-seus-3-60268558 |
| [SEUS PTGI HRR Test 2.1](https://modrinth.com/mod/) | An experimental ray-traced shader featuring improved HRR technology that reduces ghosting and enhances image quality, with Parallax Occlusion Mapping for screen-space shadows and motion effects. <br>實驗性光追光影包，搭載改良HRR技術有效減少殘影並提升畫質，支援視差遮蔽貼圖實現螢幕空間陰影與動態效果。<br><br>See more at https://www.patreon.com/posts/download-seus-2-45141775 |
| [Shrimple](https://modrinth.com/mod/BS9T99lD) | A shaderpack that keeps Minecraft's vanilla look intact while adding optional features like swaying plants, colored torchlight that reacts to handheld items, and glass-tinted lighting. Experimental ray-traced block-light shadows included; water reflections and global illumination remain basic.<br>保留 Minecraft 原版視覺風格的光影包，提供植物搖曳、手持光源、玻璃染色光效等可選功能。含實驗性方塊光源光追陰影，水體反射與全局光照效果維持基礎水平。<br><br>See more at https://github.com/Null-MC/Shrimple/ |
| [Soft Voxels Lite](https://modrinth.com/mod/Xl42lc6c) | A shaderpack that creates soft, natural lighting without harsh shadows—features gentle overcast skies, waving plants, and water reflections. Free lightweight version of Soft Voxels with full path-traced lighting.<br>以柔和自然光影取代生硬陰影的光影包，呈現陰天般戶外視覺，支援植物搖曳與水體反射。Soft Voxels精簡免費版，完整保留光線追蹤核心效果。<br><br>See more at https://rre36.com/soft-voxels/ |
| [Solas Shader](https://modrinth.com/mod/EpQFjzrQ) | <br><br>A fantasy-style shaderpack delivering clear bright visuals, glowing ores in caves, and breathtaking End dimensions—all with smooth performance on mid-tier PCs. Supports Iris/OptiFine and PBR resource packs.<br>奇幻風格光影包，畫面清晰明亮，礦洞內礦石自然發光，末地星雲效果震撼。中階電腦流暢運行，完整支援Iris/OptiFine及PBR材質包。<br><br>See more at https://github.com/Septonious/Solas-Shader/ |
| [Sundial Lite](https://modrinth.com/mod/) | A free open-source shaderpack implementing physically-based deferred rendering with configurable quality settings. Features realistic shadows, atmospheric effects, and PBR material support. Temporarily excludes path-traced effects and Nether/End dimensions found in the paid version.<br>免費開源光影包，採用物理基礎延遲渲染技術，提供可調節畫質設定。具備真實陰影、大氣效果與PBR材質支援。暫時不含付費版的光線追蹤效果與下界/終界維度特效。<br><br>See more at https://github.com/GeForceLegend/Sundial-Lite |
| [UShader](https://modrinth.com/mod/UDDa70lE) | A shaderpack reviving the iconic SEUS v10.1 lighting style with added volumetric fog and smoother performance—nostalgic visuals without original's lag.<br>重現 SEUS v10.1 標誌性光影風格的懷舊光影包，新增體積霧效果，效能超越原版且流暢運行。<br><br>See more at https://rre36.com/ushader/ |
| [VTXS Screen Space Demo](https://modrinth.com/mod/DIAdpUOD) | An experimental shaderpack focused on screen-space ray tracing for playable visuals—adds water waves, glass/water reflections, colored shadows, and armor glow while keeping gameplay smooth.<br>實驗性光影包，專注於屏幕空間光線追蹤技術：提供水波紋、玻璃/水面反射折射、彩色陰影、盔甲反光效果，確保遊戲流暢運行。 |

<!-- SHADERS_END -->

## ResourcePacks
<!-- RESOURCES_START -->
## ResourcePacks

| Name | Description |
|---|---|
| [3D Default](https://modrinth.com/mod/5aPp18Lx) | GeForceLegend's 3D Default<br><br>A lightweight 3D resource pack enhancing vanilla models with authentic item appearances and OptiFine/PBR support—minimal performance impact across Minecraft 1.8 to latest versions.<br>輕量級3D資源包，為原版模型增添真實感，支援物品精準外觀與OptiFine/PBR效果，在Minecraft 1.8至最新版本間維持低效能負擔。 |
| [Fancy Crops](https://modrinth.com/mod/UGEVQ6t9) | (Bee's) Fancy Crops<br><br>A resource pack that beautifies farms with varied crop textures and redesigned seeds/hay bales.<br>美化農場的資源包：作物紋理變化豐富，種子與乾草捆外觀精緻升級。 |
| [FPBR](https://modrinth.com/mod/nvEpbd8t) | GN FPBR<br><br>A free 128x vanilla enhancement texture pack by G2FISH (GNwork team member) that enables PBR, parallax, and subsurface scattering with Chinese shaders like itt/itrp—low system requirements with modular installation.<br>由GNwork成員G2FISH打造的128x免費原版增強材質包，搭配itt/itrp等國產光影實現PBR、視差與次表面散射效果。模組化安裝設計，低配電腦流暢運行，中配可開光影絲滑體驗。<br><br>See more at https://fishbai.cloud/wiki.html/ |
| [Low Fire](https://modrinth.com/mod/1jZGHJ05) | A resource pack that shortens in-game fire height to prevent view obstruction.<br>縮短遊戲內火焰高度的資源包，有效防止視野被遮擋。 |
| [Low Shield](https://modrinth.com/mod/CZrLuVQo) | A resource pack that lowers first-person shield height to prevent view obstruction.<br>降低第一人稱盾牌高度的資源包，有效防止視野被遮擋。 |
| [Nautilus 3D](https://modrinth.com/mod/1MyOrwfu) | Nautilus3D<br><br>A vanilla-style 3D resource pack focused on decorative blocks—featuring randomized bookshelves/ores, animated stonecutter, perfect leaf clusters, and epic trident model. Highly optimized with themed menus.<br>專注裝飾性方塊的原版風格3D資源包：書架與礦石隨機紋理、動畫切石機、茂密樹葉、三叉戟手持模型。高度優化，整合主題化選單與介面。<br><br>See more at https://github.com/FabianMPunkt/Nautilus3D/ |
| [SPBR](https://modrinth.com/mod/aNcOVoD7) | Shulker's PBR<br><br>A resource pack that adds realistic material depth to vanilla 16x textures—featuring PBR stonecutter surfaces, wood with layered depth effects, subsurface scattering on organic blocks, and fully 3D-modeled rails/pistons. Based on VNR textures with parallax mapping.<br>為原版16x材質注入真實質感的資源包：石頭切石機具物理反光、木紋呈現立體層次、生物方塊透出次表面散射效果，軌道與活塞升級全3D模型。基於VNR材質，整合視差貼圖技術。<br><br>See more at https://github.com/ShulkerSakura/SPBR/ |

<!-- RESOURCES_END -->


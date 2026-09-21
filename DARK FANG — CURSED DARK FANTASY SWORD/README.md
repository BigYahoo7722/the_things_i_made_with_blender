# DARK FANG — CURSED DARK FANTASY SWORD

A dark-fantasy sword 3D asset project built for **Blender 5.2.2 LTS**, with a production-oriented workflow covering blockout, hard-surface detailing, high-poly refinement, microdetail, damage and wear, PBR materials, UVs, 4K texture maps, game-ready LODs, presentation, camera setup, validation, and multi-format export.

The project is named **DARK FANG** and is intended as a reusable fantasy-sword asset and as a documented Blender production example.

## Languages

[فارسی](#persian) · [English](#english) · [Español](#spanish) · [Français](#french) · [Deutsch](#german) · [العربية](#arabic) · [简体中文](#chinese)

---

<a id="persian"></a>
## فارسی

**DARK FANG — شمشیر فانتزی تاریک نفرین‌شده**

این مخزن شامل یک دارایی سه‌بعدی شمشیر فانتزی تاریک با نام **DARK FANG** است که برای بازی، هنر، سینماتیک، آموزش، نمونه‌کار، نمونه‌سازی و سایر کاربردهای قانونی تهیه شده است. Pipeline پروژه برای **Blender 5.2.2 LTS** طراحی شده و شامل Blockout، طراحی Hard-Surface، High Poly، Microdetail، Damage/Wear، متریال PBR، UV، بافت‌های 4K، زنجیرهٔ LOD، Presentation، کنترل دوربین، QA و خروجی چندفرمتی است.

### وضعیت فنی فعلی

- Blender: **5.2.2 LTS**
- LOD0: **12,148 tris** — هدف حدود 12K
- LOD1: **4,998 tris** — هدف حدود 5K
- LOD2: **1,989 tris** — هدف حدود 2K
- LOD3: **1,006 tris** — هدف حدود 1K
- UV: موجود و فعال (`UVMap_LOD0`)
- QA نهایی: بدون face degenerate، edge با طول صفر، loose geometry یا non-manifold edge در گزارش Stage 17
- Textureها: Albedo، Normal، Roughness، Metallic و AO با رزولوشن **4096×4096**
- خروجی‌ها: **FBX، GLB، OBJ** برای هر چهار LOD
- فایل نهایی Blender: `DARK_FANG_AAA_FINAL_V4.blend`
- اصلاح اتصال Grip/Pommel: تأیید شده
- Stage 17 Final Re-Export + QA: **PASS**

### Presentation

برای ارائهٔ شبکه‌های اجتماعی، یک سیستم چهار دوربینهٔ جداگانه برای رندر پرترهٔ اینستاگرام ایجاد شده است:

- خروجی: **1080×1350 px**
- نسبت تصویر: **4:5**
- تعداد نماها: **4**
- اجرای رندر از طریق Timeline Camera Markers و `Ctrl+F12`
- مسیر هدف خروجی: `B:\blender\DARK_FANG_INSTAGRAM`

### لایسنس و استفادهٔ مجدد

این پروژه، تا حدی که قانون قابل‌اجرا اجازه دهد، تحت **CC0 1.0 Universal** به مالکیت عمومی واگذار شده است. هدف این واگذاری این است که افراد بتوانند محتوای مشمول این پروژه را بدون درخواست اجازهٔ قبلی کپی، تغییر، ترکیب، بازنشر، توزیع، فروش و در پروژه‌های تجاری یا غیرتجاری استفاده کنند.

**ذکر نام سازنده اجباری نیست.** اعتبار دادن اختیاری است.

دامنهٔ CC0 عمدتاً به حقوق کپی‌رایت و حقوق مرتبط مربوط است. CC0 به‌طور خودکار حقوق مستقلی مانند علائم تجاری، اختراعات/پتنت‌ها، حقوق اشخاص ثالث، حریم خصوصی، تصویر یا سایر حقوقی را که جداگانه وجود دارند، واگذار یا پاک نمی‌کند. بنابراین کاربر باید برای کاربرد مشخص خود بررسی کند که آیا حق دیگری مطرح است یا خیر.

این واگذاری فقط برای محتوایی معتبر است که منتشرکننده مالک آن باشد یا اختیار قانونی لازم برای انتشار آن را داشته باشد.

متن حقوقی پروژه در [`LICENSE`](./LICENSE) قرار دارد و متن رسمی CC0 1.0 نیز از Creative Commons قابل دسترسی است.

### سلب مسئولیت

این پروژه **as-is / همان‌طور که هست** ارائه می‌شود و هیچ تضمینی دربارهٔ سازگاری با همهٔ موتورهای بازی، نرم‌افزارها، نسخه‌های Blender، ابزارهای شخص ثالث یا تمام شرایط استفاده ارائه نمی‌کند. بررسی حقوق اشخاص ثالث و الزامات قانونی استفادهٔ موردنظر بر عهدهٔ کاربر است.

---

<a id="english"></a>
## English

**DARK FANG — Cursed Dark Fantasy Sword**

This repository contains **DARK FANG**, a dark-fantasy sword 3D asset intended for games, art, cinematics, education, portfolios, prototypes, and other lawful uses. The production workflow targets **Blender 5.2.2 LTS** and covers blockout, hard-surface detailing, high-poly refinement, microdetail, damage/wear, PBR materials, UVs, 4K texture maps, LODs, presentation, camera setup, QA, and multi-format export.

### Current technical status

- Blender: **5.2.2 LTS**
- LOD0: **12,148 tris** — target ~12K
- LOD1: **4,998 tris** — target ~5K
- LOD2: **1,989 tris** — target ~2K
- LOD3: **1,006 tris** — target ~1K
- UVs: present and active (`UVMap_LOD0`)
- Final QA: no degenerate faces, zero-length edges, loose geometry, or non-manifold edges were reported in the Stage 17 QA report
- Textures: Albedo, Normal, Roughness, Metallic, and AO at **4096×4096**
- Export formats: **FBX, GLB, OBJ** for all four LODs
- Final Blender project: `DARK_FANG_AAA_FINAL_V4.blend`
- Grip/Pommel alignment: approved
- Stage 17 final re-export + QA: **PASS**

### Presentation

A separate four-camera presentation setup is included for Instagram portrait renders:

- Output: **1080×1350 px**
- Aspect ratio: **4:5**
- Views: **4**
- Render sequencing: Timeline Camera Markers + `Ctrl+F12`
- Intended output path: `B:\blender\DARK_FANG_INSTAGRAM`

### License and reuse

To the extent permitted by applicable law, this project is dedicated to the public domain under **CC0 1.0 Universal**. The intent is to allow people to copy, modify, remix, publish, redistribute, sell, and use the covered project content in commercial or non-commercial work without asking for prior permission.

**Attribution is not required.** Credit is optional.

CC0 primarily addresses copyright and related rights. It does not automatically waive separate rights such as trademarks, patents, third-party rights, privacy rights, publicity/personality rights, or other rights that may exist independently. Users are responsible for checking whether such rights or restrictions apply to their intended use.

This dedication should only be applied to content that the publisher owns or is legally authorized to release.

See [`LICENSE`](./LICENSE) for the project license notice and the official CC0 1.0 legal text referenced there.

### Disclaimer

The project is provided **as-is**, without warranties. No guarantee is made that it will work with every game engine, DCC application, Blender version, exporter/importer, or third-party tool. Users are responsible for checking applicable third-party rights and other legal requirements for their intended use.

---

<a id="spanish"></a>
## Español

**DARK FANG — Espada de Fantasía Oscura Maldita**

Este repositorio contiene **DARK FANG**, un recurso 3D de espada de fantasía oscura destinado a videojuegos, arte, cinemáticas, educación, portfolios, prototipos y otros usos legales. El flujo de producción está diseñado para **Blender 5.2.2 LTS** e incluye blockout, detalles hard-surface, refinamiento high-poly, microdetalle, daño/desgaste, materiales PBR, UV, mapas 4K, LOD, presentación, cámaras, QA y exportación multiformato.

### Estado técnico actual

- Blender: **5.2.2 LTS**
- LOD0: **12.148 tris** — objetivo ~12K
- LOD1: **4.998 tris** — objetivo ~5K
- LOD2: **1.989 tris** — objetivo ~2K
- LOD3: **1.006 tris** — objetivo ~1K
- UV: presentes y activos (`UVMap_LOD0`)
- QA final: no se reportaron caras degeneradas, aristas de longitud cero, geometría suelta ni aristas non-manifold en el informe QA de Stage 17
- Texturas: Albedo, Normal, Roughness, Metallic y AO a **4096×4096**
- Formatos: **FBX, GLB, OBJ** para los cuatro LOD
- Proyecto final de Blender: `DARK_FANG_AAA_FINAL_V4.blend`
- Alineación Grip/Pommel: aprobada
- Reexportación final + QA de Stage 17: **PASS**

### Presentación

Se incluye una configuración independiente de cuatro cámaras para renders verticales de Instagram:

- Salida: **1080×1350 px**
- Relación: **4:5**
- Vistas: **4**
- Secuencia: marcadores de cámara en la línea de tiempo + `Ctrl+F12`
- Ruta prevista: `B:\blender\DARK_FANG_INSTAGRAM`

### Licencia y reutilización

En la medida permitida por la ley aplicable, este proyecto se dedica al dominio público mediante **CC0 1.0 Universal**. La intención es permitir copiar, modificar, remezclar, publicar, redistribuir, vender y utilizar el contenido cubierto en obras comerciales o no comerciales sin solicitar permiso previo.

**No se requiere atribución.** El crédito es opcional.

CC0 se ocupa principalmente de los derechos de autor y derechos conexos. No renuncia automáticamente a derechos independientes como marcas, patentes, derechos de terceros, privacidad, imagen/ publicity o personalidad, ni a otros derechos que puedan existir por separado. Cada usuario debe verificar si tales derechos o restricciones afectan a su uso previsto.

Esta dedicación solo debe aplicarse a contenido que el publicador posea o esté legalmente autorizado a liberar.

Consulta [`LICENSE`](./LICENSE) para el aviso de licencia del proyecto y el texto legal oficial de CC0 1.0 referenciado allí.

### Descargo de responsabilidad

El proyecto se proporciona **tal cual**, sin garantías. No se garantiza la compatibilidad con todos los motores de juego, aplicaciones DCC, versiones de Blender, importadores/exportadores o herramientas de terceros. Cada usuario debe comprobar los derechos de terceros y demás requisitos legales aplicables a su uso.

---

<a id="french"></a>
## Français

**DARK FANG — Épée de Fantasy Sombre Maudite**

Ce dépôt contient **DARK FANG**, une ressource 3D d'épée de fantasy sombre destinée aux jeux, à l'art, aux cinématiques, à l'enseignement, aux portfolios, aux prototypes et à d'autres usages légaux. Le workflow de production cible **Blender 5.2.2 LTS** et comprend le blockout, les détails hard-surface, le high-poly, le microdétail, les dommages/usures, les matériaux PBR, les UV, les textures 4K, les LOD, la présentation, les caméras, le QA et l'export multiformat.

### État technique actuel

- Blender : **5.2.2 LTS**
- LOD0 : **12 148 tris** — objectif ~12K
- LOD1 : **4 998 tris** — objectif ~5K
- LOD2 : **1 989 tris** — objectif ~2K
- LOD3 : **1 006 tris** — objectif ~1K
- UV : présents et actifs (`UVMap_LOD0`)
- QA final : aucune face dégénérée, arête de longueur nulle, géométrie libre ou arête non-manifold signalée dans le rapport QA du Stage 17
- Textures : Albedo, Normal, Roughness, Metallic et AO en **4096×4096**
- Formats : **FBX, GLB, OBJ** pour les quatre LOD
- Projet Blender final : `DARK_FANG_AAA_FINAL_V4.blend`
- Alignement Grip/Pommel : validé
- Réexport final + QA Stage 17 : **PASS**

### Présentation

Une configuration séparée à quatre caméras est incluse pour les rendus verticaux Instagram :

- Sortie : **1080×1350 px**
- Ratio : **4:5**
- Vues : **4**
- Séquence : marqueurs de caméra de la timeline + `Ctrl+F12`
- Chemin prévu : `B:\blender\DARK_FANG_INSTAGRAM`

### Licence et réutilisation

Dans la mesure permise par la loi applicable, ce projet est dédié au domaine public sous **CC0 1.0 Universal**. L'objectif est de permettre à chacun de copier, modifier, remixer, publier, redistribuer, vendre et utiliser le contenu couvert dans des œuvres commerciales ou non commerciales sans demander d'autorisation préalable.

**L'attribution n'est pas obligatoire.** Le crédit est facultatif.

CC0 concerne principalement le droit d'auteur et les droits voisins. Elle ne renonce pas automatiquement à des droits distincts tels que les marques, brevets, droits de tiers, vie privée, droit à l'image ou autres droits pouvant exister indépendamment. Chaque utilisateur doit vérifier les droits et restrictions applicables à son utilisation.

Cette dédicace ne doit s'appliquer qu'aux contenus que le diffuseur possède ou qu'il est légalement autorisé à libérer.

Voir [`LICENSE`](./LICENSE) pour l'avis de licence du projet et le texte juridique officiel CC0 1.0 qui y est référencé.

### Avertissement

Le projet est fourni **en l'état**, sans garantie. Aucune compatibilité n'est garantie avec tous les moteurs de jeu, applications DCC, versions de Blender, outils d'import/export ou logiciels tiers. L'utilisateur doit vérifier les droits de tiers et les autres exigences légales applicables à son usage.

---

<a id="german"></a>
## Deutsch

**DARK FANG — Verfluchtes Dark-Fantasy-Schwert**

Dieses Repository enthält **DARK FANG**, ein 3D-Schwert-Asset im Dark-Fantasy-Stil für Spiele, Kunst, Cinematics, Bildung, Portfolios, Prototypen und andere rechtmäßige Nutzungen. Der Produktions-Workflow zielt auf **Blender 5.2.2 LTS** und umfasst Blockout, Hard-Surface-Details, High-Poly-Überarbeitung, Microdetail, Beschädigung/Abnutzung, PBR-Materialien, UVs, 4K-Texturen, LODs, Präsentation, Kameras, QA und den Export in mehrere Formate.

### Aktueller technischer Status

- Blender: **5.2.2 LTS**
- LOD0: **12.148 Tris** — Ziel ~12K
- LOD1: **4.998 Tris** — Ziel ~5K
- LOD2: **1.989 Tris** — Ziel ~2K
- LOD3: **1.006 Tris** — Ziel ~1K
- UVs: vorhanden und aktiv (`UVMap_LOD0`)
- Finale QA: Im QA-Bericht von Stage 17 wurden keine degenerierten Flächen, Kanten mit Nulllänge, lose Geometrie oder Non-Manifold-Kanten gemeldet
- Texturen: Albedo, Normal, Roughness, Metallic und AO in **4096×4096**
- Formate: **FBX, GLB, OBJ** für alle vier LODs
- Finales Blender-Projekt: `DARK_FANG_AAA_FINAL_V4.blend`
- Grip/Pommel-Ausrichtung: bestätigt
- Stage 17 Final Re-Export + QA: **PASS**

### Präsentation

Eine separate Vier-Kamera-Konfiguration für vertikale Instagram-Renderings ist enthalten:

- Ausgabe: **1080×1350 px**
- Seitenverhältnis: **4:5**
- Ansichten: **4**
- Sequenzierung: Timeline-Kameramarker + `Ctrl+F12`
- Vorgesehener Pfad: `B:\blender\DARK_FANG_INSTAGRAM`

### Lizenz und Wiederverwendung

Soweit gesetzlich zulässig wird dieses Projekt unter **CC0 1.0 Universal** der Allgemeinheit zur freien Nutzung überlassen. Ziel ist, dass jeder den abgedeckten Inhalt ohne vorherige Genehmigung kopieren, ändern, remixen, veröffentlichen, weitergeben, verkaufen und in kommerziellen oder nicht-kommerziellen Arbeiten verwenden kann.

**Eine Namensnennung ist nicht erforderlich.** Eine Erwähnung ist freiwillig.

CC0 betrifft hauptsächlich Urheberrechte und verwandte Rechte. Sie verzichtet nicht automatisch auf eigenständige Rechte wie Marken, Patente, Rechte Dritter, Datenschutz-, Persönlichkeits- oder Bildrechte oder andere unabhängig bestehende Rechte. Nutzer müssen selbst prüfen, ob solche Rechte oder Beschränkungen für die geplante Nutzung gelten.

Die Widmung darf nur auf Inhalte angewendet werden, die der Veröffentlichende besitzt oder für deren Freigabe er rechtlich befugt ist.

Siehe [`LICENSE`](./LICENSE) für den Lizenzhinweis und den dort referenzierten offiziellen CC0-1.0-Rechtstext.

### Haftungsausschluss

Das Projekt wird **wie besehen** und ohne Gewähr bereitgestellt. Es wird keine Kompatibilität mit allen Game-Engines, DCC-Anwendungen, Blender-Versionen, Import-/Export-Werkzeugen oder Drittanbieter-Software garantiert. Die Prüfung von Drittanbieterrechten und sonstigen rechtlichen Anforderungen liegt beim Nutzer.

---

<a id="arabic"></a>
## العربية

**DARK FANG — سيف فانتازيا مظلمة ملعون**

يحتوي هذا المستودع على **DARK FANG**، وهو أصل ثلاثي الأبعاد لسيف من فانتازيا مظلمة، مخصص للألعاب والفن والمشاهد السينمائية والتعليم وملفات الأعمال والنماذج الأولية وغيرها من الاستخدامات المشروعة. صُمم مسار الإنتاج حول **Blender 5.2.2 LTS** ويشمل الـBlockout وتفاصيل Hard-Surface وHigh-Poly والـMicrodetail والضرر والتآكل ومواد PBR وUV وخرائط 4K ومستويات LOD والعرض والكاميرات وQA والتصدير إلى عدة صيغ.

### الحالة التقنية الحالية

- Blender: **5.2.2 LTS**
- LOD0: **12,148 tris** — الهدف ~12K
- LOD1: **4,998 tris** — الهدف ~5K
- LOD2: **1,989 tris** — الهدف ~2K
- LOD3: **1,006 tris** — الهدف ~1K
- UV: موجودة وفعالة (`UVMap_LOD0`)
- الفحص النهائي: لم يتم تسجيل وجوه Degenerate أو حواف بطول صفر أو هندسة منفصلة أو حواف Non-Manifold في تقرير QA للمرحلة 17
- الخرائط: Albedo وNormal وRoughness وMetallic وAO بدقة **4096×4096**
- الصيغ: **FBX وGLB وOBJ** لجميع مستويات LOD الأربعة
- ملف مشروع Blender النهائي: `DARK_FANG_AAA_FINAL_V4.blend`
- محاذاة Grip/Pommel: معتمدة
- إعادة التصدير النهائي + QA في Stage 17: **PASS**

### العرض

يتضمن المشروع إعداداً منفصلاً لأربع كاميرات مخصصاً للرندر العمودي على Instagram:

- الدقة: **1080×1350 px**
- النسبة: **4:5**
- عدد الزوايا: **4**
- التسلسل: Camera Markers على الـTimeline مع `Ctrl+F12`
- مسار الإخراج المقصود: `B:\blender\DARK_FANG_INSTAGRAM`

### الترخيص وإعادة الاستخدام

إلى الحد الذي يسمح به القانون المعمول به، يتم تخصيص هذا المشروع للملك العام بموجب **CC0 1.0 Universal**. والهدف هو السماح لأي شخص بنسخ المحتوى المشمول وتعديله وإعادة مزجه ونشره وإعادة توزيعه وبيعه واستخدامه في أعمال تجارية أو غير تجارية دون طلب إذن مسبق.

**لا يلزم ذكر اسم المؤلف.** ذكر المصدر اختياري.

تتعامل CC0 أساساً مع حقوق المؤلف والحقوق ذات الصلة. ولا تتنازل تلقائياً عن حقوق مستقلة مثل العلامات التجارية أو براءات الاختراع أو حقوق الأطراف الثالثة أو الخصوصية أو الحقوق المتعلقة بالصورة أو الشخصية أو غيرها من الحقوق التي قد توجد بشكل مستقل. يجب على المستخدم التحقق من أي حقوق أو قيود تنطبق على استخدامه المقصود.

يجب تطبيق هذا التخصيص فقط على المحتوى الذي يملكه الناشر أو يملك السلطة القانونية لإطلاقه.

راجع [`LICENSE`](./LICENSE) لإشعار الترخيص والنص القانوني الرسمي لـCC0 1.0 المشار إليه هناك.

### إخلاء المسؤولية

يُقدَّم المشروع **كما هو** ومن دون ضمانات. لا يوجد ضمان للتوافق مع جميع محركات الألعاب أو تطبيقات DCC أو إصدارات Blender أو أدوات الاستيراد/التصدير أو برامج الجهات الخارجية. يتحمل المستخدم مسؤولية التحقق من حقوق الغير والمتطلبات القانونية الأخرى.

---

<a id="chinese"></a>
## 简体中文

**DARK FANG — 被诅咒的黑暗奇幻长剑**

本仓库包含 **DARK FANG**，一套黑暗奇幻风格的 3D 长剑资产，可用于游戏、美术、电影化项目、教育、作品集、原型以及其他合法用途。制作流程以 **Blender 5.2.2 LTS** 为基础，包括 Blockout、硬表面细节、高模精修、Microdetail、损伤/磨损、PBR 材质、UV、4K 纹理、LOD、展示、摄像机、QA 以及多格式导出。

### 当前技术状态

- Blender：**5.2.2 LTS**
- LOD0：**12,148 tris** — 目标约 12K
- LOD1：**4,998 tris** — 目标约 5K
- LOD2：**1,989 tris** — 目标约 2K
- LOD3：**1,006 tris** — 目标约 1K
- UV：存在并处于激活状态（`UVMap_LOD0`）
- 最终 QA：Stage 17 QA 报告中未发现退化面、零长度边、松散几何或 Non-Manifold 边
- 纹理：Albedo、Normal、Roughness、Metallic、AO，均为 **4096×4096**
- 格式：四个 LOD 均提供 **FBX、GLB、OBJ**
- 最终 Blender 项目：`DARK_FANG_AAA_FINAL_V4.blend`
- Grip/Pommel 对齐：已确认
- Stage 17 最终重新导出 + QA：**PASS**

### 展示

项目包含独立的四摄像机 Instagram 竖屏渲染设置：

- 输出：**1080×1350 px**
- 画幅：**4:5**
- 视角数量：**4**
- 渲染序列：Timeline Camera Markers + `Ctrl+F12`
- 目标输出路径：`B:\blender\DARK_FANG_INSTAGRAM`

### 许可证与再利用

在适用法律允许的最大范围内，本项目依据 **CC0 1.0 Universal** 贡献至公共领域。其目的在于允许任何人无需事先许可即可复制、修改、混合、发布、再分发、出售以及将所涵盖的项目内容用于商业或非商业作品。

**无需署名。** 自愿注明来源即可。

CC0 主要涉及版权和相关权利。它不会自动放弃商标、专利、第三方权利、隐私权、肖像/人格权益或其他独立存在的权利。用户应自行确认具体用途是否受到这些权利或其他法律限制的影响。

只有在发布者拥有相关内容的权利或具有合法授权时，才能将本声明适用于这些内容。

请参阅 [`LICENSE`](./LICENSE) 以及其中引用的官方 CC0 1.0 法律文本。

### 免责声明

本项目按“**现状**”提供，不提供任何保证。无法保证其与所有游戏引擎、DCC 软件、Blender 版本、导入/导出工具或第三方软件兼容。用户应自行检查第三方权利及其具体用途所涉及的其他法律要求。

---

## Project structure

The final delivery package is organized approximately as follows:

```text
DARK_FANG_DELIVERY_V4/
├── 01_BLEND/
│   └── DARK_FANG_AAA_FINAL_V4.blend
├── 02_FBX/
│   ├── DARK_FANG_LOD0.fbx
│   ├── DARK_FANG_LOD1.fbx
│   ├── DARK_FANG_LOD2.fbx
│   └── DARK_FANG_LOD3.fbx
├── 03_GLB/
│   ├── DARK_FANG_LOD0.glb
│   ├── DARK_FANG_LOD1.glb
│   ├── DARK_FANG_LOD2.glb
│   └── DARK_FANG_LOD3.glb
├── 04_OBJ/
│   ├── DARK_FANG_LOD0.obj
│   ├── DARK_FANG_LOD1.obj
│   ├── DARK_FANG_LOD2.obj
│   └── DARK_FANG_LOD3.obj
├── 05_TEXTURES_4K/
│   ├── DARK_FANG_Albedo_4K.png
│   ├── DARK_FANG_Normal_4K.png
│   ├── DARK_FANG_Roughness_4K.png
│   ├── DARK_FANG_Metallic_4K.png
│   └── DARK_FANG_AO_4K.png
└── 06_DOCS/
```

## Presentation files

The repository may also contain Blender scripts for generating or updating presentation cameras and render automation. The dedicated Instagram render setup targets:

```text
B:\blender\DARK_FANG_INSTAGRAM
```

The render setup uses four camera states so that a single animation render can produce four 4:5 presentation frames.

## Credits

Attribution is **not required** under CC0. A link to this repository is appreciated but not required.

## Legal note

This README is a practical project summary. It is not a substitute for the CC0 1.0 Universal legal code or for legal advice. The operative license terms are those stated in [`LICENSE`](./LICENSE) and the applicable CC0 legal text referenced there.

The publisher makes no representation that every file in the repository is free of third-party rights unless expressly stated. Users should review files, bundled assets, external references, trademarks, patents, and other rights where relevant to their intended use.

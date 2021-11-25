<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->
- [TranslateOnLinux](#translateonlinux)
- [CAT TOOLS](#cat-tools)
  * [OFFLINE CAT TOOLS](#offline-cat-tools)
  * [OmegaT](#omegat)
  * [CafeTran Espresso](#cafetran-espresso)
  * [Memsource Editor for Desktop](#memsource-editor-for-desktop)
  * [WordFast Pro](#wordfast-pro)
  * [Swordfish Translation Editor](#swordfish-translation-editor)
  * [Fluency Now](#fluency-now)
  * [Heartsome Translation Studio](#heartsome-translation-studio)
  * [WordFast Classic](#wordfast-classic)
  * [Other](#other)
  * [ONLINE CAT TOOLS](#online-cat-tools)
  * [Memsource Editor for Web](#memsource-editor-for-web)
  * [MateCat](#matecat)
  * [Smartcat](#smartcat)
  * [Wordfast Anywhere](#wordfast-anywhere)
  * [XTM Cloud](#xtm-cloud)
  * [Wordbee](#wordbee)
  * [Termsoup](#termsoup)
  * [Other](#other-1)
- [Translation related tasks and tools](#translation-related-tasks-and-tools)
  * [Alignment](#alignment)
  * [Handling tags](#handling-tags)
  * [Translation Memory (TMX) Editing - Maintenance](#translation-memory--tmx--editing---maintenance)
  * [Segmentation - SRX editors](#segmentation---srx-editors)
  * [Term extraction](#term-extraction)
    + [Monolingual term extraction](#monolingual-term-extraction)
    + [Bilingual term extraction](#bilingual-term-extraction)
  * [Terminology management](#terminology-management)
    + [File formats](#file-formats)
    + [Tools](#tools)
- [Office software](#office-software)
- [Grammar checkers - Writing aids](#grammar-checkers---writing-aids)
- [QA tools](#qa-tools)
- [Proofreading and Revising (Track changes, compare documents)](#proofreading-and-revising--track-changes--compare-documents-)
- [Various localization-related utilities](#various-localization-related-utilities)
- [Subtitling](#subtitling)
- [Transcription](#transcription)
- [Dictionary lookup](#dictionary-lookup)
- [Project management & Invoicing](#project-management---invoicing)
- [DTP - Image localization](#dtp---image-localization)
- [Speech recognition (STT)](#speech-recognition--stt-)
- [Text-to-speech (TTS)](#text-to-speech--tts-)
- [PDFs](#pdfs)
  * [PDF Editors](#pdf-editors)
  * [PDF Readers](#pdf-readers)
  * [PDF-related utilities](#pdf-related-utilities)
  * [PDF TO TEXT](#pdf-to-text)
  * [OCR](#ocr)
- [E-book management & conversion](#e-book-management---conversion)
- [File and Folder comparison (DIFF) tools](#file-and-folder-comparison--diff--tools)
- [Desktop search - Full text index](#desktop-search---full-text-index)
- [File rename utilities](#file-rename-utilities)
- [Text editors](#text-editors)
- [Productivity tools selection](#productivity-tools-selection)
  * [AutoKey (Py3)](#autokey--py3-)
  * [ibus-typing-booster](#ibus-typing-booster)
  * [Reduce eye-strain](#reduce-eye-strain)
  * [Clipboard managers](#clipboard-managers)
  * [Screenshots](#screenshots)
  * [Screen recording - Screencasting](#screen-recording---screencasting)
  * [Time and Project tracking](#time-and-project-tracking)
  * [Pomodoro timers](#pomodoro-timers)
  * [Unit conversion](#unit-conversion)
  * [On-screen keyboard](#on-screen-keyboard)
- [Running GNU-Linux on Windows via WLS](#running-gnu-linux-on-windows-via-wls)
- [Running Windows applications on Linux](#running-windows-applications-on-linux)
  * [Natively on WINE](#natively-on-wine)
  * [Through a Windows Virtual Machine (VM)](#through-a-windows-virtual-machine--vm-)
  * [Via Dual Boot - On a separate machine](#via-dual-boot---on-a-separate-machine)
- [Updates](#updates)
- [Feedback](#feedback)
<!-- /TOC -->

# TranslateOnLinux

It is entirely possible to work as a professional translator while running a GNU/Linux distribution as your chosen operating system.

This wiki aims to provide a list of desktop and web solutions for linguists who use a GNU/Linux OS for their work. The listed software should provide a comprehensive toolbox to fit most translation needs.

Inspiration for this list: the website [LinuxForTranslators.com](https://www.linuxfortranslators.org/) by [Marc Prior](https://www.marcprior.de/en/), and the now defunct [tuxtrans](https://web.archive.org/web/20210227043921/https://www.uibk.ac.at/tuxtrans/), a GNU/Linux distribution specifically targeted at translators by [Peter Sandrini](http://www.petersandrini.net/en-index.html), along with its list of [installed software](https://web.archive.org/web/20210227063021/https://www.uibk.ac.at/tuxtrans/software.html).

For a more general overview, head over to [LinuxForTranslators.com](https://www.linuxfortranslators.org/). For discussing any GNU/Linux-related topics in a professional translation/localization context, consider subscribing to the [LinuxForTranslators@groups.io](https://groups.io/g/LinuxForTranslators) mailing list. 

*Curated by [Jean Dimitriadis](https://www.proz.com/translator/2042360) (EN-FR/EL-FR translator).*

# CAT TOOLS

Some popular computer-aided translation (CAT) tools, such as SDL Trados, memoQ or Déjà Vu are only Windows-compatible, but they are far from being the only options. There are some powerful translation tools that can run on GNU/Linux. It is worth noting almost all of them can handle (albeit with some limitations) Trados SDLXLIFF files and/or SDLPPX packages, which are often sent out by translation agencies.

These include the following:

## OFFLINE CAT TOOLS

## OmegaT

[OmegaT](https://omegat.org/) is a free-libre/open source translation memory application written in Java.

Don’t let its simple interface fool you, OmegaT boasts excellent features, some of which (like team projects) are mostly found in expensive proprietary CAT tools.

Some highlights include:

- Easy to use, uncluttered interface
- Fuzzy matching
- Automatic propagation of translations
- Unlimited number of translation memories (TMX format)
- Unlimited number of glossaries (CSV and TBX format) with recognition of inflected forms
- Looking up terms in the project, in reference translation memories, glossaries, and reference documents
- Projects with an unlimited number of folders and files, in all accepted formats
- Team projects with an unlimited number of translators (in SVN and GIT repositories)
- Right to left and bidirectional writing management
- The ability to apply various segmentation rules
- Tag protection and validation
- Morphological recognition (Lucene tokenization/lemmatization)
- Spell checking (Hunspell)
- Linguistic/grammar checking (LanguageTool)
- Dictionaries (mono and multilingual) in StarDict and Lingvo DSL formats (although GoldenDict might be a better external alternative, see Dictionaries section)
- Machine translation (Google Translate, Microsoft Translator, DeepL, Apertium, Yandex, MyMemory, IBM Watson, Language Translator, etc.)
- More than 50 supported file formats (with the Okapi plugin)
- Public API for plugins: Additional file formats (Okapi), Local machine translation (Apertium)
- Running scripts written in Groovy and JavaScript, further extending its capabilities (example: a script offers an extensive QA feature)
- Multiword auto-completion from glossary entries, abbreviation list, history completion and history prediction
- Graphic aligner for all supported formats
- External search on the Internet
- Software and documentation localized in many languages
- Complete project and TM Statistics
- A thriving community and super-fast support via its [omegat-users sourceforge mailing list](https://sourceforge.net/projects/omegat/lists/omegat-users)

**Platforms:** GNU/Linux, Windows, macOS.
**Supported formats:** More than 50 formats (with the Okapi plugin), including Microsoft Word, Excel and PowerPoint, LibreOffice, HTML, TTX and SDLXLIFF (Trados), TXML (Wordfast Pro), IDML (InDesign) and PDF (plain text and Iceni Infix export).
**Support and manual:** [Documentation and manual](https://omegat.org/documentation), [support page](https://omegat.org/support).
**License:** Free-Libre/Open Source Software (GPLv2).
**Cost:** Gratis (donations welcome).
**Reviews:** [OmegaT](https://omegat.org/reviews), [ProZ](https://www.proz.com/software-comparison-tool/tool/omegat/82), [G2](https://www.g2.com/products/omegat/reviews).

## CafeTran Espresso

[CafeTran Espresso](https://cafetran.com/) is a feature-rich CAT tool that is fun to use, built from the ground up by a developer cum translator, which shows in many ways.

Here are some highlights:

- Highly configurable GUI and extensive keyboard shortcuts
- Many supported file formats
- Excellent intercompatibility with external CAT tools: SDL Trados and memoQ files and packages, but also Wordfast Pro, Deja Vu, Memsource, Transit, etc.
- Open standards: uses XLIFF, TMX, SRX and tab-delimited TXT file formats
- Matchboard: all resources at a glance
- Context-aware Auto-assembling feature
- Flexible Translation Memory handling and options, TMs can store segments and/or fragments
- Easy (multilingual) glossary format and term management features (alternative to TM for storing fragments)
- Total Recall for storing and recalling really big TMs (millions of segments)
- Auto-completion, suggests words on the fly
- Quick search bar for querying various resources
- Advanced Find & Replace dialog box
- Excellent filtering and concordance capabilities
- Smart word selection, paste by selecting text
- Drag-and-drop for many functions
- Easy tag insertion
- Quick typos correction by cycling through alternative spellings
- Clever text transposition and case handling
- Auto-propagation (with various settings and exceptions allowed)
- Query your favorite Internet resources straight from within CafeTran
- Integrated MT engines (via an API connection or a web interface): DeepL, Google Translate, Microsoft Translator, Yandex.Translate, MyMemory, IBM Watson, Amazon Translate, etc.
- Amazon Polly Text To Speach (TTS) integration for listening source/target segments read aloud.
- Rich QA features and Statistics
- Export and reimport bilingual Word documents for external proofreading or review
- Integration with ProZ.com and TM-Town
- Powerful TMX editing and maintenance features
- Alternative clipboard workflow to translate unsupported formats
- Special workflow for translating paper documents and images
- Network memory server for remote work or teamwork
- Active community and very attentive developer, interested in user feedback and ideas for future development

**Platforms:** GNU/Linux, Windows, macOS.
**Supported formats:** [file formats](https://github.com/idimitriadis0/TheCafeTranFiles/wiki/4-File-formats#file-formats-overview).
**Support:** [Solutions](https://cafetran.freshdesk.com/support/solutions) (Knowledge Base), [official forum and support](https://cafetran.freshdesk.com/support/discussions), [reference documents](https://github.com/idimitriadis0/TheCafeTranFiles/wiki).
**License:** Closed source.
**Demo version:** no time limit, TM files up to 1000 TUs in total and glossaries no larger than 500 terms.
**Cost:** [Licensing options](https://www.cafetran.com/get-cafetran/) // Also, full access for [ProZ.com Plus members](https://www.proz.com/pages/Plus-subscriber-checklist) (currently extended to paying ProZ members). // Also available through ProZ Translator Group Buying  ([TGB](https://www.proz.com/tgb)) campaign.
**Reviews:** [ProZ](https://www.proz.com/software-comparison-tool/tool/cafetran_espresso/97).

## Memsource Editor for Desktop

Memsource is an easy, streamlined and powerful online CAT tool, which also offers a desktop editor (compatible with Linux and written in Qt), hence its inclusion in this section. It provides a complete translation environment that allows you to set up your own workflow, and share projects with your vendors.

Among other things, it offers an extensive [file format support](https://help.memsource.com/hc/en-us/articles/360014358579-Supported-File-Formats), with interesting file filter and [pre-translation](https://help.memsource.com/hc/en-us/articles/360013675780-Pre-translation-Overview) options, a host of [MT engines](https://help.memsource.com/hc/en-us/articles/360012620459) and MT-related functions (it is one of the tools of choice for MT post-editing) and features a thorough support website. It also sports a useful [in-context preview](https://help.memsource.com/hc/en-us/articles/360012775960-In-Context-Preview) feature and can handle large remote TMs and termbases as well. It is used by some agencies who offer project-based licenses as it allows for remote management and distribution of translation jobs, keeping track of translators' progress in real time. The web version is reportedly quite slower than the desktop version. There is a port for Android and iOS.

Online/Offline tool
**Platforms:** GNU/Linux, Windows, macOS, Android, iOS.
**Supported formats:** [file formats](https://help.memsource.com/hc/en-us/articles/360014358579).
**Support and manual:** [Support](https://help.memsource.com/hc/en-us), [Memsource Editor for Desktop and for Web documentation](https://help.memsource.com/hc/en-us/categories/115000351051-Translating).
**License:** Closed source.
**Demo**: 30-day trial / Free Personal edition (maximum two files at a time).
**Cost:** [editions and pricing](https://www.memsource.com/pricing/).
**Reviews:** [ProZ](https://www.proz.com/software-comparison-tool/tool/memsource_cloud/40), [G2Crowd](https://www.g2crowd.com/products/memsource/reviews), [Capterra](https://www.capterra.com/p/151871/Memsource-Cloud/).

## WordFast Pro

Among the major commercial TM tools, WordFast Pro is the only one that is truly cross-platform. It is available as a standalone application (in contrast to WordFast Classic, which is Word-based).

[WordFast Pro](https://www.wordfast.com/products/wordfast_pro), whose interface and underlying technology was first implemented as version 4.0 is now at version 6.6.x. 

The legacy [WordFast Pro 3](https://www.wordfast.com/products/wordfast_pro_3) was last updated to version 3.4.14 in August 2018 and is no longer in development. It still works in many systems and some users continue to use it.

While these tools have a different translation interface, both share a number of features, such as multiple supported file formats (and file filter options), unlimited TM and Glossary access (as well as remote access, via [WordFast Server](https://www.wordfast.com/products_wordfast_server.html)), Machine Translation integration, advanced time-saving features and real-time assurance (Transcheck).

In addition, the current WFP offers a WYSIWYG interface for formatting tags, Target-only Live Preview, Segment Filtering, Multilingual Translation Projects, Export and Import Translation Packages (including SDL Trados files and packages) and the ability to Chain (virtually merge) files for translation consistency.

The demo version has some limitations, but it is not time-based, making it useful to keep around, especially for round trip scenarios, since it supports many file formats and offers nice filter options.

**Platforms:** GNU/Linux, Windows, macOS.
**Supported formats:** [WFP 3](https://www.wordfast.com/products/wordfast_pro_3), [WFP 6](https://www.wordfast.com/products/wordfast_pro) (check specifications).
**Support and manual:** [Wordfast support page](https://www.wordfast.com/training_support), [support wiki](https://www.wordfast.net/wiki/Wordfast_Pro_5) and [manual](https://wordfast.com/WFP/5.0/Wordfast_Pro_Help.htm), videos and training courses are available as well.
**License:** Closed source.
**Demo:** Wordfast offers a demo version that runs without a paid license for translation memories (TM) of up to 500 translation units, making it possible to use Wordfast on actual translation projects before you decide to purchase. You can also register for a 30 day, fully functional trial license.
**Cost:** [pricing](http://www.wordfast.com/checkout?product=PRO). Also available through ProZ Translator Group Buying  ([TGB](https://www.proz.com/tgb)) campaign.
**Reviews:** [ProZ](https://www.proz.com/software-comparison-tool/tool/wordfast_pro/22), [Capterra](https://www.capterra.com/p/159255/Wordfast-Pro/reviews/).

## Swordfish Translation Editor

[Swordfish](https://www.maxprograms.com/products/swordfish.html) IV is an advanced  cross-platform CAT tool based on open standards, designed for demanding professional translators. 

It supports exchanging TMX (Translation Memory eXchange) and uses the GlossML glossary format. It includes a super fast Internal database server and integrated support for [RemoteTM Web Server](https://www.maxprograms.com/products/remotetm.html). You can also use third-party database engines like Oracle 10g or MySQL 5.x for storing TM and terminology data.

Swordfish supports a host of file formats. It is also compatible with other CAT tools, since it supports the XLIFF (including Trados Studio SDLXLIFF files and SDLPPX packages, Wordfast Pro TXLF fiiles and MemoQ mqXLIF files), Uncleaned RTF, TTX, TTX Exchange and TXML (Worfast Pro and GlobaLink).

Other features include In-Context Exact Matches, full interface customization, segment filtering, comfortable proofreading and advanced TM/MT engines (including Azure Translator Text (Microsoft), DeepL, Google Cloud Translation, MyMemory and Yandex).

Strongly committed to open source software, the developer, Maxprograms, publishes all its tools as [open source](https://github.com/rmraya?tab=repositories) and free to use. The various [localization software and utilities](https://www.maxprograms.com/products/index.html) include [Stingray](https://www.maxprograms.com/products/stingray.html) (document aligner), [TMXEditor](https://www.maxprograms.com/products/tmxeditor.html), [Fluenta](https://www.maxprograms.com/products/fluenta.html) DITA Translation Manager, as well as [Anchovy](https://www.maxprograms.com/products/anchovy.html) (Glossary manager and term extractor), [SRXEditor](https://www.maxprograms.com/products/srxeditor.html) (Segmentation Rules editor), [OpenXLIFF filters](https://www.maxprograms.com/products/openxliff.html) (which can be used with other CAT tools), [XLIFF Manager](https://maxprograms.com/products/xliffmanager.html) and [TMXValidator](https://www.maxprograms.com/products/tmxvalidator.html). 

**Platforms:** GNU/Linux, Windows, macOS.
**Supported formats:** [General documentation, XML formats and Software development](https://www.maxprograms.com/products/swordfish.html).
**Support and manual:** User guide ([PDF](https://www.maxprograms.com/support/swordfish.pdf) and [web](https://www.maxprograms.com/support/swordfish.html)), [Getting started](https://www.maxprograms.com/tutorials/SwfishGettingStarted.html), [Groups.io support group](https://groups.io/g/maxprograms/) (The group is intended for supporting all tools published at Maxprograms, not only Swordfish).
**License:** Open source ([Eclipse Public License v1.0](http://www.eclipse.org/legal/epl-v10.html)).
**Demo version**: 30-day trial.
**Cost:** Free to use (requires building the binaries from [source code](https://github.com/rmraya/Swordfish)), with subscriptions for support and binaries available on the [online store](http://www.maxprograms.com/store/buy.html).
**Reviews:** [Proz](https://www.proz.com/software-comparison-tool/tool/swordfish_translation_editor/89).

## Fluency Now

Fluency Now is an easy to use full-featured CAT tool suite that’s affordable for freelancers and organizations alike.

Some of its [product features](https://www.westernstandard.com/Fluency/TranslationSuite.aspx) include:

- Easy to learn, customizable interface
- Great file compatibility
- Built-in terminology available in over 35 language pairs
- Support for TMX, SDLTM, TTX,txt, MDB, ACCDB translation memories
- Support for txt, TBX, SDLTB, and other terminology formats
- Pseudo Translation
- Alignment Tool
- Transcription Tool
- Multiple Machine translation engine support
- TTS and Speech to command with extensive Accessibility support
- Auto Correct, Auto Text, Term suggest, and TM suggestions while you type
- Supports right to left languages
- Customizable (dynamic) web resources
- Live preview
- Informative toolbars, statistics and project analysis
- Quick help and technical support
- HIPAA & HITECH Compliant
- Support for Fluency TM & Term Server (Entrerprise Edition)
- Support for Fluency Flow Project Management (Entrerprise Edition)

**Platforms:** GNU/Linux, Windows, macOS.
**Supported formats:** [Benefits & Features](https://www.westernstandard.com/Fluency/TranslationSuite.aspx).
**Support and manual:** [Fluency 101](https://fluencytranslation.wordpress.com/fluency-101/), [video tutorials](https://www.westernstandard.com/Fluency/Video_Tutorials.aspx).
**License:** Closed source.
**Demo version**: 15-day trial.
**Cost:** Monthly and yearly [subscription](https://www.westernstandard.com/Store/Purchase.aspx).
**Reviews:** [Proz](https://www.proz.com/software-comparison-tool/tool/fluency_translation_suite_2013/55), [Capterra](https://www.capterra.com/p/167274/Fluency-Now/).

## Heartsome Translation Studio

[Heartsome](https://github.com/heartsome/translationstudio8) is a discontinued commercial CAT tool software that is now open sourced and offered gratis.

The software itself is getting old (it is no longer developed for more than 5 years now), but sports some nice capabilities that make it useful to keep around.

It also offers a separate [Heartsome TMX Editor](https://github.com/heartsome/tmxeditor8) for editing TMX memories.

**Platforms:** GNU/Linux, Windows, macOS.
**Supported formats:** see [GitHub](https://github.com/heartsome/translationstudio8) page.
**Support:** [GitHub page](https://github.com/heartsome/translationstudio8) has links for user manual, quick start guide and file conversion guide.
**License:** Open source (GPLv2).
**Cost:** Gratis.
**Reviews:** [Proz](https://www.proz.com/software-comparison-tool/tool/heartsome_translation_studio/85).

## WordFast Classic

[WordFast Classic](https://www.wordfast.com/products/products_wordfast) is a CAT tool that operates entirely inside of Microsoft Word. Since some versions of MS Word can be installed and run via the Wine compatibility layer (see related section below), WordFast Classic can be used in GNU/Linux.

Features include an intuitive interface, user-defined macros, integration with machine translation and external dictionaries and real-time QA.

**Platforms:** GNU/Linux, Windows, macOS.
**Supported formats:** Word.
**Support:** [support wiki](https://www.wordfast.net/wiki/Wordfast_Classic), [user manual](https://www.wordfast.net/wiki/Wordfast_Classic_User_Manual).
**License:** Closed source.
**Demo:** [Demo version](https://wordfast.net/index.php?go=demo) with no time limit, up to 1000 translation units, limited MT.
**Cost:** [Price](http://www.wordfast.com/checkout?product=CLA).
**Reviews:** [Proz](https://www.proz.com/software-comparison-tool/tool/heartsome_translation_studio/85).

## Other

[Virtaal](https://virtaal.readthedocs.io/en/latest/): Virtaal is an easy and lightweight tool that opens Gettext (.po, .mo), XLIFF, TMX and TBX files, among other formats. Even if its nice feature set may not fully appeal to professional translators, it represents a very good utility to use as a quick viewer for the above-mentioned bilingual file types. It should be noted that it hasn't seen active development since 2017 and is in maintenance mode; some distros (like Fedora) do not ship it.

[Lokalize](https://userbase.kde.org/Lokalize): Lokalize is a computer-aided translation (CAT) tool, a full-featured GUI application for translators written from scratch using the KDE4 framework in 1999 and ported to the KDE5 framework in 2007. Aside from basic editing of PO files with nifty auxiliary details, it integrates support for glossary, translation memory, diff-modes for QA, project management, pology/posieve verification, etc. Mostly interesting for free software localization. It is tightly integrated with KDE localization together with kdesvn, which makes it ideal for localization of KDE software, while also serving as a full-blown localization tool.

[QtLinguist](https://doc.qt.io/qt-5/linguist-translators.html): Developed by The Qt Company to localize primarily Qt applications, this tool is able to translate TS, PO and XLIFF files. Despite being proprietary, it is open source and generally available on Linux via the package qttools5/qt5-qttools/qt5tools (name depends on the distribution) and via website download. Downloading from your distribution is recommended.

[DGT-OmegaT](http://185.13.37.79/) is an active fork of OmegaT (currently, the 3.4. branch), developed by the Directorate-General for Translation of the European Commission, adding some [specific features](http://185.13.37.79/?q=node/2) built for their own needs. Some features, like Tagwipe, have been integrated into the original OmegaT software. [Documentation](http://185.13.37.79/?q=node/36). [Download](http://185.13.37.79/?q=node/31).

[Anaphraseus](http://sourceforge.net/projects/anaphraseus/files/) (WordFast Classic-like CAT tool available as an OpenOffice/LibreOffice extension)

[Esperantilo](http://www.esperantilo.org/tm/) (no new versions since 2012)

[OmegaT+](http://omegatplus.sourceforge.net/) (OmegaT fork, no new version since 2012)

## ONLINE CAT TOOLS

While problematic from a privacy and freedom point of view, the advent of Cloud/web-based CAT tools has added several GNU/Linux compatible solutions to the existing arsenal.

## Memsource Editor for Web

Mentioned along with Memsource Editor for Desktop in the above section. Please note the desktop version still requires some steps to be completed in the online version. 

## MateCat

[MateCat](https://matecat.com/) is a free, easy to use, enterprise-level online tool developped by Translated, designed to make translation, post-editing and outsourcing easy and to provide a complete set of features to manage and monitor translation projects.

MateCat supports a host of file formats and various MT engines (including Modern MT and free access to MyMemory MT service/Public TM). It also sports a nifty [Aligner](https://www.matecat.com/plugins/aligner/index#/).

Given its feature-set, it can also be used in a round trip scenario (as an additional filter to handle file types unsupported by other CAT tools). [Read more about this here](https://github.com/idimitriadis0/TheCafeTranFiles/wiki/4-File-formats#matecat-recommended).

**Supported formats**: [70 formats](https://site.matecat.com/support/introducing-matecat/supported-browser-languages-formats/).
**Support and manual:** [Documentation and support](https://site.matecat.com/support/).
**License:** Software based on mostly open source components.
**Cost:** Free (registration recommended).
**Reviews:** [Proz](https://www.proz.com/software-comparison-tool/tool/matecat/134), [G2](https://www.g2.com/products/matecat/reviews).

The completely open source version of the webserver can also be [installed offline](https://site.matecat.com/installation-guide/).

**Warning:** By default, MateCat stores your translated segments in the public MyMemory TM. To make sure this does not happen unwillingly, create a private TM resource: In the Project creation page, click on Settings (Alternatively, in the TM and glossary field, expand the drop-down menu and select Create resource). Click on + New resource button in the opened dialog. Give the TM an optional name. Hit Confirm. You will see that “MyMemory: Collaborative translation memory” resource is Enabled for Lookup, but not set to be Updated anymore. That way, translated segments will only be stored in your private resources.

**Warning:** Matecat only officially supports Chrome/Chromium and will go out of its way to block your access if you're using a different browser. It is possible to use it with other browsers such as Firefox by switching your user agent, but speed/performance might be slightly worse.

## Smartcat

[Smarcat](https://smartcat.ai/) is an intuitive, feature-rich computer-assisted translation web app. It provides a full set of translation automation technologies for companies and translators and makes it easy for them to connect and collaborate.

It directly integrates with Paypal and Payoneer as well as local and international wire transfer. A Marketplace section is available for seeking translation jobs (though often low-payed as it allows for values below 1 cent), which can then allow for direct referrals. 

**Supported formats**: [file formats](https://help.smartcat.com/hc/en-us/articles/360006979511-File-formats-supported-in-Smartcat/).
**Support and manual:** [Documentation and support](https://help.smartcat.ai/hc/en-us).
**License:** Closed source.
**Cost:** Mostly free (registration needed), billable OCR service.
**Reviews:** [Proz](https://www.proz.com/software-comparison-tool/tool/smartcat/145), [G2](https://www.g2.com/products/smartcat/reviews), [Capterra](https://www.capterra.fr/software/155255/smartcat).

## Wordfast Anywhere

[WordFast Anywhere](https://www.freetm.com/) is a free and complete online CAT tool, one of the oldest of its kind, allowing translators to work from anywhere, provided they have an Internet connection and a web browser.

**Supported formats**: txml, txt, doc, docx, xls, xlsx, htm, html, inx, indml, pdf, jsp, asp, odt, tif, rtf, ppt, pptx,mif, ttx, txlf, xlf, xliff, sdlxliff.
**Support and manual:** [Wiki](https://www.wordfast.net/wiki/Wordfast_Anywhere), [manual](http://www.wordfast.com/sites/default/files/www.wordfast.net/zip/wf_en6.zip).
**License:** Closed source.
**Cost:** Free (registration needed).
**Reviews:** [ProZ](https://www.proz.com/software-comparison-tool/tool/wordfast_anywhere/29).

## XTM Cloud

XTM International develops XTM, a complete online Translation Management System (TMS) with an integrated Computer Aided Translation (CAT), targeted at enterprises, LSPs and freelance translators. The centrally shared TM, terminology, workflow and translator workbench are all accessed via a browser. While XTM is cost effective and easy to use, it is a scalable system, that is built for collaboration and incorporates a comprehensive API.

**Supported formats**: [file formats](https://xtm.cloud/faq/xtm-cloud-file-types/).
**Support and manual:** [XTM Academy](https://xtm.cloud/academy/) provides access to knowledge base articles, webinars, tutorials, online documentation release notes, and [support](https://support.xtm-intl.com/en/support/home).
**License:** Closed source.
**Demo:** 30-day free [trial](https://xtm.cloud/trial/).
**Cost:** Monthly, quarterly or annual [subscription pricing](https://xtm.cloud/pricing/) depending on the Account type (Freelance, Group, Entreprise), Duration, Number of users and Words/month.
**Reviews:** [Proz](https://www.proz.com/software-comparison-tool/tool/xtm_cloud/91), [Capterra](https://www.capterra.fr/software/157254/xtm-cloud), [G2](https://www.g2.com/products/xtm-cloud/reviews).

## Wordbee

[Wordbee](https://www.wordbee.com/) is an online Translation Project Management and Translation Editor. It is a complete CAT tool, price management, customer management, invoicing, and linguistic solution.

**Supported formats**: [Supported file types](https://www.wordbee.com/file-formats/).
**Support and webinars:** [Documentation](https://documents.wordbee.com/display/home/Welcome), [Support](https://wordbee.zendesk.com/hc/en-us), [Webinars](https://www.wordbee.com/events/webinars/).
**License:** Closed source.
**Demo:** 14-day free trial.
**Cost:** Monthly or annual subscription.
**Reviews**: [Capterra](https://www.capterra.com/p/151876/Wordbee/reviews/), [G2](https://www.g2.com/products/wordbee/reviews).

## Termsoup

[Termsoup](https://termsoup.com/) is a cloud-based computer-assisted translation (CAT) software designed to boost productivity. This no-frill, user-friendly platform is ideal for literary (but not only) translators who need streamlined features for long-form projects. The platform makes collaboration simple with real-time editing and auto-save features so translators and colleagues can work together.

Sports various original features and an interesting UI/UX.

**Supported formats**: doc, docx, xls, xlsx, ppt, pptx, txt, html, xml, dtd, json, csv, yaml, srt, wix, json, yml, odt, ods, odp, po, xlf, xliff, sdlxliff, ttx, mif, idml, icml, and dita.
**Support and manual:** [User guide](https://termsoup.crisp.help/en-us/).
**License:** Closed source.
**Cost:** Subscription-based, free 10-day trial.
**Reviews:** [Capterra](https://www.capterra.com/p/204194/Termsoup/).

## Other

Not to mention the different online browser-based localization platforms which can be used on GNU/Linux:



* [Smartling](https://www.smartling.com): A translation management solution which includes a web CAT tool which help automate, manage, and professionally translate content.
* [Crowdin](https://crowdin.com/)
* [Transifex](https://www.transifex.com/): Proprietary and closed source, but often used to translate open-source software. Free for translators.
* [Weblate](https://weblate.org/en/): Free/Libre open source software, it can be self-hosted or you can pay for hosting services.
* [Pontoon](https://pontoon.mozilla.org/): Used to localize the interface of Mozilla Firefox websites.
* [Zanata](http://zanata.org/)
* [Pootle](http://pootle.translatehouse.org/)
* [POEditor](https://poeditor.com/)
* [Webtranslateit](https://webtranslateit.com/en)

# Translation related tasks and tools

## Alignment

Document alignment is the process of matching source language segments with target language segments and creating a reusable bilingual document (commonly a translation memory). It is a way of making use of existing translation materials, especially those not translated via a CAT tool.

[LF Aligner](https://sourceforge.net/p/aligner/wiki/Home/) (free, offline) is an excellent alignment tool which relies on Hunalign for automatic sentence pairing. Input: txt, doc, docx, rtf, pdf, html. Output: tab delimited txt, tmx, and xls. With web features. The Linux version opens an interactive easy to use terminal. The alignment review step requires editing the produced file in a spreadsheet program. The Windows version does not need installation and can run on Wine. It offers a GUI, and, at the alignment review/editing step, it opens an easy interface for splitting and merging source/target segments and fixing any alignment error.

[WordFast Aligner](https://www.wordfast.net/?go=align) (free, online)

[WordFast Anywhere](http://autoaligner.freetm.com/) (free, online, registration needed) also integrates an [autoaligner](https://www.wordfast.net/wiki/Wordfast_Online_Aligner).

[MateCat aligner](https://guides.matecat.com/mate), a TMX creator whose design is very similar to MateCat translation editor and accessible via the Aligner tab from the [MateCat homepage](https://www.matecat.com/).

[TM-Town](https://www.tm-town.com) (online, registration needed) has an [alignment tool](https://www.tm-town.com/blog/document-alignment-tool-update) that can help you convert a source and target document into a translation memory (TM) file.

[YouAlign.com](http://www.youalign.com/) (free, online, registration needed, 1MB max file size) an alignment tool based on AlignFactory, a powerful automated document alignment tool with a web crawler.

[PlusTools](https://www.wordfast.net/wiki/PlusTools) is a free MS Word add-in that can handle multiple tasks, including aligning documents.

Many other CAT tools, such as WordFast Pro, OmegaT, CafeTran Espresso, SmartCat and Memsource offer an alignment feature.

[Stingray](https://www.maxprograms.com/products/stingray.html) Document Aligner (open source and free to use, with [paid](https://www.maxprograms.com/store/buy.html) subscription for support and binaries) is a cross-platform document aligner designed to assist professional translators in the production of translation memories from existing translated material.

## Handling tags

Word documents (especially those coming from OCR’d files or PDF converted files) are often strewn with codes which produce unnecessary tags when imported in a CAT tool. This tagged information shows up in the translation grid as spurious codes{1}around{2}, or even in the mid{3}dle of, words, making sentences difficult to read and translate and generally negating many of the productivity benefits of the program. There are ways to get around this.

[CodeZapper](http://asap-traduction.com/CodeZapper) (€20 licence) is a set of Word VBA macros designed to “clean up” Word files before being imported into a standalone translation environment so that the files have fewer tags.

[TransTools - Document Cleaner](https://www.translatortools.net/docs/transtools/doccleaner) (freeware) Part of the [TransTools](https://www.translatortools.net/docs/transtools) set of MS Office add-ins, Document Cleaner is a collection of tools for the preparation of badly formatted documents for translation. It features a Tag cleaner tool, which attempts to strip unnecessary tags.

[CafeTran Espresso](https://cafetran.com/) CAT tool offers a special filter to handle MS Word documents after OCR, which clears the source text of unnecessary formatting tags. It can prove useful anytime an MS Word document produces too many unnecessary tags.

[OmegaT](https://omegat.org/) CAT tool has a Remove tags option, which strips ALL tags from the imported document(s). The latest version now includes the [TagWipe](https://libretraduko.wordpress.com/2018/04/18/tagwipe-in-omegat/) utility/Groovy script for clearing excessive tags on Word documents. It offers a GUI that lets the user select different options with which it should be run.

## Translation Memory (TMX) Editing - Maintenance

[Heartsome TMX Editor](https://github.com/heartsome/tmxeditor8) (free, open source)

A powerful TM maintenance tool for all CAT software. It provides many useful and practical functions besides common editing features, allowing you to perform TM maintenance tasks easily, simply and all with one tool.

[TMXEditor](https://www.maxprograms.com/products/tmxeditor.html) (free, open source)

Maxprograms TMXEditor is a cross-platform open source desktop application designed for editing TMX. It is able to handle very large files with millions of segments.

[Okapi Olifant](http://okapi.sourceforge.net/Release/Olifant/ReadMe.htm) (free, open source)

An excellent free Translation Memory Editor. Caveat: its current version is based on the old (2009) Windows-only .NET version of Okapi framework (a new Java-based version is in the works). Upside: It can be installed via Wine (or PlayOnLinux/CrossOver), provided that you have .NET framework 2.0 or later installed (on your Wine bottle/prefix). [Online documentation](http://okapi.sourceforge.net/Release/Olifant/Help/).

[CafeTran Espresso](http://cafetran.com/) (paid)

CafeTran Espresso CAT tool offers a powerful workflow for performing various editing and maintenance tasks on TMX Translation Memories. The Demo limits TM editing to 1,000 TUs.

[SuperTMXMerge](https://github.com/amake/SuperTMXMerge) (free, open source)

Diff tool for comparing and merging TMX translation memories.

[Goldpan TMX/TBX Editor](https://logrusglobal.com/goldpan.html) (free, Windows VM only)

An intuitive and multifunctional TMX/TBX file editor from Logrus Global Software Development Team.

## Segmentation - SRX editors

The SRX (Segmentation Rules eXchange) format is an open standard to save segmentation rules in a file so they can be used between different tools.

Examples of tools that support SRX files: OmegaT, CafeTran Espresso, Swordfish, WordFast Pro, and Memsource.

Maxprograms’ [SRXEditor](https://www.maxprograms.com/products/srxeditor.html) is an open source cross-platform editor of segmentation rules, designed to use Segmentation Rules eXchange (SRX) 2.0. You can use SRXEditor to create new SRX files and edit existing ones. It also can be used for testing segmentation rules to ensure that they break text as expected. It is also currently included in Swordfish III installers.

[Okapi Ratel](http://okapiframework.org/wiki/index.php?title=Ratel) is a free-libre/open source cross-platform application that helps create and maintain segmentation rules in the SRX format. Such rules are used to break down translatable text into more meaningful parts. Ratel is part of the Okapi Framework, and can be used either as a standalone utility or from within Okapi Rainbow.

Downloadable SRX rules: [OmegaT’s default rules](https://raw.githubusercontent.com/omegat-org/omegat/master/src/org/omegat/core/segmentation/defaultRules.srx), [LanguageTool’s segmentation rules](https://github.com/languagetool-org/languagetool/blob/master/languagetool-core/src/main/resources/org/languagetool/resource/segment.srx).

## Term extraction

Monolingual term extraction attempts to analyze a text or corpus in order to identify candidate terms, while bilingual term extraction analyses existing source texts along with their translations in an attempt to identify potential terms and their equivalents.

### Monolingual term extraction

<!--- [Prospector](https://logrusglobal.com/prospector.html) Free, online, English only. If you work on English source texts, try it.
Based on the world’s largest corpus of the English language supported by a Brigham Young University professor, and a unique algorithm developed by a team of in-house experts. --->
[TermoStat Web](http://termostat.ling.umontreal.ca/interfaceTermostat.php)

Free, online. Languages: English, French, Italian, Portuguese, Spanish. The results are really good. Uses linguistic and statistical methods while taking the potential terms’ structures and relative frequencies into account in the analysis corpus. TermoStat is free, but users must register. Outputs a Tab delimited TXT (which can be renamed to and opened as a CSV file in LibreOffice).

[Tilde terminology](https://term.tilde.com/) (powered by Taas)

Free/Premium, online, 25 languages. Various options to choose from. By default, it uses TWSC (Tilde wrapper system for CollTerm) based on linguistic analysis enriched by statistical features. Extraction time somewhat long, but results quite accurate. By specifying a subject domain, some term candidates are matched with translations from a variety of sources for target translation lookup.

[The Sketch Engine](https://www.sketchengine.co.uk/)

Subscription-based, online. Several supported languages. Monolingual and bilingual term extraction supported. Also offers a simpler [OneClick term extractor](https://terms.sketchengine.co.uk/) for single word and multiword candidates.

[Okapi Framework - Rainbow](http://okapiframework.org/wiki/index.php?title=Rainbow)

Free, offline. Its term extraction utility offers flexible, configurable statistical analysis. Supports all languages which use scripts with space-delimited words.

### Bilingual term extraction

[The Sketch Engine](https://www.sketchengine.co.uk/)

Subscription-based, online. Several supported languages. Monolingual and bilingual term extraction supported.

[Anchovy](https://www.maxprograms.com/products/anchovy.html)

Anchovy is an offline multilingual cross-platform glossary editor and bilingual term extraction tool based on the open Glossary Markup Language (GlossML) format. It handles various import and export file formats.

## Terminology management

### File formats

**Excel / CSV/TSV / Tab-delimited TXT**

Some simple glossary formats such as Excel files, CSV/TSV (Comma-separated values/Tab-separated values) files and tab-delimited text files may be all you need for your terminology management and glossary exchange needs.

Excel and CSV/TSV files can simply be edited in office applications such as [Microsoft Excel](https://support.office.com/en-us/article/import-or-export-text-txt-or-csv-files-5250ac4c-663c-47ce-937b-339e391393ba?ui=en-US&rs=en-US&ad=US), [LibreOffice Calc](https://help.libreoffice.org/Calc/Importing_and_Exporting_CSV_Files) (superior CSV/TSV handling compared to Excel). [Ron’s Editor](https://www.ronsplace.eu/Products/RonsEditor), an excellent dedicated CSV editor with professional features (Feee/Lite and Pro versions available, with a 30-day trial) is Windows-only, but can be used with Wine after installing .Net Framework 4.5.2.

Tab-delimited TXT files can be edited in any text editor, although it is recommended to simply rename them to .csv or .tsv, no other conversion needed.

Most CAT tools support such files (and converting from one of these file formats to another is mostly trivial): [OmegaT](https://omegat.sourceforge.io/manual-standard/en/index.html#__sethome
), CafeTran Espresso, [Matecat](https://www.matecat.com/support/managing-language-resources/add-glossary/), Memsource (Import/Export Excel), WordFast Pro (Tab delimited TXT), [Fluency Now](https://fluencytranslation.wordpress.com/fluency-now-adding-personal-terminology/), etc.

[Anchovy](https://www.maxprograms.com/products/anchovy.html) free utility can import TMX, CSV and tab-del glossaries and export to  ([GlossML](https://www.maxprograms.com/glossml/glossml.pdf), the format used by Swordfish), CSV, HTML, TMX, TBX and XML.

For conducting CAT-tool independent TM and glossary searches, [TMLookup](http://www.farkastranslations.com/tmlookup.php) is an open-source tool designed to search (massive) bilingual and multilingual text databases (translation memories) and glossaries. For glossaries, it can import TXT and XLS files. It runs fine on Wine.

**TBX**

TBX, short for TermBase eXchange, is the international standard for representing and exchanging information about terms, words, and other lexical data. Here’s a list of tools with some TBX support: [https://www.tbxinfo.net/tbx-support/](https://www.tbxinfo.net/tbx-support/)

Several CAT tools can **import/read** TBX files: OmegaT, CafeTran Espresso, Memsource, WordFast Pro, Swordfish, etc.

Heartsome TMX editor can **import and export to TBX** (but not directly edit), among other formats.

Anchovy can **export** to TBX: [Anchovy](https://www.maxprograms.com/products/anchovy.html) (free).

Virtaal can **edit/read** TBX files.

XBench (see below) can **import** TBX files and **convert** them to tab-delimited TXT files.

[Goldpan TMX/TBX Editor](https://logrusglobal.com/goldpan.html) (installs but does not run correctly in Wine, needs a Windows VM) can **edit and export/save** TBX (and TMX) files

[Translate-Toolkit](http://docs.translatehouse.org/projects/translate-toolkit/en/latest/) is a set of libraries and command line tools made by the same creators of Pootle and Virtaal and used by many free software projects, like Lokalize. It comes with [several file conversion utilities](http://docs.translatehouse.org/projects/translate-toolkit/en/latest/commands/index.html), including xls2csv and [csv2tbx](http://docs.translatehouse.org/projects/translate-toolkit/en/latest/commands/csv2tbx.html). It's useful to manage term bases in .xlsx, .csv and .tbx when no GUI tool is available (or for general scripting).

**SDLTB**

Trados Studio termbases (SDLTB) are written in a proprietary format, created by SDL MultiTerm. Since SDL Trados/Multiterm are quite common, you might come accross these files fairly often.

Some CAT tools support importing SDLTB files: CafeTran Espresso, Fluency Now and Memsource ([partly](https://help.memsource.com/hc/en-us/articles/360013696860-Modify-Term-Bases)

Tools for converting SDLTB files: [Trados Studio Resource Converter](http://www.vannellen.com/fortranslators.php) and [WfConverter](http://wordfast.fi/blog/cat-tools/2012/11/03/convert-sdltm-and-sdltb-without-studio-and-multiterm/)

Tools for converting to SDLTB (among other conversions): [Glossary Converter](http://www.cerebus.de/glossaryconverter/) (Windows VM, or Wine with MS Office)

### Tools

[XBench](https://www.xbench.net/) is a Terminology and QA tool.

It features an older freeware non-unicode version (2.9) and a yearly subscription-based version 3.x in active development. The program is Windows-only but runs well on Wine.

XBench supports a host of glossary, TM and bilingual formats. For Terminology, XBench can import/read Tab-delimited Text files, TBX, MultiTerm XML Glossaries, Wordfast Glossaries, etc.

It can also be used to convert to TMX and Tab-delimited text files.

# Office software

An Office suite represents an important part of a translator’s or reviser’s toolkit and is often a critical step in the translation workflow.

[Microsoft Office](https://www.office.com/)

Various versions of Microsoft Office are quite well supported via Wine and are installable using [PlayOnLinux](https://playonlinux.com/) (free) or [CrossOver](https://codeweavers.com/) (paid). See dedicated section below.

If needed, Microsoft Office can also be installed in a Windows VM (see related section).

Useful Microsoft Office add-ins:
- [CodeZapper](http://asap-traduction.com/CodeZapper) (one-time donation) is a set of Word VBA macros designed to “clean up” Word files before being imported into a standalone translation environment so that the files have fewer tags.
- [TransTools](http://www.translatortools.net/) is a collection of tools for Microsoft Word, Microsoft Excel, Microsoft PowerPoint, Microsoft Visio, Autodesk AutoCAD and other programs. These tools will help you at every step of the translation process – during the preparation of documents for translation, in the course of translation, and during QA and post-formatting. [Feature overview](http://www.translatortools.net/benefits.html).
- [PlusTools](https://www.wordfast.net/wiki/PlusTools) is a free MS Word add-in that can handle multiple tasks, including preparing tagged files for translation, extracting terminology, and alignment.
- [Grammarly](https://www.grammarly.com/office-addin/) (freemium) is an Windows program that you can install along with MS Office. It automatically detects grammar, spelling, punctuation, word choice, and style mistakes in your writing (English only). Also available as a Chrome plugin and a web app.

[LibreOffice](https://www.libreoffice.org/)

LibreOffice is an excellent Office suite in its own right. It can open and save MS Office documents, but the improved compatibility is not always perfect, which can be critical when it comes to delivering final documents and meeting client expectations. You may need to consider other options as well.

One neat functionality it has is the ability to export hybrid PDFs, which are PDFs embedded with the original .odt file. This means that, by opening a hybrid PDF through LibreOffice Writer, the translator/proofreader is able to edit the original file while maintaining PDF formatting. This is exclusive to LibreOffice, as no other office software is able to do this.

Pair it with hunspell for spelling support for your language and the hyphen/hyphenation package for optimal use.

[Feature/compatibility comparison](https://wiki.documentfoundation.org/Feature_Comparison:_LibreOffice_-_Microsoft_Office) with Microsoft Office.

Useful [LibreOffice extensions](http://extensions.libreoffice.org/):
- [LanguageTool](https://extensions.libreoffice.org/extensions/languagetool): linguistic and grammar check for many supported languages.
- [Grammalecte](https://extensions.libreoffice.org/extensions/grammalecte): French grammar checker. Note: You must disable LanguageTool for Grammalecte to work in LibreOffice.
- [Linguist](https://extensions.libreoffice.org/extensions/linguist): Simple text analyzer (including word counts).
- [MultiFormatSave](https://extensions.libreoffice.org/en/extensions/show/multisave-1): It enables you to save simultaneoulsly a document in the OpenDocument, MS Office and/or PDF formats as you choose.
- [Multisave](https://extensions.libreoffice.org/extensions/multisave): Save a document simultaneously into OpenDocument and/or MS-Office and/or PDF formats.
- [AltSearch](https://extensions.libreoffice.org/en/extensions/show/alternative-dialog-find-replace-for-writer): Advanced find and replace function.
- [Copy only visible cells](https://extensions.libreoffice.org/extensions/copy-only-visible-cells): An alternative to the “Select Visible Cells” command in Microsoft Excel.
- [Export as images](https://extensions.libreoffice.org/extensions/export-as-images): Export all the Impress slides or Draw pages as images of JPG, PNG, GIF, BMP and TIFF format.
- [Pepito Cleaner](http://pepitoweb.altervista.org/pepito_cleaner/index.php): Pepito Cleaner helps quickly resolve the most common formatting mistakes of old scans, PDF imports, and every digital text file.
- [CleanDoc](https://extensions.openoffice.org/project/cleandoc): (Old) Remove hidden information from the document - macros, dialogs, form elements, user fields.
- [Anaphraseus](https://extensions.libreoffice.org/extensions/anaphraseus): free CAT tool integrated into OpenOffice/LibreOffice, like WordFast Classic in Word.
- [Read Text](https://extensions.libreoffice.org/extensions/read-text): Text to speech solution which uses an external program or web service to read a text (not tested).

[Apache OpenOffice](https://www.openoffice.org/)

Less developed and feature-rich than LibreOffice. Use LibreOffice instead.

[WPS Office](http://www.wps.com/)

Free for Linux users and comes with an unchangeable ribbon/tabbed bar, not very customizable but it's still featureful. Boasts high MS Office compatibility, but it is unable to handle free formats like ODT. It includes support for baloons that is arguably better than that of Microsoft Word, as the tracked changes section can be scrolled. It allows to set your own keyboard shorcuts for specific Unicode characters, which is useful depending on your keyboard layout. If you find any issues (e.g. theming), check the [general troubleshooting page over the Arch Linux wiki](https://wiki.archlinux.org/index.php/WPS_Office).

[SoftMaker Office](https://www.softmaker.com/en/softmaker-office)

Paid software; you can subscribe to its Software-as-a-Service model (similar to Office 365) or purchase it once. 30-day free trial with FreeOffice. Boasts high MS Office compatibility, the interface is quite feature-complete and has a traditional look, although it lacks baloons.

Tip: Trial can be reset by removing the SoftMaker folder.

[SoftMaker FreeOffice](http://www.freeoffice.com/)

The free version of SoftMaker Office.

[OnlyOffice](https://www.onlyoffice.com/)

It has good looks and potential, but it's way less featureful than other desktop clients like LibreOffice, Softmaker Office and WPS Office. Works both offline and in the cloud, can be integrated directly to a Nextcloud instance. Boasts 100% compatibility with MS Office formats (as it saves natively into these formats).
It does not currently include dynamic counting of words. See [here](https://github.com/ONLYOFFICE/DesktopEditors/issues/166).

[Google Docs](https://www.google.com/docs/about/)/[Google Drive](https://drive.google.com) (online)

You can now directly edit, comment, and collaborate on Office files using Google Docs, Sheets, and Slides. Changes will be auto-saved to the file in Office format ([help article](https://support.google.com/drive/answer/9276408?hl=en)). Google Docs can be set up for [offline access](https://support.google.com/docs/answer/6388102).

With the Office Editing for Docs, Sheets & Slides [Chrome extension](https://chrome.google.com/webstore/detail/office-editing-for-docs-s/gbkeegbaiigmenfmjfclcdgdpimamgkj), Microsoft Office files that you drag into Chrome, open in Gmail, Google Drive, and more, will be opened in Docs, Sheets, and Slides for viewing and editing.

[Microsoft Office Online](https://www.office.com/) (online)

The online version of MS Office 365 is a stripped-down version of the original desktop suite and free to use.

**Office file conversion**

For quick and easy office file conversions, you can use command line utilities (directly in the terminal or integrated in scripts).

[Abiword](https://www.abisource.com/) is a word processing program that can be used for various tasks, including CLI-based file conversions. For command line options, refer to its [man page](https://linux.die.net/man/1/abiword).

[unoconv](https://github.com/unoconv/unoconv) is a CLI utility for converting any document from and to any LibreOffice supported format. For command line options, refer to its [man page](https://linux.die.net/man/1/unoconv).

_soffice_ is the CLI version of the LibreOffice office suite. It can be used for launching LibreOffice GUI with specific options or in headless mode, as well as converting to various formats. For command line options, refer to its [man page](https://www.systutorials.com/docs/linux/man/1-soffice/).

**A word on Microsoft fonts:**

You’ll probably need a way to install Microsoft/Windows fonts on your Linux distribution to be able to work with the same fonts as other Microsoft Office users. These are mostly proprietary. You can install these fonts on your GNU/Linux distribution via a package typically called ttf-mscorefonts-installer/msttcorefonts and signing an EULA. It's the result of the now discontinued project [Core fonts for the web](https://en.wikipedia.org/wiki/Core_fonts_for_the_Web) and [available here](http://corefonts.sourceforge.net/); however, since newer versions of Microsoft Core Fonts are unavailable for redistribution/commercial use since the project was discontinued and ttf-mscorefonts-installer packages incredibly old versions of these fonts (2012), this might render incompatibility. Emphasis on might. Thus it might be a good idea to save the original Microsoft Fonts for personal use.

Copying the fonts folder from a Windows machine and placing it in the hidden .local/share/fonts folder of your home folder (or creating it, if it does not exist) is a distribution-independent solution. On legacy systems, it is possible to do the same with the ~/.fonts folder or .local/share/fonts instead. 

If fonts don’t look good, you might need to learn how to improve anti-aliasing.

# Grammar checkers - Writing aids

- [Antidote](https://www.antidote.info/en) (FR/EN): is an excellent French and/or English language, typography and style corrector, which also includes several Dictionaries (definitions, synonyms, word combinations, etc.) and Guides. It currently offers a subscription-based web version with Connectix, a Linux-compatible connector for LibreOffice, Thunderbird, Firefox, Chrome (and derivative browsers, such as Chromium and Vivaldi), plus excellent software support.  Well worth the investment.
- [LanguageTool](https://languagetool.org/languages/) (multiple languages, free and open source): linguistic and grammar check for LibreOffice, Chrome, Google Docs also available as a Standalone app for [many supported languages](https://languagetool.org/languages/).
- [Grammarly](https://www.grammarly.com/) (EN) (freemium) detects grammar, spelling, punctuation, word choice, and style mistakes in your writing. Available as a Chrome extension, as a Word add-in and a web app.
- [Grammalecte](https://www.dicollecte.org/) (FR): free and open source French grammar checker for LibreOffice, Thunderbird, Firefox, Chrome and CLI editors. Note: You must disable LanguageTool for Grammalecte to work in LibreOffice.
- Other writing editors and writing aids (EN): [ProWritingAid](https://prowritingaid.com/), [Hemingway App](http://www.hemingwayapp.com/).
- Other online proofreading tools (EN) include [GrammarChecker](https://grammarchecker.net/) and [GrammarLookup](https://www.grammarlookup.com/).
- [Ludwig.guru](https://ludwig.guru/) (EN) is a linguistic search engine and contextualized translator.
- [Writefull](https://writefullapp.com/) (EN) is an app that gives feedback on your writing by checking your text against databases of correct language (also offers translations from any language into English). It is available as a cross-platform desktop application and as a Chrome extension.

Note: [PerfectIt](http://www.intelligentediting.com/) (EN) (paid) cannot be installed with Wine (as tested), it needs to be used in a Windows VM.

# QA tools

Each CAT tool offers a built-in QA:

- OmegaT features a very good “QA - Check rules” script.
- CafeTran offers a very rich [QA feature](https://github.com/idimitriadis0/TheCafeTranFiles/wiki/2-Menu-and-Interface#qa).
- Memsource sports a [Quality Assurance pane](https://help.memsource.com/hc/en-us/articles/360012872099) for a host of [QA checks](https://help.memsource.com/hc/en-us/articles/360012872099).
- [WFP 3](https://www.wordfast.com/WFP3/Wordfast_Pro_Help.htm) and [WFP 6](https://www.wordfast.com/WFP/6.6/Wordfast_Pro_Help.htm) offer Transcheck.
- WordFast Classic has [Quality Assurance](https://www.wordfast.net/wiki/Quality_Assurance_Wordfast_Classic).
- MateCat has [built-in QA](https://www.matecat.com/support/translating-projects/qa-messages/) and also includes [lexiqa](https://www.matecat.com/support/advanced-features/matecat-qa-lexiqa/) for in-segment checks.
- SmartCat also covers [Quality Assurance](https://help.smartcat.ai/hc/en-us/articles/115002017352-Quality-Assurance).
- Same goes for [WordFast Anywhere](https://www.wordfast.net/wiki/Wordfast_Anywhere_6_Manual#QA_tab).

On top of the QA checks integrated into your chosen CAT tool, you may want or need to use a dedicated QA tool.

- Okapi Framework [CheckMate](http://okapiframework.org/wiki/index.php?title=CheckMate) (also built-in to Rainbow) is a free cross-platform application that allows you to perform various quality checks on bilingual translated documents.
- [XBench](http://www.xbench.net/)
  - The Freeware version 2.9 works fine on Wine, although it does not offer Unicode support.
  - The paid version XBench 3.x seems to work fine as well.
  - XBench also offers a Chrome Extension for Memsource, Wordfast Pro, Matecat, Smartcat, XTM,  Transifex and Crowdin.
- [Verifika](https://e-verifika.com/) (paid, 14-day trial) 32-bit edition can be installed, but may not run in Wine. Probably to be used in a Windows VM. Same goes for [QA Distiller](http://www.qa-distiller.com/).

# Proofreading and Revising (Track changes, compare documents)

<!--- TODO Expand this section--->

Reviewing translations and proofreading can either be done within a CAT tool, especially with the Track Changes feature, via an exported Word or RTF bilingual table or on the exported target document itself.

Let’s take each scenario separately:

**Track changes (in a CAT tool):**

In SDL Trados and memoQ, reviewers often make use of the included Track changes feature.

While each CAT software offers different methods for reviewing translations, if you are working outside of the above-mentioned tools, you cannot use Track changes in the bilingual (SDLXLIFF, MQXLIFF) files themselves.

You can, however, suggest the use of [TQAuditor](https://cloud.tqauditor.com/quick/upload)’s Quick Compare feature, to produce an Excel report highlighting any changes made during revision, by comparing the translated and the reviewed bilingual file. If you register with [TQAuditor](https://tqauditor.com) (free), you can keep track of these jobs and access a few more actions. Since TQAuditor supports bilingual files from various CAT tools, it represents a universal, “CAT-tool-agnostic” solution for producing translation reviews. This means you can open the SDLXLIFF files to review, make the necessary changes in your preferred CAT tool, and then create a comparison report in TQAuditor.

**(Track) changes (in an exported bilingual Word/RTF)**

Working on exported bilingual Word or RTF files offers the advantage that the reviewer does not need to own the original CAT tool, or any CAT tool, for that matter. The disadvantage being that the reviewer is left without the convenience (plus TM and other resources) of a CAT tool. If you receive a bilingual Word or RTF for external review, you can just use your Office suite Text processing application (MS Word, LibreOffice Writer, WPS Writer etc.) to complete the review. Provided that bilingual review files can be opened in LibreOffice (SDL Trados files may not be compatible, it seems), it’s good to know that its track changes/compare document feature is compatible with MS Office, at least with some precautions (like ensuring you use the same author name and initials in both programs, see archived link [here](https://web.archive.org/web/20180104151847/http://www.techandlife.com/2015/04/compatibility-of-tracked-changes-and-comments-between-word-and-libreoffice-writer/)). If you don’t use Track changes, the Compare document feature can be applied to create a document showing the modifications made.

**(Track) changes (in the target document)**

Here, it’s about working on the software program that handles the original file format. If it’s a Word document, you can use Track changes (or Compare Document) as usual. When delivering the final file, it’s usually expected to save a separate copy with no tracked changes (accept all).

# Various localization-related utilities

[Okapi Framework](http://okapiframework.org/)

The Okapi Framework is a cross-platform and free-libre/open source set of components and applications that offer extensive support for localizing and translating documentation and software.

[Rainbow](http://okapiframework.org/wiki/index.php?title=Rainbow) is an Okapi application which allows you to launch different utilities to help you perform various localization-related tasks. It includes CheckMate and Ratel, which can also be launched as standalone utilities.

[CheckMate](http://okapiframework.org/wiki/index.php?title=CheckMate) is a GUI application that performs various QA checks on bilingual translation files such as XLIFF, TMX, TTX, PO, TS, Trados-Tagged RTF, and any other bilingual format supported by the framework.

[Ratel](http://okapiframework.org/wiki/index.php?title=Ratel) is a GUI application to create and maintain segmentation rules. Such rules are used to break down translatable text into more meaningful parts. Ratel uses Okapi’s SRX-based segmentation engine. SRX is the Segmentation Rules eXchange format.

[XLIFF Manager](https://maxprograms.com/products/xliffmanager.html)

XLIFF Manager is a cross-platform open source graphical user interface for [OpenXLIFF Filters](https://www.maxprograms.com/products/openxliff.html) (an open source set of filters for creating, merging and validating XLIFF 1.2 and 2.0 files) written in JavaScript.

With XLIFF Manager you can:

- Create XLIFF 1.2 and 2.0 files that can be translated in any modern CAT tool for a variety of file types.
- Convert your translated XLIFF files to original format with a couple of clicks.
- Validate XLIFF files created by any tool. Validation is supported for XLIFF 1.0, 1.1, 1.2 and 2.0.
- Produce an HTML file with word counts and segment status statistics from an XLIFF document.
The XLIFF files generated by OpenXLIFF Filters don't use proprietary markup and are fully compatible with most CAT tools.

[BootCaT](https://bootcat.dipintra.it/)

Bootstrap Corpora And Terms from the Web. BootCaT is a free/libre software cross-platform Java application, which you can use to create specialized monolingual corpora on the fly. You can use a concordancer, such as AntConc, on the resulting corpus. Note: The [Sketch Engine](https://www.sketchengine.eu/) uses WebBootCaT among other features.

[AntConc](https://www.laurenceanthony.net/software/antconc/)

AntConc is a freeware corpus analysis toolkit for monolingual concordancing and text analysis.

[AntFileConverter](https://www.laurenceanthony.net/software/antfileconverter/)

A freeware tool to convert PDF and Word (DOCX) files into plain text for use in corpus tools like AntConc.

[AntFileSplitter](https://www.laurenceanthony.net/software/antfilesplitter/)

A freeware text file splitting tool.

[AntPConc](https://www.laurenceanthony.net/software/antpconc/)

A freeware parallel corpus analysis toolkit for concordance search and text analysis using UTF-8 encoded text files.

[EncodeAnt](https://www.laurenceanthony.net/software/encodeant/)

A freeware tool for detecting and converting character encodings.

[Any2UTF8](https://docs.sslmit.unibo.it/doku.php?id=any2utf8:start)

Any2UTF8 is a simple program to convert plain text file in any character encoding to UTF8.

[ODA File Converter](https://www.opendesign.com/guestfiles/oda_file_converter)

For converting between different versions of .dwg and .dxf files.

[HTTRack/WebHTTRack](https://www.httrack.com/)

A free (GPL, libre/free software) and easy-to-use offline browser utility allowing you to copy a World Wide Web site from the Internet to a local directory, building recursively all directories, getting HTML, images, and other files from the server to your computer. HTTrack arranges the original site’s relative link structure. Simply open a page of the “mirrored” website in your browser, and you can browse the site from link to link as if you were viewing it online. Useful for some website translation scenarios.

[Translate Toolkit](http://toolkit.translatehouse.org/)

A toolkit with various terminal utilities for localization engineers, offering format conversions, and quality assurance tasks. Most notably it includes command line tools for converting XLIFF, PO, TS, DOCX/XLS, TBX, TMX, TXT, WORDFAST, SRT, XML, etc.

[TMXValidator](https://www.maxprograms.com/products/tmxvalidator.html)

Check the validity of your TMX documents on any platform.

[FileOpen](https://plugin.fileopen.com/all.aspx)

Plug-in and viewer to access documents encrypted with the FileOpen software. While the Linux version is old, the Windows versions can be run via Crossover Linux or PlayOnLinux (see section on WINE) in combination with a compatible Adobe Acrobat/Adobe Reader version.

# Subtitling

Professional subtitling software is mostly Windows only, I’m afraid. Here are some free alternatives for more occasional subtitling (although Aegisub and, more recently, Subtitle Edit, are being used by professional subtitlers as well).

[Aegisub](http://www.aegisub.org/)

Aegisub is a free, cross-platform open-source tool for creating and modifying subtitles. Aegisub makes it quick and easy to time subtitles to audio and features many powerful tools for styling them, including a built-in real-time video preview.

Although one the most advanced and powerful free subtitling tools out there, and an excellent program for time-spotting, Aegisub has stopped being actively developed a few years ago. Consider using Subtitle Edit.

Aegisub’s [user manual](http://docs.aegisub.org/3.2/Main_Page/).

[Subtitle Edit](http://www.nikse.dk/subtitleedit/)

Subtitle Edit is a free (open source) subtitle editor. It can read, write, and convert between more than 200 subtitle formats. Useful for file conversions. [Help page](http://www.nikse.dk/SubtitleEdit/Help). [Tutorial videos](http://www.nikse.dk/SubtitleEdit/Video). If the Linux-ready (portable) version is giving you issues, try the Windows version via Wine.

[Gaupol](https://otsaloma.io/gaupol/)

Editor for text-based subtitles. Supports translating subtitles side by side with the original.

[Amara](https://amara.org/en/subtitling-platform/) offers a very good online subtitling platform.

[dotsub](https://dotsub.com/) is another web-based system for creating and viewing subtitles for videos in multiple languages across all platforms.

[Subtitle Composer](https://subtitlecomposer.kde.org) is a subtitle editor made available by KDE that allows for both mouse- and keyboard-driven workflows. Most notably it includes dettachable panes for you to customize your environment; translate subtitles side by side; recognize speech via PocketSphinx; detect errors automatically; and manage times in bulk.

# Transcription

Foot pedal not included.

[Easytranscript](https://www.e-werkzeug.eu/index.php/en/products/easytranscript)

An easy to use transcription software with a variety of features. Free.

[Express Scribe](http://www.nch.com.au/scribe/index.html)

There are two options for [running Express Scribe on the Linux](http://www.nch.com.au/scribe/linux.html) operating system.
- Option 1: Native Linux Exe
- Option 2: WINE Install

[Transcribe!](https://www.seventhstring.com/xscribe/overview.html)

Download [for Linux](https://www.seventhstring.com/xscribe/download_linux.html). There is a 30-day evaluation period, after which you decide if you wish to [buy](https://www.seventhstring.com/xscribe/buy.html) the software.

# Dictionary lookup

[GoldenDict](http://goldendict.org/) is a feature-rich cross-platform dictionary lookup program.

The program has the following features:

- Support of multiple dictionary file formats, namely:
  - Babylon .BGL files, complete with images and resources
  - StarDict .ifo/.dict./.idx/.syn dictionaries
  - Dictd .index/.dict(.dz) dictionary files
  - ABBYY Lingvo .dsl source files, together with abbreviations. The files can be optionally compressed with dictzip. Dictionary resources can be packed together into a .zip file.
  - ABBYY Lingvo .lsa/.dat audio archives. Those can be indexed separately, or be referred to from .dsl files.
- Support for Wikipedia, Wiktionary, or any other MediaWiki-based sites to perform lookups in.
- Ability to use arbitrary websites as dictionaries via templated Url patterns (slightly slow).
- Ability to run arbitrary external programs for audio playback or content generation (text-to-speech, man pages, etc) (use the latest Git version for this)
- Support for looking up and listening to pronunciations from forvo.com
- Hunspell-based morphology system, used for word stemming and spelling suggestions.
Ability to index arbitrary directories with audio files for pronunciation lookups
Full Unicode case, diacritics, punctuation and whitespace folding. This means the ability to type in words without any accents, correct case, punctuation or spaces (e.g. typing “Grussen” would yield “grüßen” in German dictionaries).
- Scan popup functionality. A small window pops up with the translation of a word chosen from another application.
- Support for global hotkeys. You can spawn the program window at any point, or directly translate a word from the clipboard.
- Tabbed browsing in a modern Qt 4 interface.

With a bit of Google search, you can find different (mostly monolingual) Babylon, Stardict, Dictd and Lingvo [dictionaries to use in GoldenDict](http://goldendict.org/dictionaries.php) in some languages.

Other Dictionary applications exist on GNU/Linux, but they are nowhere near GoldenDict in functionality.

For dictionary file conversion, make sure to check out [PyGlossary](https://github.com/ilius/pyglossary), a tool for converting dictionary files aka glossaries with various formats for different dictionary applications.

Depending on your language pairs and subject fields, there are multiple dictionaries, glossaries, corpora, terminology banks, concordancers, etc. available online. Listing them is beyond the scope of this document.

Here’s just one: [MagicSearch.com](http://magicsearch.org/) is a multilingual metasearch engine which allows you to search multiple sources (dictionaries, corpora, machine translation engines, concordancers, search engines) with a single click. Select a language pair and submit a search (select the same source and target language for monolingual searches). MagicSearch will display a single scrollable page with multiple sources. You can click on each source button as it changes its color (=loads) to move to the respective source. MagicSearch remembers the language pair you selected the next time you visit the site (using a cookie).

Tip: Set “One-page results” to OFF, to speed up queries. Click on the gear to select which resources to use (and hide the others), and reorder them as you see fit. MagicSearch is also available as a browser extension.

# Project management & Invoicing

Project management tools don’t have to be translation-specific, although it may help. Also, depending on your country of residence and tax requirements, you can use different more general invoicing tools.

[Protemos](https://protemos.com/)

Free [for freelancers](https://protemos.com/tms-for-freelance-translators.html). Track translation orders, monitor deadlines, organize files, send invoices and control payments

[LSP.expert](https://www.lsp.expert/)

Project management and invoicing tool for Freelance translators, teams, and agencies. Online, subscription-based, 30-day trial.

[SDL Trados Businesss Manager](https://www.sdltrados.com/products/business-manager/?utm_source=referral&utm_medium=ibaccs&utm_campaign=business-manager&utm_tactic=holding-page&utm_content=learn-more) (previously BaacS)

Translation project management and invoicing tool. Offers an offline Windows-only version as well as an online version. Paid Freelance edition with permanent licence. The offline version is free for ProZ Plus members.

I you are a paying ProZ.com member, you can also use the online [ProZ.com invoicing tool](https://www.proz.com/invoice/about).

[Flantie](https://www.flantie.com/)

Flantie is an easy to use online task and invoice management system for translators and interpreters. It offers both a Free and and a Pro plan.

[Project Libre](http://www.projectlibre.com/product/projectlibre-open-source)

An open source desktop alternative to Microsoft Projects.

# DTP - Image localization

There is no QuarkXpress, Adobe InDesign, Photoshop or Illustrator for GNU/Linux.

Those offering DTP services may need to use a Windows VM or simply reconsider.

GNU/Linux is not completely lacking in the DTP department. [Scribus](https://www.scribus.net/) can produce professional PDFs, just like InDesign or QuarkXpress, [Inkscape](https://inkscape.org/) is probably just as good as Illustrator and [GIMP](http://gimp.org/) can tackle many of Photoshop’s capabilities.

It’s just that these tools cannot necessarily provide the required compatibility to flawlessly integrate into a client’s proprietary DTP workflow.

Along with some other software and utilities, they can, however, prove useful for occasional image localization and editing.

[ImageTranslate](https://www.imagetranslate.com/)

An online paid service for translating images.

# Speech recognition (STT)

<!--- TODO --->

Speech recognition is quite lacking in GNU/Linux. At present, few options compare to Nuance’s Dragon Naturally Speaking, which does not run natively (although some editions are reported to be usable under Wine).

Online solutions, such as [Voice notebook](https://voicenotebook.com/), make often use of the Google Speech API, which is also built-in Google Docs (CafeTran Espresso offers a [solution](https://cafetran.freshdesk.com/support/solutions/folders/6000225250) to take advantage of that).

Currently, one way to integrate speech recognition into your GNU/Linux workflow is to use an Android phone. Indeed, the smartphones' mic is optimized for recording voice and for noise suppression. Plus, you can apply voice typing across the desktop.

# Text-to-speech (TTS)

<!--- TODO --->

Text-to-speech can be used in a number of scenarios for revision or self-revision purposes. Alas, quality solutions do not abound.

Interested users might want to investigate [Balabolka](http://www.cross-plus-a.com/balabolka.htm), which runs in Wine (not tested).

Another solution would be to use [Amazon Polly](https://aws.amazon.com/polly/?nc1=h_ls) text-to-speech service, with the combination of a bash script.

CafeTran Espresso CAT tool actually implements TTS with the Amazon Polly API.

# PDFs

## PDF Editors

[Sejda PDF Editor](https://www.sejda.com/desktop) (Fremium)

[Foxit Reader](https://www.foxitsoftware.com/pdf-reader/) (Free) PDF reader (not editor) with some lite editing features such as PDF annotation and PDF sign.

[PDF-XChange Editor](https://www.tracker-software.com/product/pdf-xchange-editor) (Free)

[Able2Extract](https://www.investintech.com/prod_a2e.htm) (Paid) lets you convert, OCR, create and edit PDF documents.

[Qoppa PDF Studio](https://www.qoppa.com/pdfstudio/) (Paid)

[Master PDF Editor](https://code-industry.net/masterpdfeditor/) (Paid)

[Infix PDF Editor/TransPDF](https://www.iceni.com/infix.htm) (Paid, free for TransPDF editing)

Inceni’s Infix is a PDF Editor for Windows which works well under Wine (see related section below). Just deselect the PDF printer option during installation.

This software is of special interest to translators because it can be used along with [TransPDF](https://transpdf.iceni.com/), a free/pay as you go online service which handles [PDF files translation](https://www.iceni.com/translation.htm): it offers to convert the PDF to the XLIFF format which can then be translated in a CAT tool, in order to produce a translated PDF file that closely follows the original layout.

PDFs translated via TransPDF can be edited using the free demo version of Infix PDF Editor. This is very handy for making final adjustments to spacing and layout ready for clients.

Users of the paid Infix version can use TransPDF free of charge. [ProZ Plus](http://www.proz.com/about-plus-package) members enjoy free 10 credits (equivalent to 10 PDF pages) per month, along with [discounted credits](https://go.proz.com/transpdf-credit-purchase) purchase.

TransPDF also offers a paid OCR feature for non-editable PDFs.

[FlexiPDF](https://www.softmaker.com/en/flexipdf) (Paid)

FlexiPDF is a PDF Editor for Windows which also works well under Wine (only lacks specific functionality such as print to PDF on Linux) and is sold both under a subscription model (FlexiPDF NX) and as a product (FlexiPDF).

The professional version of FlexiPDF includes the export/import of text from a PDF for translation with a CAT tool, similarly to Infix/TransPDF. They offer discounts on occasion and based on the country you are, so it's affordable.

For a thorough review of solutions for handling PDFs in translation, see [here](https://github.com/idimitriadis0/TheCafeTranFiles/wiki/4-File-formats#pdf).

## PDF Readers

[Evince](https://wiki.gnome.org/Apps/Evince): Document viewer for multiple document formats. Supports PDF, PostScript, DjVu, TIFF, and DVI.

[Foxit Reader](https://www.foxitsoftware.com/pdf-reader/): PDF reader (not editor) with some lite editing features such as PDF annotation and PDF sign/protect.

[Okular](https://okular.kde.org/): Universal document viewer, supporting different kinds of documents, like PDF, Postscript, DjVu, CHM, XPS, ePub, and others. 
Tip: Since Okular refreshes automatically when the file is updated, it can be used for target file preview purposes with a CAT tool such as OmegaT.

## PDF-related utilities

[PDFSam](https://pdfsam.org/): Split, merge, extract pages, rotate and mix PDF files.

[PDF Chain](http://pdfchain.sourceforge.net/): A graphical interface allowing to manipulate PDF documents (concatenate, burst, watermark, attach files…)

[PDF Mod](https://wiki.gnome.org/Attic/PdfMod): Modify PDF documents: Reorder, rotate, and remove pages, export images from a document, edit the title, subject, author, and keywords, and combine documents via drag and drop.

[Tabula](http://tabula.technology/): Tabula is a tool for liberating data tables locked inside (editable) PDF files.

## PDF TO TEXT

For converting editable PDFs to Docx, most PDF conversion utilities require using a Windows VM.

[Able2extract Professional](https://www.investintech.com/prod_a2e.htm) is a closed source paid software that offers a Linux desktop version. It lets you convert, create and edit PDF documents. Conversion works for PDF to Word, Excdel, PowerPoint, AutoCAD, Images, Publisher and LibreOffice documents (ODT, ODS and ODP). It sports an OCR feature as well, including extracting scanned PDF tables into Excel.

[Foxit PDF to word online converter](https://www.foxitsoftware.com/pdf-to-word-converter/) produces excellent results.

[CloudConvert](https://cloudconvert.com/) online converter does a very nice job as well, with the added bonus that it also handles a host of different file conversion types and offers an API (you can create a script).

[AntFileConverter](http://www.laurenceanthony.net/software/antfileconverter/) is a freeware tool to convert PDF and Word (DOCX) files into plain text for use in corpus tools like AntConc.

For command-line enthusiasts, programs such as pdftotext, pdfreflow (pdftohtml), Calibre’s e-book-convert, pdf2htmlEX, pdfbox can be added to the mix for PDF text extraction.

For a thorough review of solutions for handling PDFs in translation, see [here](https://github.com/idimitriadis0/TheCafeTranFiles/wiki/4-File-formats#pdf).

## OCR

While there is no GUI version of [ABBYY FineReader](https://www.abbyy.com/en-me/finereader/) for GNU/Linux, ABBYY offers the [ABBYY FineReader Engine for Linux](https://www.abbyy.com/ocr-sdk/) as a command line interface (CLI), at an equivalent price.

Other native OCR solutions usually lag behind ABBYY FineReader and other proprietary software.

[Able2extract Professional](https://www.investintech.com/prod_a2e.htm) is a paid software that offers PDF conversion, creation and editing with OCR capabilities, including extracting scanned PDF tables into Excel (7-day free trial available).

A Windows VM (see related section) can be used to run [ABBYY FineReader](https://www.abbyy.com/en-me/finereader/) and other programs (such as Adobe Acrobat Pro, Nuance OmniPage, Readiris and Wondershare PDFelement). Some earlier versions of ABBYY FineReader (up to version 10) are also reportedly working via Wine (see related section).

Free/Open Source OCR engines include Tesseract, GOCR, and Cuneiform. The first two provide decent results, but struggle with complex layouts.

Various GUI software tools make use of these engines.

One of the easiest and most feature-rich is [gImageReader](https://github.com/manisandro/gImageReader). It scans images and PDFs, with manual and automatic recognition in multiple languages. Post-processing the recognized text includes a spellchecker, an excellent find and replace feature and a useful “remove line breaks” action that can have its use outside of OCR tasks as well.

When it comes to image scan post-processing, or pre-processing for use in a program like ABBYY FineReader (to improve OCR, but also for creating scanned ebooks), there is nothing like [Scantailor](http://scantailor.org/). Or rather, was, because it has stopped being developed. [Scantailor Advanced](https://github.com/4lex4/scantailor-advanced/releases) is still active though. The wiki is [here](https://github.com/4lex4/scantailor-advanced).

# E-book management & conversion

[Calibre](https://calibre-ebook.com/) is an excellent e-book management application for organizing, viewing, converting and editing e-books. Since linguists tend to keep many (e)books around, it’s definitely worth looking into it.

[Sigil](https://sigil-ebook.com/) is a very nice epub editor.

Interested in translating e-books? A solution is described [here](https://github.com/idimitriadis0/TheCafeTranFiles/wiki/4-File-formats#epub--mobi--azw--e-book).

# File and Folder comparison (DIFF) tools

[Meld](http://meldmerge.org/): Visual diff and merge tool for files, directories, and version controlled projects.

[Beyond Compare](https://www.scootersoftware.com/): Compare files and folders, merge changes, synchronize files and generate reports. Commercial software.

[KDiff3](https://kde.org/applications/development/org.kde.kdiff3): File and directory diff and merge tool

[Kompare](https://apps.kde.org/en/kompare): File and directory diff and merge tool with mirrored scrolling

[Diffuse](http://diffuse.sourceforge.net/): Graphical tool for merging and comparing text files

[Diffoscope](https://diffoscope.org/): Terminal utility for diff with colors for better visualization

[DiffPDF](http://www.qtrac.eu/diffpdf.html): Compare PDFs

[diff-pdf](https://vslavik.github.io/diff-pdf/): Compare PDFs (terminal)

[SuperTMXMerge](https://github.com/amake/SuperTMXMerge): Diff tool for comparing and merging TMX translation memories.

# Desktop search - Full text index

[Recoll](https://www.lesbonscomptes.com/recoll/)

Recoll allows you to search for keywords (with many search criteria, including fuzziness) inside documents as well as file names. It can be used to index specific directories for ad hoc documentary research. Recommended.

[DocFetcher](http://docfetcher.sourceforge.net/en/index.html)

Allows you to index select directories and search the contents of files on your computer. Great for ad hoc indexing your documentary research, your ebook library, etc. Sadly, no longer being developped.

[FSearch](https://github.com/cboxdoerfer/fsearch)

A fast and lightweight file search utility based on GTK+3. Similar to the (Windows only) Everything Search Engine, it provides instant (as you type) results, with RegEx and filter support among other features.

[AngrySearch](https://github.com/DoTheEvo/ANGRYsearch)

A fast file search utility based on QT5, that attempts to provide a Linux version of the Everything Search Engine available for Windows.

[Searchmonkey](https://sourceforge.net/projects/searchmonkey/)

Allows users to search for file names and contents using powerful regular expressions.

[Regexxer](http://regexxer.sourceforge.net/) is a GUI search/replace tool featuring Perl-style regular expressions.

[Gnome Shell](https://www.gnome.org/) Desktop Environment comes with a configurable built-in Tracker (Search), which allows for searching various types of content, including “full-text search”. If you don’t use it, you might as well disable it, to prevent full indexing.

[KDE Plasma 5](https://www.kde.org) Desktop Environment comes with baloo search, which indexes your home folder and can be configured to search only specific folders, to perform full content indexing (useful to find text in office files), and to allow searching hidden files and folders. Two setups are optimal for it: just leaving the defaults but with full content indexing disabled (openSUSE does this), or making it not search the home folder and only search (perhaps with full content indexing) in the Documents, Downloads, Pictures, Music and Videos folders (Fedora does this).

For simple, lightweight desktop search, you can use Tracker on GNOME, Baloo without full content indexing on Plasma, or [Catfish](http://www.twotoasts.de/index.php/catfish/).

Of course, there are also powerful command-line utilities for searching files (find), text searching for lines matching a regular expression (grep), etc.

# File rename utilities

[Nautilus (Files)](https://wiki.gnome.org/Apps/Files) file manager comes bundled with a bulk renamer (just select multiple files and press F2).

[Thunar](https://docs.xfce.org/xfce/thunar/start) file manager also includes an excellent [Bulk Rename](https://docs.xfce.org/xfce/thunar/bulk-renamer/start) utility.

[Dolphin](https://apps.kde.org/en/dolphin) file manager that includes numeric-based bulk renaming (file1.txt, file2.txt etc)

[KRename](https://apps.kde.org/en/krename) is a flexible program for bulk renaming based on text patterns.

# Text editors

[Gedit](https://wiki.gnome.org/Apps/Gedit) and [Kate](https://kate-editor.org/) are two of the nice default text editors available.

[Geany](https://geany.org/) is a great lightweight text editor and Integrated Development Environment (IDE).

Text editors with even richer functions (also meant for coding) include GitHub’s [Atom](https://atom.io/), [Visual Studio Code](https://code.visualstudio.com), [Sublime Text](https://www.sublimetext.com/) (free/paid) and [Brackets](http://brackets.io/).

For historical reasons, I’ll also include two of the oldest editors, with some hardcore fans: [Vim](https://www.vim.org/) and [GNU Emacs](https://www.gnu.org/software/emacs/) (see also [Editor wars](https://en.wikipedia.org/wiki/Editor_war)).

**Markdown editors**

Atom, Visual Studio Code, Sublime Text, Brackets and even Geany all support Markdown syntax, with or without add-ons.

Three of the best dedicated Markdown editors/viewers are [Typora](https://typora.io), [Zettlr](https://www.zettlr.com) and [Obsidian](https://obsidian.md).

# Productivity tools selection

## AutoKey (Py3)

A Python 3 port of [AutoKey](https://github.com/autokey/autokey), the desktop automation utility for Linux and X11. It allows you to manage a collection of scripts, and assign abbreviations and hotkeys to these scripts allowing you to execute them on demand in whatever program you are using. It can also be used as a text expander, where you store phrases (snippets of text) to be reused across various applications by typing an abbreviation or a keyboard shortcut.

[Wiki](https://github.com/autokey/autokey/wiki), [OldAutokey](https://code.google.com/archive/p/autokey/) page and [user group](https://groups.google.com/g/autokey-users).

## ibus-typing-booster

[Ibus-typing-booster](https://mike-fabian.github.io/ibus-typing-booster/) is an intelligent context sensitive completion input method to speed-up typing. It supports most languages (except Chinese and Japanese).

Note: CafeTran Espresso, OmegaT and other CAT tools already implement predictive typing/auto-completion features.

## Reduce eye-strain

Utilities that adjusts the color temperature of your display(s) according to the position of the sun.

[f.lux](https://justgetflux.com/)

[Redshift](http://jonls.dk/redshift/). Also available as a [Gnome shell extension](https://extensions.gnome.org/).

Note: the GNOME and Plasma Desktop environments also sport integrated Night mode. In GNOME it can be found under Settings > Displays, in Plasma it can be found under System Settings > Display and Monitor > Night Color.

## Clipboard managers

[GPaste](https://github.com/Keruspe/GPaste)

[Parcellite](http://parcellite.sourceforge.net/)

[CopyQ](https://hluk.github.io/CopyQ)

[Klipper](https://userbase.kde.org/Klipper)

## Screenshots

Beyond the standard screenshot capabilities of the desktop environment (Gnome, KDE, etc.), there are separate apps that take it one step further:

[Shutter](http://shutter-project.org/)

[Lightscreen](https://lightscreen.com.ar/)

[Flameshot](https://github.com/lupoDharkael/flameshot)

## Screen recording - Screencasting

[SimpleScreenRecorder](http://www.maartenbaert.be/simplescreenrecorder/) Excellent and easy-to-use screen recorder

[Peek](https://github.com/phw/peek) animated GIF/video Screen Recorder

[Open Broadcaster Software](https://obsproject.com/) Full-featured cross-platform screen recording and live streaming software.

[recordMyDesktop](http://recordmydesktop.sourceforge.net/about.php)

## Time and Project tracking

[Project Hamster](https://github.com/projecthamster/)

[TMetric](https://tmetric.com/)

[TimeCamp](https://www.timecamp.com/)

[RescueTime](https://www.rescuetime.com/)

[Toggl](https://toggl.com)

[Super Productivity](https://github.com/johannesjo/super-productivity)

## Pomodoro timers

[Gnome Pomodoro](http://gnomepomodoro.org/)

[PomoDoneApp](https://pomodoneapp.com/)

[Pomello](https://pomelloapp.com/)

## Unit conversion

[ConvertAll](http://convertall.bellz.org/) (offline)

## On-screen keyboard

**Onboard** is an excellent on-screen (virtual) keyboard. Handy if you wish to remember how to type less frequent characters for your language.

# Running GNU-Linux on Windows via WLS
The Windows Subsystem for Linux ([WLS](https://docs.microsoft.com/en-us/windows/wsl/)) lets you run a GNU/Linux environment -- including most command-line tools, utilities, and applications -- directly on Windows, unmodified, without the overhead of a traditional virtual machine or dual-boot setup.

This means you are able to [run Linux distributions and applications side-by-side](https://docs.microsoft.com/en-us/windows/wsl/install) with Windows. WLS requires Windows 10 (Build 19041 and higher) and Windows 11.

# Running Windows applications on Linux

## Natively on WINE

[Wine](https://www.winehq.org/) (an acronym for “Wine Is Not an Emulator”) is a free and open-source compatibility layer that aims to allow computer programs developed for Microsoft Windows to run on Unix-like operating systems. Instead of simulating internal Windows logic like a virtual machine or emulator, Wine translates Windows API calls into POSIX calls on-the-fly, eliminating the performance and memory penalties of other methods and allowing you to cleanly integrate Windows applications into your desktop.

Running Windows software on Linux can sometimes be a complex endeavor, however, you get to install and run many Windows programs via Wine (and its helper script, [Winetricks](https://wiki.winehq.org/Winetricks)).

To see the support status of a specific application and version, you can use the Wine’s [official website](https://www.winehq.org/). Not all software is represented.

Since each Windows app has different requirements, it is usually recommended to create different Wine “prefixes”.

Two applications aim to make it easy to install Windows programs in such separate locations:

- [CrossOver](https://www.codeweavers.com/): The company CodeWeavers markets CrossOver specifically for running Microsoft Office and other major Windows applications. It is a commercial software which builds upon Wine.
- [PlayOnLinux](https://playonlinux.com/): Currently under heavy development and transition, PlayOnLInux is the free pendant to CrossOver.

Some examples of useful translation-related applications that run well on Linux via Wine (mostly PlayOnLinux and Crossover) are the following:
- Microsoft Office 2010, 2013 and 2016, [XBench](https://www.xbench.net/index.php/download), and [Glossary Converter](http://www.cerebus.de/glossaryconverter/). For the GUI Windows version of [LF Aligner](https://sourceforge.net/projects/aligner/) (with a nice interface for splitting-merging aligned segments), just run it with Wine. Same goes for [TMLookup](http://www.farkastranslations.com/tmlookup.php), an open-source tool to search bilingual and multilingual text databases (translation memories) and glossaries. [Ron’s Editor](https://www.ronsplace.eu/Products/RonsEditor) excellent CSV File Editor works after installing .Net Framework 4.5.2.

Many Windows programs that require specific versions of the .NET framework can be installed successfully after installing these first. Tip: Trial versions can be easily reinstalled since you can create separate machines with a few clicks.

## Through a Windows Virtual Machine (VM)

The recommended free and easy way to install a Windows virtual machine and run it inside GNU/Linux is through a cross-platform application called [VirtualBox](https://www.virtualbox.org/).

With Virtualbox (provided you also install the extension pack and guest additions), you can run Windows in fullscreen mode, use USB and other devices, share folders or clipboard between the two systems (the Linux host and the Windows client), take advantage of the Internet connection, and more. There’s no need to shut down and restart the Windows VM, you can simply save the VM state, for a quick reuse anytime.

This means you can run (almost) any Windows software while staying on Linux, including SDL Trados, memoQ, Deja Vu, Transit, ABBYY Finereader, Adobe Photoshop, Indesign, Illustrator, Premiere, etc. Working within a VM can be slightly inconvenient in the long run, so running such Windows applications is better left for occasional use only. Other CAT tools should be favored for primary use, but it is nice to know that you can still launch such Windows apps and utilities should your workflow require it.

<!--- Examples of utilities: Glossary Converter, GoldPan Editor, ExcellMerge, ExcellDiff  --->

Running a VM requires assigning some of your computer RAM to Windows operation, so it is preferable to have enough RAM, to begin with. The more, the better, starting from 8 GB.

Other virtualization applications worth mentioning:

Paid: [Parallels](https://www.parallels.com/)
Free/Paid: [VMware](https://www.vmware.com/)
Free: [QEMU](https://www.qemu.org/)

<!-- Probably worth adding the information available on https://rabbitictranslator.com/wordpress/index.php/2020/07/04/fluff-linux-sessions/ since, although a niche case, this method can be used to maximize performance enough so as to run Windows well on 4GB machines with HDD. -->

## Via Dual Boot - On a separate machine

You can also install GNU/Linux alongside Windows on your PC (which is often recommended as a first step for newcomers, although interested users with Windows 10/11 should also check out WLS) or on a separate machine.

Happy translating!

# Updates

- 20180408 Initial wiki upload
- 20180622 Small update
- 20180728 Added terminology management section/CAT tools > Wordbee/Screen recording software, and minor edits
- 20180731 Added TMXEditor under TMX editing and Anchovy under Term extraction
- 20180830 Added XTM Cloud in Online CAT tools
- 20180901 Added Infix PDF Editor and TransPDF
- 20181112 Added Flantie in Project management & Invoicing, FSearch and AngrySearch in Desktop search, TimeCamp in Time/Project tracking, PyGlossary in Dictionary lookup.
- 20181213 Fixed dead link for LibreOffice Writer/MS Word track changes compatibility. Added Able2Extract Professional for PDF conversion and OCR.
- 20191020 Minor update. CafeTran Espresso demo mode does not support unlimited TMX editing anymore. Added Olifant to "Translation Memory (TMX) Editing/Maintainance" tools. Google Translation toolkit will be soon decommissioned, so it has been removed from the list of online CAT tools.
- 20191105 SRXEditor is now open source and available as a standalone cross-platform program. Memsource editors renamed to Memsource Editor for Desktop and Memsource Editor for Web. Added an Antivirus section. Added ODA File Converter for .dwg and .dxf files. Added a few more Diff tools (Diffuse, KDiff3). Removed XLIFFChecker, added XLIFF Manager. Windows 10 can run Linux distribution side-by-side, without VMs.
- 20191108 Contributor update (added content for LibreOffice, OnlyOffice, FlexiPDF and Lokalize plus minor edits).
- 20200218 Fixed TOC, added ibus-typing-booster
- 20200611 Various minor content edits. Contributor update: added Termsoup and DGT-OmegaT under CAT tools, added the CLI ABBYY FineReader Engine for Linux under OCR and PDF to text, added a section for command-line office file conversions under Office software. Mention for FileOpen (localization-related utilities) and ImageTranslate (image localization) and TMetric (time tracking). Stingray document aligner is now open source.
- 20201128 Contributor update, many content edits. Added license for OmegaT and Heartsome; mentioned Memsource mobile; Virtaal in maintenance mode; add QtLinguist, Kompare, Diffoscope, baloo, Dolphin, KRename; Matecat Chrome-only, VM gone; descriptions for Smartcat, Transifex, Weblate, Pontoon, translate-toolkit, WPS, Softmaker, OnlyOffice, SubtitleComposer, GNOME/Plasma utilities, Microsoft fonts; XDG fonts; hunspell for LibreOffice.
- 20211123 Updated all content and fixed broken links. Swordfish VI and all maxprograms.com applications are now open source and free to use (with optional paid subscription for binaries and support). WFP 3 is legacy now. MateCat sports an aligner. Matecat filtrers removed (no longer offered as Open Source). Mention of markdown editors. Google Docs now offers Microsoft Office editing. Removed Antivirus section for now.

# Feedback

You can send me feedback via a [ProZ message](https://www.proz.com/?sp=mailsend&eid_s=2042360). Please start your subject with the name of the document: “TranslateOnLinux”.

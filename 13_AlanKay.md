# **アラン・ケイ：パーソナルコンピューティングのパイオニアとその思想**

## **1\. 序論**

アラン・カーティス・ケイ博士は、コンピュータ科学の歴史において、パーソナルコンピュータの概念を先見	的に提唱し、その実現に不可欠な基盤技術の多くを創造した、極めて影響力のある人物である。彼が主導したオブジェクト指向プログラミングやグラフィカルユーザインターフェース（GUI）の開発は、現代のコンピュータ利用のあり方を根本から形作った 1。しかし、ケイ博士の貢献は単なる技術的発明に留まらない。彼の業績の根底には、コンピュータを人間の知的能力を拡張し、創造性を涵養するための「パーソナルダイナミックメディア」として捉える一貫したビジョンが存在した 1。このビジョンは、特に子供たちの学習プロセスへの深い関心と結びついており、彼の技術開発の方向性に決定的な影響を与えた 1。

本稿では、まずケイ博士の生い立ちから初期の研究活動を概観し、次にゼロックス・パロアルト研究所（PARC）での革新的な業績、特にダイナブック構想、Smalltalkの開発、GUIへの貢献を詳述する。続いて、彼の思想形成に影響を与えた時代背景と知的源泉を考察し、最後に、現代のコンピュータ技術、ソフトウェア開発、インタラクションデザイン、そして教育への広範な影響を明らかにする。

## **2\. 経歴と初期の業績**

アラン・ケイは1940年5月17日、米国マサチューセッツ州スプリングフィールドで生を受けた 2。幼少期から読書に親しみ、3歳で流暢に文章を読みこなすなど、早くからその知的な才能の片鱗を見せていた 2。コロラド大学では数学と分子生物学という異なる分野で学士号を取得し、同時にプロのジャズギタリストとしても活動するなど、その学際的な関心と能力は特筆に値する 2。この多様な経験は、後にコンピュータを単なる計算機としてではなく、より柔軟で複合的なシステム、表現の媒体として捉える彼のユニークな視座の形成に寄与したと考えられる。例えば、分子生物学におけるシステムとしての生命の理解は 2、後のオブジェクト指向における生物学的アナロジー（メッセージングによる自律的なオブジェクト間の協調など）に繋がった可能性が示唆される 7。

コンピュータプログラミングとの出会いは空軍士官候補生時代であり、ここで自身の適性を見出した 2。1966年、ユタ大学大学院工学部に進学し、1969年には計算機科学の博士号を取得している 1。このユタ大学時代は、ケイのキャリアにおいて極めて重要な時期であった。特に、「コンピュータグラフィックスの父」と称されるアイバン・サザランドとの出会いは決定的であった。サザランドの指導のもと、画期的な対話型グラフィックスシステムであるSketchpadの開発に関与した経験は 2、後のオブジェクト指向プログラミングやGUIに関するケイの着想の萌芽となった。Sketchpadにおける図形の親子関係やインスタンス生成といった概念は、オブジェクトとクラスという後のSmalltalkの核心的概念と通底するものであった。

さらに、ユタ大学ARPA（高等研究計画局）研究チームの一員として、3Dグラフィックス技術の開発や、インターネットの原型であるARPANETの初期設計にも参画した 3。ARPANETへの関与は、コンピュータネットワークの将来的な重要性を早期に認識させ、後のダイナブック構想における無線ネットワーク機能の組み込み 1 という先見性へと繋がった。これは、コンピュータを個々の独立したツールとしてだけでなく、相互接続されたコミュニケーションと協調のためのメディアとして捉える視点の現れであった。また、初期の対話型オブジェクト指向パーソナルコンピュータであるFLEXマシンの共同設計者としても名を連ねている 3。FLEXマシンは、グラフィカルインターフェースとオブジェクト指向の要素を内包しており、ケイがパーソナルでインタラクティブなコンピューティング環境を探求する上での重要な布石となった。

このように、ケイの初期のキャリアは、グラフィックス、ネットワーク、オブジェクト指向といった、後のパーソナルコンピューティングを構成する核心的な要素群との早期かつ深い関わりによって特徴づけられる。これらの要素は、ユタ大学時代に既に萌芽として存在し、相互に関連しながら後のゼロックスPARCでの包括的なシステム開発へと結実していくことになる。

## **3\. ゼロックス・パロアルト研究所(PARC)時代と主要な発明**

1970年、アラン・ケイはゼロックス社のパロアルト研究所（PARC）の創設メンバーとして参画し、ここで彼の最も影響力のある業績の多くが生み出されることになる 2。PARCにおいてケイが率いたラーニングリサーチグループ（LRG）は、コンピュータを子供たちの知的探求と創造活動を支援する革新的な学習ツールとして開発することを使命としていた 3。この目標設定自体が、当時のコンピュータ研究の主流とは一線を画すものであり、技術開発の初期段階から教育への強い応用志向を持っていたことが窺える 14。

### **3.1 ダイナブック (Dynabook) 構想**

ケイの最も有名な構想の一つが「ダイナブック」である。これは1968年に「KiddiComp」として初期のアイデアが生まれ、1972年の論文「すべての年齢の子供たちのためのパーソナルコンピュータ (A Personal Computer for Children of All Ages)」において、その詳細なビジョンが提示された 1。ダイナブックは、薄型で持ち運び可能、高解像度のフラットスクリーン、直感的なグラフィカルインターフェース、キーボード、そして無線ネットワーク接続機能を備えた、個人のための動的な情報操作・学習・創造デバイスとして構想された 1。これは、現代のノートパソコンやタブレット端末の直接的な原型と言える先駆的なアイデアであった。

重要なのは、ダイナブックが単なるハードウェアの概念に留まらず、ソフトウェアと教育カリキュラムが不可分に統合された「学習環境」としての性格を強く持っていた点である 8。ケイは、ハードウェアが技術的に実現可能になった現代においても、適切なソフトウェアと教育的枠組みが伴わなければ、ダイナブックは真に発明されたとは言えないと繰り返し述べている 8。PARCで開発されたAltoコンピュータは、このダイナブック構想を実現するための中間段階、「暫定ダイナブック (interim Dynabook)」として位置づけられ、多くの革新的技術の実験プラットフォームとなった 2。

### **3.2 Smalltalkの開発**

ダイナブック構想のソフトウェア面を支える中核技術として開発されたのが、プログラミング言語Smalltalkである。これは、世界初の完全なオブジェクト指向プログラミング言語であり、同時に統合開発環境、さらにはオペレーティングシステムとしての機能も備えていた 1。アラン・ケイが中心となり、ダン・インガルス、アデル・ゴールドバーグらLRGの優秀な研究者チームによって開発が進められた 43。

Smalltalkの設計思想は、ケイが提唱したオブジェクト指向の核心的原則に基づいている。すなわち、「メッセージング」によるオブジェクト間のコミュニケーション、「ローカルな状態保持と保護（カプセル化）」によるデータの隠蔽、そして「極端な遅延束縛（レイトバインディング）」による実行時の柔軟性である 13。ケイのオブジェクト指向観は、生物細胞の振る舞いをメタファーとしており、各オブジェクトが自律的なコンピュータのように振る舞い、メッセージの送受信によってのみ相互作用するという、当時の手続き型プログラミングとは根本的に異なるパラダイムを提示した 7。この思想は、ソフトウェアの設計と構築の方法に革命をもたらし、今日の複雑な情報システムの開発に不可欠な概念となっている。

### **3.3 グラフィカルユーザインタフェース (GUI) への貢献**

ケイとLRGのチームは、Smalltalk環境とAltoコンピュータ上で、現代のグラフィカルユーザインタフェース（GUI）の基礎となる多くの要素を発明、あるいは実用化した 1。具体的には、複数の情報を同時に表示し、効率的な作業を可能にするオーバーラッピングウィンドウ、機能を視覚的に表現するアイコン、状況に応じてコマンドを選択できるプルダウンメニューやポップアップメニュー、そしてマウスによるポインティングデバイスの採用などが挙げられる。

これらのGUI要素は、ビットマップディスプレイの能力を最大限に活用し、ユーザーがコンピュータと直感的かつ視覚的に対話することを可能にした。また、WYSIWYG (What You See Is What You Get) エディタの開発は、画面上で見たままの形で文書やグラフィックを編集・印刷できる環境を提供し、後のデスクトップパブリッシング（DTP）の隆盛に繋がった。さらに、イーサネットによるローカルエリアネットワーク（LAN）技術の開発への関与は、パーソナルコンピュータがスタンドアロンの機械からネットワーク化された情報共有・協調作業ツールへと進化する上で不可欠な要素であった 1。

PARCにおけるケイの業績群、すなわちダイナブック構想、Smalltalk、そしてGUI関連技術は、個別の発明として捉えるのではなく、一つの壮大なビジョン―コンピュータを個人の知的活動と創造性を増幅する「パーソナルダイナミックメディア」へと変革する―の実現に向けた、相互に連携し合う統合的なイノベーションであったと理解することが重要である。Altoはダイナブックの暫定的な姿であり 2、Smalltalkはその上で動作する柔軟なソフトウェア環境を提供し 43、GUIはその環境との直感的な対話を可能にした 47。このハードウェア、ソフトウェア、インターフェース、そしてそれらを支える設計思想の緊密な連携こそが、PARCをしてパーソナルコンピューティング革命の震源地たらしめた要因と言えるだろう。

ケイが提唱した「暫定ダイナブック」としてのAltoの開発戦略は、未来の技術を先取りして実験環境を構築するという、彼の「未来を発明する」方法論の具体的な現れであった。ムーアの法則を逆算し、将来のコンピューティングパワーを現在の高価なハードウェアで「偽装」することで、当時の技術的制約を超えた革新的なアイデアの探求を可能にしたのである 11。この戦略が高コストながらも、SmalltalkやGUIといった野心的なプロジェクトの実験を可能にし、後のパーソナルコンピューティングの標準となる多くの概念を生み出す土壌となった。

## **4\. 思想的背景と影響**

アラン・ケイの革新的な業績の背後には、彼自身の学際的な知的好奇心と、同時代の様々な思想家や技術者からの影響が存在した。彼のコンピュータ観は、単なる技術的関心に留まらず、人間がどのように学び、創造し、世界と関わるかという根源的な問いへと繋がっていた。

### **4.1 主要な影響源**

* **マーシャル・マクルーハン (Marshall McLuhan):** カナダのメディア理論家であるマクルーハンの「メディアはメッセージである」という有名なテーゼは、ケイに深い影響を与えた 6。ケイは、コンピュータを単なる情報処理の道具としてではなく、人間の思考様式やコミュニケーションのあり方そのものを変容させる力を持つ新しい「メディア」として捉えた。マクルーハンが指摘したように、新しいメディアを理解し使いこなすためには、人間自身がそのメディアの特性を内面化する必要があるという洞察は、ケイがダイナブック構想において、ユーザーがコンピュータというメディアと深く関わることで新たな思考や表現を獲得することを目指した点と共鳴する。ケイはコンピュータを、既存のあらゆるメディアを包含し、それらを動的に組み合わせ、ユーザーが対話的に操作できる「メタメディア」として構想した 6。  
* **シーモア・パパート (Seymour Papert) と構成主義的学習論:** MITの数学者・計算機科学者であり、LOGOプログラミング言語の開発者であるパパートとの出会いは、ケイの教育に対する考え方に大きな影響を与えた 1。パパートは、子供たちがコンピュータを使ってプログラミング（LOGOタートルを動かすなど）を経験することを通じて、抽象的な数学的概念や問題解決能力を能動的に「構築」していくという構成主義的学習論を提唱した。この思想は、ケイがダイナブックを「子供たちのための」学習ツールとして位置づけ、SmalltalkやEtoysといったプログラミング環境を子供たちにも理解しやすく、創造性を刺激するように設計する上で中心的な役割を果たした。  
* **ジャン・ピアジェ (Jean Piaget) とジェローム・ブルーナー (Jerome Bruner):** スイスの発達心理学者ピアジェの子供の認知発達段階に関する理論や、アメリカの心理学者ブルーナーが提唱した学習における三段階の表象モード（enactive: 行動的、iconic: 映像的、symbolic: 象徴的）は、ケイのGUI設計思想に直接的な影響を与えた 2。特にブルーナーのEISモデルは、ケイがGUIのインタラクションを「Doing With Images makes Symbols（イメージを伴う実行がシンボルを作る）」という原則で捉える上で理論的根拠となった。マウスによる直接操作（doing）、画面上のアイコン（images）、そしてSmalltalkのようなプログラミング言語（symbols）という対応関係は、ユーザーが具体的な操作から視覚的な理解を経て、より抽象的な概念操作へと自然に移行できるような学習プロセスをインターフェース設計に組み込む試みであった。  
* **アイバン・サザランド (Ivan Sutherland) とダグラス・エンゲルバート (Douglas Engelbart):** サザランドのSketchpadが示した、オブジェクトを直接操作し、その属性を変更できるという対話的なグラフィックシステムは、後のオブジェクト指向の考え方に繋がる重要な示唆を与えた 2。一方、エンゲルバートが1968年に行ったNLS (oN-Line System) の歴史的なデモンストレーション、通称「The Mother of All Demos」は、マウス、ハイパーテキスト、ウィンドウシステム、リアルタイム共同編集といった、後のパーソナルコンピューティングの標準となる多くの機能を統合的に提示し、ケイを含む当時の研究者たちに強烈な衝撃とインスピレーションを与えた 2。エンゲルバートの「人間の知能を増強する (augmenting human intellect)」という思想は、ケイのパーソナルコンピューティングのビジョンと深く共鳴するものであった。  
* **J.C.R. リックライダー (J.C.R. Licklider):** ARPAの情報処理技術部長として、「人間とコンピュータの共生 (Man-Computer Symbiosis)」というビジョンを掲げ、対話型コンピューティングやネットワーク技術の研究を強力に推進したリックライダーの思想もまた、ケイに影響を与えた 4。リックライダーは、コンピュータを単なる高速計算機としてではなく、人間の思考を助け、創造性を刺激するパートナーとして捉えるべきだと主張した。この人間中心のコンピュータ観は、ケイがダイナブックを個人の知的活動を支援するメディアとして構想する上で、重要な思想的背景となった。

### **4.2 「パーソナルダイナミックメディア (Personal Dynamic Media)」の概念**

これらの影響を背景に、ケイは1977年にアデル・ゴールドバーグとの共著論文「Personal Dynamic Media」において、自身のコンピュータ観を明確に提示した 1。この概念は、コンピュータを、個人の学習、発見、探求、コミュニケーション、そして芸術的創造のための、動的で応答性の高い個人的なメディアとして定義するものであった。

ケイが目指したのは、単に既存のメディア（書籍、絵画、音楽、映像など）をデジタル的に模倣することではなかった。むしろ、コンピュータという新しいメディアが持つ独自の特性―検索可能性、編集可能性、対話性、ネットワーク性、プログラマビリティなど―を活用することで、従来のメディアの限界を超え、全く新しい表現と学習の可能性を開く「メタメディア」としてのコンピュータの姿を構想したのである 6。この「パーソナルダイナミックメディア」というビジョンは、ケイのその後の研究開発活動全体を貫く指導原理となった。

ケイの思想的背景を考察すると、彼が単なる技術者や発明家という枠を超え、コンピュータの本質とそれが人間社会、特に教育や創造性の領域にどのような影響を与えるかについて深く思索する哲学者、教育者としての側面が浮かび上がってくる。彼の発明の多くは、技術的課題の解決というよりも、人間がどのように学び、創造し、他者と効果的に相互作用するかという、より根源的な問いから生まれていると言えるだろう。ダイナブック構想が繰り返し「子供たちのための」と強調されるのは、その思想の最も象徴的な現れである 1。

ケイの「パーソナルダイナミックメディア」という概念は、現代のインターネット、マルチメディア、ソーシャルメディア、さらにはAR（拡張現実）やVR（仮想現実）といった没入型メディアの発展を予見していただけでなく、それらが持つべき理想的な姿―ユーザーによる創造性の発揮、深い学習の促進、そして人間同士のより豊かなコミュニケーションの実現―をも示唆していたと言える。彼の先見性は、技術の進展が著しい現代においても、我々がテクノロジーとどのように向き合うべきかという問いに対して、重要な示唆を与え続けている。

## **5\. 現代のデザインと教育への影響**

アラン・ケイの業績とその思想は、現代のコンピュータ技術、ソフトウェア開発、インタラクションデザイン、そして教育のあり方に計り知れない影響を与え続けている。

### **5.1 パーソナルコンピュータとGUIの普及**

ゼロックスPARCで開発されたAltoコンピュータとSmalltalk環境で具現化されたGUIのコンセプトは、スティーブ・ジョブズをはじめとするAppleのエンジニアに強い感銘を与え、Lisa及びMacintoshの開発に決定的な影響を及ぼした 1。Macintoshの成功を通じて、オーバーラッピングウィンドウ、アイコン、マウスといったGUIの要素は一般に普及し、その後のパーソナルコンピュータにおける標準的なユーザーインターフェースとなった。このことは、研究室レベルで生まれた革新的なアイデアが、優れたデザインとビジョンによって商業的に成功し、社会全体のコンピュータ利用体験を根底から変革した顕著な事例である。

### **5.2 オブジェクト指向プログラミングの浸透**

Smalltalkで確立されたオブジェクト指向プログラミングの諸概念（メッセージング、カプセル化、継承、ポリモーフィズムなど）は、その後のプログラミング言語設計の主流となった。Java、C++、Objective-Cといった現代の主要なプログラミング言語は、Smalltalkから直接的または間接的に多大な影響を受けており 1、大規模で複雑なソフトウェアシステムの開発において、オブジェクト指向は不可欠なパラダイムとして広く採用されている。

### **5.3 ソフトウェア開発方法論への寄与**

Smalltalkの対話的でインクリメンタルな開発スタイル、すなわち「ライブコーディング」や迅速なプロトタイピングを可能にする環境は、アジャイルソフトウェア開発やRAD（ラピッドアプリケーション開発）といった現代的な開発方法論の思想的源流の一つと見なすことができる 7。また、ケイ自身がSqueakをオープンソースプロジェクトとして推進したように 1、彼の思想は、コードの公開、コミュニティによる協調的な改善といったオープンソースの精神とも親和性が高い。ケイは、ソフトウェアシステムがエラーを検出し修正しながら成長していく能力の重要性を説き、オープンソースのような分散的で協調的な開発モデルが、そのような自己改善的なシステム構築に適している可能性を示唆している 24。

### **5.4 インタラクションデザインの原則の確立**

ケイが提唱し、Smalltalk環境で実践したユーザーインターフェースの設計原則は、現代のインタラクションデザインおよびUX（ユーザーエクスペリエンス）デザインの基礎となっている。ユーザーの認知プロセスを重視したユーザー中心設計の思想、画面上のオブジェクトを直接操作する感覚、システムからの即時的で理解しやすいフィードバックの重要性などは、その代表例である 12。特に、ジェローム・ブルーナーの学習理論に基づいた「Doing With Images makes Symbols（イメージを伴う実行がシンボルを作る）」という認知モデル 6 は、ユーザーがシステムを段階的に理解し、習熟していくためのインターフェース設計において、今日でも有効な指針を提供している。

### **5.5 Squeak/Etoysと教育分野での実践**

ダイナブックの教育的理念を直接的に継承するプロジェクトとして、ケイはSqueak Etoysの開発を主導した 1。Squeak Etoysは、子供たちが視覚的なオブジェクトを操作し、タイルベースのスクリプトを組むことで、プログラミングの基本的な概念や、数学・科学の原理を構成主義的に学ぶことを可能にする、強力かつ柔軟なオーサリング環境である。このツールは、子供たちが自ら問題を定義し、解決策を考案し、それをコンピュータ上で実現するという創造的な学習サイクルを支援する。また、ケイはニコラス・ネグロポンテが主導したOLPC (One Laptop Per Child) プロジェクトにも深く関与し、Squeak Etoysを搭載した安価なラップトップを開発途上国の子供たちに提供することで、教育機会の格差解消にも貢献しようとした 4。

アラン・ケイの遺産は、彼が開発に貢献した個々の技術や製品そのものに留まらない。より本質的なのは、コンピュータを人間の知性、創造性、学習、そして協調作業を根源的に変革しうる「パーソナルダイナミックメディア」として捉え、その実現に向けた包括的な思想と実践を提示した点にある 1。ダイナブックは単なる小型コンピュータの設計図ではなく、Smalltalkは単なるプログラミング言語ではなく、GUIは単なる操作画面ではなく、それぞれが人間とコンピュータのより良い共生関係と、人間の知的潜在能力の拡張を目指すという、教育的かつ哲学的とも言える深い問いから生まれたものであった。

ケイが繰り返し述べた「コンピュータ革命はまだ起こっていない」という言葉 11 は、技術が真に人間の能力を解放し、万人のための創造的メディアとして十分に活用されるためには、単なる消費者ではなく「創造者」としてのユーザーを育成する必要があるという、今日ますます重要性を増す課題を示唆している。彼の思想は、現代のUXデザイン、教育工学、知識創造、そしてAIが遍在化する社会における人間とテクノロジーの協調のあり方を考える上で、依然として重要な参照点であり続けている。

## **6\. 結論**

アラン・ケイの業績は、パーソナルコンピューティングの技術的基盤を構築しただけでなく、コンピュータを人間の知性と創造性を飛躍的に拡張するための「パーソナルダイナミックメディア」と捉えるという、コンピュータ観における根本的なパラダイムシフトを提示した点に最大の意義がある。彼の先見的な洞察と、特に子供たちの教育に対する深いコミットメントは、今日のデジタル社会のあり方、そして未来のテクノロジーと人間の関係性に対しても、依然として大きな影響を与え続けている。

ダイナブック構想、Smalltalk、GUI、オブジェクト指向といった彼の主要な貢献は、それぞれが独立した輝かしい発明であると同時に、より大きなビジョン―人間中心のコンピューティング環境の実現―の一部として相互に連携し、その全体像を構成していた。この統合的なアプローチこそが、彼のイノベーションの核心であった。

特に、「ユーザー自身がツールを創造し、それを通じて思考を拡張する」という彼の思想は、AIやXR（Extended Reality）といった新たな技術が社会に浸透しつつある現代において、人間とテクノロジーのより生産的で創造的な共生関係を構築するための重要な指針となる。ケイが示した「コンピュータ革命はまだ終わっていない」という視点は、テクノロジーが真に人間の可能性を解放し、万人のための創造的メディアとなるための探求が、今後も継続していくことを力強く示唆している。彼が遺した知的遺産は、これからの情報社会をデザインする上で、繰り返し参照され、再解釈されるべき価値を持つと言えるだろう。

## **7\. 参考文献**

以下に、本レポート作成にあたり参照した主要な論文及び関連資料の一部を挙げる。

* Kay, A. C. (1972). A Personal Computer for Children of All Ages. *Proceedings of the ACM Annual Conference*, Boston. 1  
* Kay, A. C., & Goldberg, A. (1977). Personal Dynamic Media. *IEEE Computer*, *10*(3), 31-41. 1  
* Kay, A. C. (1993). The Early History of Smalltalk. In T. J. Bergin & R. G. Gibson (Eds.), *History of Programming Languages II* (pp. 511-598). ACM Press. (初出は1993年のACM SIGPLAN Notices, 28(3), 69-95) 13  
* Kay, A. C. (1990). User Interface: A Personal View. In B. Laurel (Ed.), *The Art of Human-Computer Interface Design* (pp. 191-207). Addison-Wesley. 12  
* ビューポインツ・リサーチ・インスティテュート (Viewpoints Research Institute) のウェブサイト及び関連資料 28  
* コンピュータ歴史博物館 (Computer History Museum) のアラン・ケイに関する資料 4  
* 全米技術アカデミー (National Academy of Engineering) のチャールズ・スターク・ドレイパー賞に関する資料 1  
* 京都賞財団 (Inamori Foundation) の京都賞に関する資料 1  
* ACM (Association for Computing Machinery) のチューリング賞及び関連資料 2

## **付録**

**表1: アラン・ケイの主要な受賞歴と栄誉**

| 受賞年 | 賞の名称 | 授与機関 | 主な受賞理由（判明している場合） | 出典例 |
| :---- | :---- | :---- | :---- | :---- |
| 1987年 | ACMソフトウェアシステム賞 (ACM Software System Award) | ACM (Association for Computing Machinery) | Smalltalk開発における貢献 | 1 |
| 1999年 | コンピュータ歴史博物館フェロー (Computer History Museum Fellow) | コンピュータ歴史博物館 (Computer History Museum) | オブジェクト指向プログラミング、パーソナルコンピューティング、GUIへの先駆的貢献 | 1 |
| 2001年 | C\&C賞 (C\&C Prize) | NEC C\&C財団 (NEC C\&C Foundation) | パーソナルコンピュータとネットワーク化されたコンピューティング環境の概念創出と実現への貢献 | 1 |
| 2003年 | チューリング賞 (Turing Award) | ACM (Association for Computing Machinery) | オブジェクト指向プログラミング言語の根底にある多くのアイデアの先駆的貢献、Smalltalk開発チームの指揮、パーソナルコンピューティングへの基礎的貢献に対して | 1 |
| 2004年 | 京都賞先端技術部門 (Kyoto Prize in Advanced Technology) | 稲盛財団 (Inamori Foundation) | 現代のパーソナルコンピュータの概念の創出とその実現への多大な貢献 | 1 |
| 2004年 | チャールズ・スターク・ドレイパー賞 (Charles Stark Draper Prize) | 全米技術アカデミー (National Academy of Engineering) | 初の実用的なネットワーク化パーソナルコンピュータの構想、概念化、開発に対して（バトラー・ランプソン、ロバート・テイラー、チャック・サッカーと共同受賞） | 1 |
| 2008年 | ACMフェロー (ACM Fellow) | ACM (Association for Computing Machinery) |  | 2 |
| 2011年 | ハッソ・プラットナー研究所フェロー (Hasso-Plattner-Institut Fellow) | ハッソ・プラットナー研究所 (Hasso-Plattner-Institut) |  | 2 |

#### **Works cited**

1. アラン・カーティス・ケイ | 京都賞, accessed May 26, 2025, [https://www.kyotoprize.org/laureates/alan\_curtis\_kay/](https://www.kyotoprize.org/laureates/alan_curtis_kay/)  
2. アラン・ケイ \- Wikipedia, accessed May 26, 2025, [https://ja.wikipedia.org/wiki/%E3%82%A2%E3%83%A9%E3%83%B3%E3%83%BB%E3%82%B1%E3%82%A4](https://ja.wikipedia.org/wiki/%E3%82%A2%E3%83%A9%E3%83%B3%E3%83%BB%E3%82%B1%E3%82%A4)  
3. Dr. Alan C. Kay \- NAE Website, accessed May 26, 2025, [https://www.nae.edu/55013/Dr-Alan-C-Kay-](https://www.nae.edu/55013/Dr-Alan-C-Kay-)  
4. Alan Kay \- CHM, accessed May 26, 2025, [https://computerhistory.org/profile/alan-kay/](https://computerhistory.org/profile/alan-kay/)  
5. PC Pioneer Alan Kay Wins Kyoto Prize \- TechNewsWorld, accessed May 26, 2025, [https://www.technewsworld.com/story/pc-pioneer-alan-kay-wins-kyoto-prize-34424.html](https://www.technewsworld.com/story/pc-pioneer-alan-kay-wins-kyoto-prize-34424.html)  
6. Alan Kay \- A.M. Turing Award Laureate, accessed May 26, 2025, [https://amturing.acm.org/award\_winners/kay\_3972189.cfm](https://amturing.acm.org/award_winners/kay_3972189.cfm)  
7. Alan Kay, early visionary of computer science, speaks at ATLAS ..., accessed May 26, 2025, [https://www.colorado.edu/atlas/alan-kay-2019](https://www.colorado.edu/atlas/alan-kay-2019)  
8. Dynabook \- Wikipedia, accessed May 26, 2025, [https://en.wikipedia.org/wiki/Dynabook](https://en.wikipedia.org/wiki/Dynabook)  
9. \[\[personal dynamic media\]\] at anagora.org, accessed May 26, 2025, [https://anagora.org/personal%20dynamic%20media](https://anagora.org/personal%20dynamic%20media)  
10. manovich.net, accessed May 26, 2025, [https://manovich.net/content/04-projects/054-alan-kay-s-universal-media-machine/51\_article\_2006.pdf](https://manovich.net/content/04-projects/054-alan-kay-s-universal-media-machine/51_article_2006.pdf)  
11. How Alan Kay invented the future \- Eric Normand's Newsletter, accessed May 26, 2025, [https://ericnormand.substack.com/p/how-alan-kay-invented-the-future](https://ericnormand.substack.com/p/how-alan-kay-invented-the-future)  
12. Alan Kay – User Interface: A Personal View (1989), accessed May 26, 2025, [https://worrydream.com/refs/Kay\_1989\_-\_User\_Interface,\_a\_Personal\_View.pdf](https://worrydream.com/refs/Kay_1989_-_User_Interface,_a_Personal_View.pdf)  
13. The Early History Of Smalltalk, accessed May 26, 2025, [https://worrydream.com/EarlyHistoryOfSmalltalk/](https://worrydream.com/EarlyHistoryOfSmalltalk/)  
14. Alan Kay: Transforming the Computer Into a Communication Medium \- Engineering and Technology History Wiki, accessed May 26, 2025, [https://ethw.org/w/images/2/23/Barnes.pdf](https://ethw.org/w/images/2/23/Barnes.pdf)  
15. 今更ながらアラン・ケイとDynabook \- テクノロジーとデザインと, accessed May 26, 2025, [https://uxtokyo.net/alankay](https://uxtokyo.net/alankay)  
16. Etoys (programming language) \- Wikipedia, accessed May 26, 2025, [https://en.wikipedia.org/wiki/Etoys\_(programming\_language)](https://en.wikipedia.org/wiki/Etoys_\(programming_language\))  
17. アラン・ケイ氏京都大学名誉博士称号授与記念講演会及び祝賀会 ..., accessed May 26, 2025, [https://www.kyoto-u.ac.jp/ja/archive/prev/news\_data/h/h1/news4/2008/090120\_1](https://www.kyoto-u.ac.jp/ja/archive/prev/news_data/h/h1/news4/2008/090120_1)  
18. en.wikipedia.org, accessed May 26, 2025, [https://en.wikipedia.org/wiki/Dynabook\#:\~:text=The%20KiddiComp%20concept%2C%20envisioned%20by,similar%20functionality%20to%20that%20now](https://en.wikipedia.org/wiki/Dynabook#:~:text=The%20KiddiComp%20concept%2C%20envisioned%20by,similar%20functionality%20to%20that%20now)  
19. Learning with Squeak Etoys \- SciSpace, accessed May 26, 2025, [https://scispace.com/pdf/learning-with-squeak-etoys-1ybrlond1w.pdf](https://scispace.com/pdf/learning-with-squeak-etoys-1ybrlond1w.pdf)  
20. Getting started with Squeak Etoys \- The Daily Papert, accessed May 26, 2025, [https://dailypapert.com/constructionism2010/W\_Freudenberg.pdf](https://dailypapert.com/constructionism2010/W_Freudenberg.pdf)  
21. Alan Kay \- Wikipedia, accessed May 26, 2025, [https://en.wikipedia.org/wiki/Alan\_Kay](https://en.wikipedia.org/wiki/Alan_Kay)  
22. Constructionism (learning theory) \- Wikipedia, accessed May 26, 2025, [https://en.wikipedia.org/wiki/Constructionism\_(learning\_theory)](https://en.wikipedia.org/wiki/Constructionism_\(learning_theory\))  
23. Alan Kay's Squeakland posts, accessed May 26, 2025, [https://worrydream.com/AlanKaySqueaklandPosts/](https://worrydream.com/AlanKaySqueaklandPosts/)  
24. Alan Kay: Software Design, the Future of Programming and the Art of ..., accessed May 26, 2025, [https://library.educause.edu/resources/1999/1/alan-kay-software-design-the-future-of-programming-and-the-art-of-learning](https://library.educause.edu/resources/1999/1/alan-kay-software-design-the-future-of-programming-and-the-art-of-learning)  
25. Model of the Dynabook “dynamic book” (replica by Alan Kay) \- CHM Revolution, accessed May 26, 2025, [https://www.computerhistory.org/revolution/mobile-computing/18/315/1683](https://www.computerhistory.org/revolution/mobile-computing/18/315/1683)  
26. Alan Kay \- “User Interface: A Personal View” 119891 \- daniel g. siegel, accessed May 26, 2025, [https://www.dgsiegel.net/files/refs/Kay%20-%20User%20Interface%3A%20A%20Personal%20View.pdf](https://www.dgsiegel.net/files/refs/Kay%20-%20User%20Interface%3A%20A%20Personal%20View.pdf)  
27. Scratching the Surface With Mitchel Resnick \- Joe Kinsella, accessed May 26, 2025, [https://joekinsella.me/2011/02/scratching-the-surface-with-mitchel-resnick/](https://joekinsella.me/2011/02/scratching-the-surface-with-mitchel-resnick/)  
28. Viewpoints Research Institute, accessed May 26, 2025, [https://vpri.org/](https://vpri.org/)  
29. The Viewpoints Research Institute's STEPS Project, accessed May 26, 2025, [https://computinged.wordpress.com/2011/01/03/the-viewpoints-research-institutes-steps-project/](https://computinged.wordpress.com/2011/01/03/the-viewpoints-research-institutes-steps-project/)  
30. パーソナルコンピュータ「Dynabook」は誰のために作られた？ アラン・ケイが言いたかったこと（阿部和広氏に聞く：前編） | サイボウズ式, accessed May 26, 2025, [https://cybozushiki.cybozu.co.jp/?p=11813](https://cybozushiki.cybozu.co.jp/?p=11813)  
31. What is a Dynabook? An Afterword by Alan Kay | Policy Commons, accessed May 26, 2025, [https://policycommons.net/artifacts/1796423/afterword/2528067/](https://policycommons.net/artifacts/1796423/afterword/2528067/)  
32. Alan Kays Definition Of Object Oriented \- C2 wiki, accessed May 26, 2025, [https://wiki.c2.com/?AlanKaysDefinitionOfObjectOriented](https://wiki.c2.com/?AlanKaysDefinitionOfObjectOriented)  
33. Alan Kay and OO Programming \- Curtis “Ovid” Poe, accessed May 26, 2025, [https://curtispoe.org/articles/alan-kay-and-oo-programming.html](https://curtispoe.org/articles/alan-kay-and-oo-programming.html)  
34. Squeak \- Wikipedia, accessed May 26, 2025, [https://en.wikipedia.org/wiki/Squeak](https://en.wikipedia.org/wiki/Squeak)  
35. www.google.com, accessed May 26, 2025, [https://www.google.com/search?q=Alan+Kay+Turing+Award](https://www.google.com/search?q=Alan+Kay+Turing+Award)  
36. Alan Kay's Vision of OOP \- DEV Community, accessed May 26, 2025, [https://dev.to/muhammad\_salem/alan-kays-vision-of-oop-k5h](https://dev.to/muhammad_salem/alan-kays-vision-of-oop-k5h)  
37. Alan Kay \- Computer Timeline, accessed May 26, 2025, [http://www.computer-timeline.com/timeline/alan-kay/](http://www.computer-timeline.com/timeline/alan-kay/)  
38. Father Ivan and his Children \- Lewis Art Café, accessed May 26, 2025, [https://lewisartcafe.com/father-ivan-and-his-children/](https://lewisartcafe.com/father-ivan-and-his-children/)  
39. Alan Kay's Remarkable Contributions \- Inspired.org, accessed May 26, 2025, [https://www.inspired.org/thoughts/2025/5/16/alan-kays-remarkable-contributions](https://www.inspired.org/thoughts/2025/5/16/alan-kays-remarkable-contributions)  
40. Alan Kay and the predecessor of modern tablets | Hidden Heroes \- Netguru, accessed May 26, 2025, [https://hiddenheroes.netguru.com/alan-kay](https://hiddenheroes.netguru.com/alan-kay)  
41. The 40th Anniversary of the Dynabook \- CHM \- Computer History Museum, accessed May 26, 2025, [https://computerhistory.org/events/40th-anniversary-dynabook/](https://computerhistory.org/events/40th-anniversary-dynabook/)  
42. www.nae.edu, accessed May 26, 2025, [https://www.nae.edu/55013/Dr-Alan-C-Kay-\#:\~:text=One%20of%20the%20earliest%20members,and%20icons%20graphical%20user%20interface.](https://www.nae.edu/55013/Dr-Alan-C-Kay-#:~:text=One%20of%20the%20earliest%20members,and%20icons%20graphical%20user%20interface.)  
43. Smalltalk \- Wikipedia, accessed May 26, 2025, [https://en.wikipedia.org/wiki/Smalltalk](https://en.wikipedia.org/wiki/Smalltalk)  
44. en.wikipedia.org, accessed May 26, 2025, [https://en.wikipedia.org/wiki/Smalltalk\#:\~:text=Smalltalk%20is%20a%20purely%20object,later%20found%20use%20in%20business.](https://en.wikipedia.org/wiki/Smalltalk#:~:text=Smalltalk%20is%20a%20purely%20object,later%20found%20use%20in%20business.)  
45. The Early History of SmallTalk by Alan Kay \- Goodreads, accessed May 26, 2025, [https://www.goodreads.com/book/show/35120577-the-early-history-of-smalltalk](https://www.goodreads.com/book/show/35120577-the-early-history-of-smalltalk)  
46. Java Was Strongly Influenced by Objective-C \- GMU CS Department, accessed May 26, 2025, [https://cs.gmu.edu/\~sean/stuff/java-objc.html](https://cs.gmu.edu/~sean/stuff/java-objc.html)  
47. The Lisa: Apple's Most Influential Failure \- CHM, accessed May 26, 2025, [https://computerhistory.org/blog/the-lisa-apples-most-influential-failure/](https://computerhistory.org/blog/the-lisa-apples-most-influential-failure/)  
48. www.inspired.org, accessed May 26, 2025, [https://www.inspired.org/thoughts/2025/5/16/alan-kays-remarkable-contributions\#:\~:text=Alan%20and%20his%20small%20team,local%20area%20networks%20(Ethernet)%2C](https://www.inspired.org/thoughts/2025/5/16/alan-kays-remarkable-contributions#:~:text=Alan%20and%20his%20small%20team,local%20area%20networks%20\(Ethernet\)%2C)  
49. History of the graphical user interface \- Wikipedia, accessed May 26, 2025, [https://en.wikipedia.org/wiki/History\_of\_the\_graphical\_user\_interface](https://en.wikipedia.org/wiki/History_of_the_graphical_user_interface)  
50. Alan Kay \- Latest Future of Reading Chapter-5 \- Achraf Kassioui, accessed May 26, 2025, [https://www.achrafkassioui.com/library/Alan%20Kay%20-%20The%20Future%20of%20Reading.pdf](https://www.achrafkassioui.com/library/Alan%20Kay%20-%20The%20Future%20of%20Reading.pdf)  
51. What was Alan Kay's motivation for being interested in children, and how do you think this influenced the development of programming languages like SmallTalk? \- Quora, accessed May 26, 2025, [https://www.quora.com/What-was-Alan-Kays-motivation-for-being-interested-in-children-and-how-do-you-think-this-influenced-the-development-of-programming-languages-like-SmallTalk](https://www.quora.com/What-was-Alan-Kays-motivation-for-being-interested-in-children-and-how-do-you-think-this-influenced-the-development-of-programming-languages-like-SmallTalk)  
52. Jean Piaget \--Great Minds, Great Thinkers \- Edinformatics, accessed May 26, 2025, [https://www.edinformatics.com/great\_thinkers/piaget.htm](https://www.edinformatics.com/great_thinkers/piaget.htm)  
53. Jean Piaget \- Crystalinks, accessed May 26, 2025, [https://www.crystalinks.com/piaget.html](https://www.crystalinks.com/piaget.html)  
54. Alan Kay | Biography, Inventions, & Facts \- Britannica, accessed May 26, 2025, [https://www.britannica.com/biography/Alan-Kay](https://www.britannica.com/biography/Alan-Kay)  
55. Douglas Engelbart and Human-Computer Interaction \- Coconote, accessed May 26, 2025, [https://coconote.app/notes/db4ecac7-2019-4f29-a4b5-8eb99c44f53d](https://coconote.app/notes/db4ecac7-2019-4f29-a4b5-8eb99c44f53d)  
56. A Visit With Alan Kay \- Coding Horror, accessed May 26, 2025, [https://blog.codinghorror.com/a-visit-with-alan-kay/](https://blog.codinghorror.com/a-visit-with-alan-kay/)  
57. KEYNOTE 1: Alan Kay \- Rethinking Design, Risk, and Software \- YouTube, accessed May 26, 2025, [https://www.youtube.com/watch?v=QboI\_1WJUlM](https://www.youtube.com/watch?v=QboI_1WJUlM)  
58. Alan Kay interview for The Machine That Changed The World, accessed May 26, 2025, [https://worrydream.com/refs/Kay\_1990\_-\_Interview\_(The\_Machine\_That\_Changed\_The\_World).html](https://worrydream.com/refs/Kay_1990_-_Interview_\(The_Machine_That_Changed_The_World\).html)  
59. Alan Kay's Quora dialogues and the philosophical dilemma of Systems thinking \- General, accessed May 26, 2025, [https://forum.malleable.systems/t/alan-kays-quora-dialogues-and-the-philosophical-dilemma-of-systems-thinking/173](https://forum.malleable.systems/t/alan-kays-quora-dialogues-and-the-philosophical-dilemma-of-systems-thinking/173)  
60. Kay, A. (1990). User interface: A personal view. In B. Laurel (Ed.), The art of human-computer interface design (pp. 191–207)., accessed May 26, 2025, [https://notes.andymatuschak.org/zEGqBPb51ecnLemaxDZbdXm](https://notes.andymatuschak.org/zEGqBPb51ecnLemaxDZbdXm)  
61. en.wikipedia.org, accessed May 26, 2025, [https://en.wikipedia.org/wiki/Computer\_History\_Museum](https://en.wikipedia.org/wiki/Computer_History_Museum)  
62. Alan Kay \- CHM \- Computer History Museum, accessed May 26, 2025, [https://computerhistory.org/profile/alan-kay-2/](https://computerhistory.org/profile/alan-kay-2/)  
63. Dr. Alan Kay wins Honorary Degree from Northwestern Univ. | Kyoto Prize \- 京都賞, accessed May 26, 2025, [https://www.kyotoprize.org/en/news/2019/07/dr-Alan-Kay-wins-Honorary-Degree-from-Northwestern-Univ](https://www.kyotoprize.org/en/news/2019/07/dr-Alan-Kay-wins-Honorary-Degree-from-Northwestern-Univ)  
64. 京都賞 | 京都大学, accessed May 26, 2025, [https://www.kyoto-u.ac.jp/ja/about/history/honor/award-b/kyoto](https://www.kyoto-u.ac.jp/ja/about/history/honor/award-b/kyoto)  
65. Alan Kay 2003 ACM A.M. Turing Award Lecture \- YouTube, accessed May 26, 2025, [https://www.youtube.com/watch?v=ymF94cFfzUQ](https://www.youtube.com/watch?v=ymF94cFfzUQ)  
66. Alan C. Kay \- DBLP, accessed May 26, 2025, [https://dblp.org/pid/k/AlanCKay](https://dblp.org/pid/k/AlanCKay)
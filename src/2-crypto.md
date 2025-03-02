# 密碼！

## 引言
要了解密碼龐克倫理，首先需要理解密碼技術，特別是其數位形式技術和哲學特徵。在當代公共討論中，人們經常將密碼稱為「加密」，但「加密」只是*密碼學*這個更廣泛學科中的一個術語，密碼學是關於製作和破解密碼的科學。密碼學中負責製作密碼的分支叫做*密碼學*（cryptography），由密碼學家（cryptographers）來實踐；而負責破解密碼的分支則稱為*密碼分析*（cryptanalysis），由密碼分析師（cryptanalysts）來實踐。密碼或密碼算法是一種數學函數，允許用戶將明文消息（通常是以英語或西班牙語等自然語言書寫的）轉換為密文消息，即明文消息的亂碼版本，反之亦然。加密或加密處理是將明文轉換為密文的過程，而解密或解密處理則是將密文轉換為明文的過程。密碼學家的工作是設計足夠強大的密碼，讓未經授權的人無法弄清楚如何將密文轉回明文，從而在未經許可的情況下讀取消息。密碼分析師的工作恰恰相反：弄清楚密碼是如何設計的，從而能夠將密文轉回明文並未經授權地閱讀消息，通常甚至不會讓發送者知道。David Kahn（1967）將密碼學的起源追溯到古代文明，但在二十世紀，軍隊宣稱對製作和破解密碼擁有壟斷權。然而今天，幾乎每個人、每天都在使用密碼學工具。雖然大多數人僅模糊地意識到自己每天都在使用「加密」，但密碼龐克圍繞這種古老科學的現代版本構建了他們的倫理和政治世界觀。

在整本書中，我們將使用簡稱「*密碼*」來指代密碼學、加密過程和密碼學密碼本身。

理解密碼龐克倫理與密碼之間的關係，最好的方式是從技術哲學入手，這是一個反思技術本質和技術對社會影響的哲學分支。Carl Mitcham 指出，技術哲學中有兩種主要的傳統：「工程技術哲學」和「人文技術哲學」。Mitcham 寫道，工程技術哲學從「內部」分析技術，將自己定向於「理解技術存在於世界中的方式，作為其他種類思維和行為的範式」。這種哲學方法主要來自工程師和其他技術專家，他們試圖通過自身的技術知識來理論化世界。另一方面，人文技術哲學指的是「宗教、詩歌和哲學將非技術或跨技術的視角應用於解釋技術意義的嘗試」。這一方法主要來自哲學家和社會科學家，他們試圖從以人為本的角度理解技術成就和發明。Mitcham 認為，無論是工程傳統還是人文傳統的技術哲學方法，單獨看都不完整。他主張，任何技術哲學的方法應該結合人文傳統對人類價值的重視與工程傳統對精煉技術知識的欣賞。

作為一個運動，密碼龐克運動很好地展示了 Mitcham 的願景，因為許多密碼龐克既是博學的科學家和工程師，又能將哲學思想與技術專業知識結合在一起。密碼龐克運動的三位公認創始人都是科學家。John Gilmore 是一位計算機程式員，他幫助開發了使設備能夠連接到無線網絡的協議。Tim May 是一位物理學家，他的發現幫助改善了早期微芯片的設計和運行。Eric Hughes 是一位數學家，他研究過密碼學。但 Gilmore、May、Hughes 和許多後來的密碼龐克也不僅僅停留在具體的技術知識上，他們將這些知識放在更廣泛的人類價值框架中來思考。

跟隨密碼龐克的步伐，我們必須綜合技術和哲學知識，構建一個引人入勝的密碼技術哲學。Bruce Schneier 曾著名地觀察到，密碼學既是一門科學，又是一門藝術。密碼學是一門科學，因為它根植於理論數學。但正如 Joshua Holden 所指出的，密碼與其他科學不同，因為「密碼學關於的是智慧的敵手，這些敵手積極地爭奪是否會揭露秘密」。從這個角度來看，密碼可以被視為一門藝術，特別是作為一門交流藝術。在其歷史的大部分時間裡，通訊理論主要關注實現清晰交流的夢想。但密碼學是一門交流藝術，它故意通過打亂消息來干擾清晰度，這樣非預期的接收者就無法理解所傳遞的消息。換句話說，儘管大多數交流藝術幫助人們更清晰地交流，但密碼幫助人們*僅與預期的接收者*進行交流。將密碼視為一門交流藝術，也使我們能夠看到，密碼龐克倫理提供了一種將技術專業與人類價值結合的技術哲學。正如 John Durham Peters 所觀察到的，通訊理論「與倫理學、政治哲學和社會理論是同源的」，因為它關心的是「自我與他者、自我與自我，以及社會組織中的親近與距離」。從這個意義上說，密碼既是一門數學科學，也是一種藝術實踐，能夠促成特定類型的人際關係。

根據 David Kahn、Bruce Schneier、Simon Singh、Joshua Holden 和 Keith Martin 的研究，下文的前兩個部分提供了基本的密碼學概念和方法的技術概覽。第一部分通過檢視幾種簡單的替換密碼，介紹了密碼學的基本術語、數學和歷史。第二部分探討了公開密鑰密碼學的創建及其所依賴的數學運算。在前兩部分建立了我們的密碼龐克密碼哲學的工程側面後，第三部分則介紹了這一技術哲學的人文側面。運用 Ivan Illich 的《*共生工具*》中的哲學術語來分析密碼龐克對密碼的論點，我們可以得出結論：密碼龐克視密碼為 Illich 所說的共生工具。在構建密碼龐克的技術哲學時，我們能夠理解為何密碼龐克會說密碼是「數學真理和道德必要性的完美結合」。

## 密碼學簡介

密碼學的討論通常以描述通信背景及其參與者開始：Alice（A人）、Bob（B人）和Eve（竊聽者）。Alice 和 Bob 想要互相通信，但希望 Eve 無法聽到他們的對話或閱讀他們的書信。在這種情況下，假設 Alice 和 Bob 正在發送手寫信件，而 Eve 試圖攔截這些信件，打開信封並閱讀其內容。在這種情況下，Alice 和 Bob 需要選擇一個密碼並創建一個*加密密鑰*。密碼是生成密鑰的數學算法，而密鑰是 Alice 和 Bob 用來加密通信的具體字母或數字模式。一旦 Alice 和 Bob 選擇了密碼並創建了加密密鑰，他們需要做兩件事。首先，他們必須記住，擁有密鑰的任何人都可以解密他們的信件。雖然他們選擇的密碼算法可以且通常是公開的，但只有 Alice 和 Bob 知道他們選擇了哪個密鑰。Eve 應該被阻止獲得該密鑰的副本。第二，由於密鑰需要保密，Alice 和 Bob 需要找到某種方式來共享密鑰，避免 Eve 獲得副本。如果 Eve 攔截了密鑰，而 Alice 和 Bob 繼續使用該加密密鑰寫信，那麼 Eve 就能夠解密並閱讀他們所寫的所有內容。Alice 不能生成一個加密密鑰並將其郵寄給 Bob，因為 Eve 可能會攔截並複製該密鑰；同樣，Alice 也不能通過電話告訴 Bob 密鑰，因為 Eve 可能會竊聽他們的電話並記下密鑰。因此，Alice 和 Bob 必須找到密碼學家所謂的*安全信道*來共享密鑰。他們可以選擇讓一位信任的朋友送去密封的信封，但這仍然依賴於信任第三方。交換密鑰的最安全方法是 Alice 和 Bob 親自見面。一旦他們安全地交換了密鑰，Alice 就可以使用這個密鑰來加密她的信件，並將加密的信件郵寄給 Bob，Bob 再用相同的密鑰來解密消息並閱讀 Alice 所寫的內容。直到 Eve 拿到 Alice 和 Bob 的密鑰之前，她可以攔截她想要的所有信件，但她無法閱讀其中的內容。

Alice 和 Bob 可以選擇任何密碼系統，但假設他們選擇了最古老且最常見的密碼之一：*簡單的替換密碼*。在大多數情況下，簡單的替換密碼正如其名所示：一種密碼算法，其中字母表中的字母被逐一替換為字母表中的另一個字母。這類密碼中最早且最著名的之一就是凱薩密碼（Caesar Cipher），以羅馬皇帝凱薩（Julius Caesar）命名。凱薩需要與他的將軍們秘密通信，他知道敵人有時會俘虜信使。因此，他使用了一種被稱為「*移位密碼*」的簡單替換密碼來加密通信。如果敵軍士兵攔截了凱薩的信使，他們將無法理解凱薩所寫的內容。為了使用英語創建凱薩密碼，我們需要將每個明文字母分配給相應的密文字母（見表 2.1）。凱薩經常將字母表中的每個字母向右位移三個位置，字母表的最後幾個字母會繞回到前幾個字母。如果皇帝想告訴他的將軍們「黎明時攻擊（attack at dawn）」，那麼 A 就會被替換為 D，T 被替換為 W，C 被替換為 F，依此類推，直到我們得到消息 DWWDFN DW GDZQ。為了隱藏單詞的長度，凱薩可能會將消息分成四個字母一組：DWWD FNDW GDZQ。這樣，凱薩密碼為 Alice 和 Bob 提供了一種簡便的方法來加密他們的通信。

| Alphabet | A | B | C | D | E | F | G | H | I | J | K | L | M |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Key | D | E | F | G | H | I | J | K | L | M | N | O | P |
| Alphabet | N | O | P | Q | R | S | T | U | V | W | X | Y | Z |
| Key | Q | R | S | T | U | V | W | X | Y | Z | A | B | C |

雖然可能並不顯而易見，凱薩的移位密碼實際上可以用數學算法來表示。在這個密碼中，我們有明文字母（M）、密文字母（C）和密鑰（k）。首先，我們必須構建方程式，即明文字母加密鑰等於密文字母，或 M + k = C。第二，我們需要為每個字母分配一個數字：A 變成 1，B 變成 2，C 變成 3……一直到 Z 變成 26。第三，我們必須確定密鑰：因為凱薩通過將字母向右移動三個位置來創建他的密鑰，所以 k 是 3。因此，對於字母表中的任何字母，M + 3 = C。但仍然有一個問題需要解決。假設凱薩想要確認他之前的命令「黎明時攻擊」並用簡單的指令「是」來表達。他需要加密字母 Y，它的數字是 25。為了加密，他將進行以下運算：25 + 3 = 28。但密鑰中沒有 28，因為英文字母只有 26 個字母。所以，我們需要在方程中加入一個*取餘數*的數字。取餘數本質上是一個環繞數字；它告訴我們何時回到開頭。就像時鐘上的指針或音樂符號中的重複小節線一樣，取餘數告訴我們何時回到 1。所以，當凱薩加密 Y 時，他進行這樣的計算：25 + 3 = 28 取餘數 26，由於 26 之後要回到 1，「27」變成 1，28 變成 2，依此類推。在這種情況下，2 是 B，整個消息「是」經過加密後就變成了 BHV（見表 2.2）。

| Plaintext | M+k= C modulo 26 | Ciphertext |
| :--- | :--- | :--- |
| Y | 25+3=28 modulo 26 | B |
| E | 5+3=8 modulo 26 | H |
| S | 19+3=22 modulo 26 | V |

凱薩密碼可能足夠巧妙，能夠欺騙大多數 2000 年前的敵人，但不幸的是，對 Alice 和 Bob 來說，數世紀的研究揭示了這種密碼容易受到*穷举密鑰搜索*（也稱為*暴力破解攻擊*）的攻擊。這種特殊的密碼有 26 個密鑰空間，意味著它只有 26 個可能的密鑰。第一個密鑰不會很好，因為它與普通字母表相同：A 代替 A，B 代替 B，依此類推。對於其他密鑰，字母會移動兩個位置、三個位置（凱薩最喜歡的）四個位置，依此類推，直到 26 個位置。第 27 次位移後，字母表和密鑰將再次匹配——第一個密鑰。如果 Eve 發現 Alice 和 Bob 使用的是一個簡單的替換密碼，將字母表向右移動某個位置，那麼她就知道密鑰空間是 26。因此，她可以嘗試猜測每一個可能的密鑰，直到她得到一條有意義的消息。在密碼學術語中，密鑰空間越小（即可能的密鑰數量越少），執行成功暴力破解攻擊（猜測所有可能的密鑰直到找到正確的）就越容易。

然而，Alice 和 Bob 仍然可以使用簡單替換密碼。不同於將字母向右移動某個位置，他們的密碼可以依賴於字母表的*隨機排列*。對於這種簡單的替換密碼，字母將被隨機打亂，然後與常規字母表進行配對（見表 2.3）。這樣的密碼與凱薩密碼類似，因為每個明文字母都會被分配一個密文字母。使用這個密鑰，凱薩的明文消息「黎明時攻擊」將變成密文消息 QDDQPN QD RQSV。然而，這種排列密碼比字母移位提供了更大的密鑰空間，因此對暴力破解攻擊更具安全性。要找到移位版本密碼的密鑰空間，我們只需計算所有可能的移位，即英文字母表的 26 次。要找到隨機排列版本密碼的密鑰空間，我們必須計算 26 的階乘，即 26 × 25 × 24 × ……  × 2 × 1。數學上，這個階乘用 26! 表示。為了讓 Eve 成功破解這個密碼，她不僅要嘗試 26 個密鑰，而是要嘗試 403,291,461,126,605,635,584,000,000 個密鑰——超過 403 七十萬億個可能的密鑰。即便是現代的計算能力，Eve 也會非常難以成功執行暴力破解攻擊。如果 Eve 的電腦每秒能處理 1 億條指令，那麼她的電腦大約需要 1270 億年才能猜測所有可能的密鑰。即使 Eve 的電腦在猜測了僅 20% 的密鑰後就猜中了正確的密鑰，她也需要 250 億年。

| Alphabet | A | B | C | D | E | F | G | H | I | J | K | L | M |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Key | Q | E | P | R | W | O | X | B | K | J | N | Y | A |
| Alphabet | N | O | P | Q | R | S | T | U | V | W | X | Y | Z |
| Key | V | H | G | L | C | F | D | I | T | S | U | Z | M |

雖然使用隨機排列使得加密在防範暴力破解攻擊方面更加安全，Eve 仍然有一些方法可以用來解密 Alice 和 Bob 的信件。例如，如果 Eve 知道 Alice 和 Bob 正在使用英語進行通信，那麼她可以利用*字母頻率攻擊*來找出加密密鑰。正如任何經驗豐富的 Scrabble 玩家所知道的那樣，英語中並不是所有字母的使用頻率相同。像 E 和 T 這樣的字母大約出現 10% 到 12% 的時間，而像 K 和 V 這樣的字母大約只有 1% 的出現頻率。一旦 Eve 收集了足夠的 Alice 和 Bob 的信件，她就可以看到每個密文字母出現的頻率。那些大約 10% 時間出現的字母更可能是 T 而不是 V。一旦 Eve 破解了足夠的字母，她就可以像《*財富之輪*》比賽者一樣解開這個謎題，並使用獲得的密鑰來閱讀 Alice 和 Bob 之間的所有未來信件。同樣，如果 Eve 得到了兩封相同字母的信件，一封是明文，另一封是密文，她可以通過*已知明文攻擊*來反向工程加密密鑰。這些方法使 Eve 有機會在不需要等待 1270 億年來猜測每一個排列的情況下找出密鑰。

雖然還有許多更多的密碼學方法和密碼分析攻擊需要討論，我們對 Alice 和 Bob 使用簡單替換密碼防止 Eve 閱讀信件的探討，為理解密碼學的基本數學和技術原則奠定了基礎。如我們所見，密碼學在當兩個或更多人（像 Alice 和 Bob）希望在不讓竊聽者（像 Eve）窺探他們通信內容的情況下進行通信時，最為重要。儘管 Eve 可能知道 Alice 和 Bob 正在交換信件，但密碼可以防止她知道他們在說*什麼*。然而，隨著 Eve 發展出更為複雜的密碼分析攻擊，Alice 和 Bob 也必須逐步提高他們的通信安全性。一旦他們意識到 Eve 可以輕鬆地通過暴力破解攻擊破解凱薩的位移密碼，他們決定使用隨機排列來生成一個新的密碼學密鑰。雖然這種密碼學方法要強得多，但 Eve 還是有可能通過字母頻率分析或已知明文攻擊來找出 Alice 和 Bob 的密鑰。

在本節開始時，我們提到 Alice 和 Bob 需要記住兩件事：首先，他們的加密密鑰必須保密；其次，他們必須通過某個安全的信道來共享密鑰。到目前為止，我們的討論主要集中在第一個問題上。假設 Alice 和 Bob 可以親自見面來共享加密密鑰，那麼我們可以說他們已經通過安全信道共享了密鑰。然而，在 19 世紀中期電報的發明引入了一個新問題，電報是第一個電子通信媒介。正如 James Carey 所觀察到的，電報「第一次實現了通信和運輸的有效分離」。在電報出現之前，信件只能以人類的速度傳遞——步行、騎馬、坐馬車、坐船。但是電報將運輸和通信分開，讓通信得以瞬間傳遞。儘管今天我們常常忽視電報，但 Carey 提醒我們，我們仍然生活在一個電報時代。「通信和運輸的分離，」Carey 寫道，「在隨後的通信發展中被廣泛應用，直到計算機控制系統」。在電報以後的世界中，Alice 和 Bob 無法在利用快速通信手段的*同時*保持隱私，因為他們仍然需要親自見面來共享加密密鑰。因此，從電報到互聯網的電子通信引入了一個新的問題：是否有可能在不見面的情況下共享加密密鑰？

## 公鑰密碼革命

「今天，我們站在密碼學革命的邊緣，」Whitfield Diffie 和 Martin Hellman 在 1976 年寫道。在超過 2000 年的歷史中，所有的密碼學都屬於*對稱密鑰加密*，這意味著加密信息的發送者和解密信息的接收者使用完全相同的密鑰。當凱薩向他的將軍發送命令時，他們使用相同的密鑰；當 Alice 向 Bob 寫信時，他們也使用相同的密鑰。密碼學中只能使用一個密鑰的觀念如此根深蒂固，以至於大多數人認為沒有其他方法是可能的。因此，當 Diffie 和 Hellman 在他們的 1976 年論文《密碼學新方向》中介紹了*非對稱密鑰密碼學*時，他們的確革新了密碼學。非對稱密鑰密碼學更常被稱為*公鑰密碼學*，因為與前面討論的簡單替換密碼不同，這種類型的密碼系統允許用戶公開分發加密密鑰。與凱薩和 Alice 及 Bob 必須將加密密鑰保密以防竊聽者不同，Diffie 和 Hellman 證明了設計一個具有兩個密鑰的密碼系統是可能的——一個公開的加密密鑰和一個私密的解密密鑰。雖然公鑰加密直到 Ron Rivest 等人（1978）提供了使其運作的數學方法才得以完全發展，Diffie 和 Hellman 以他們的公鑰密碼系統真正革新了密碼學。

像對稱密鑰密碼系統一樣，我們必須理解公鑰密碼的概念和數學基礎，才能充分理解它對倫理和社會價值的相關性。理解公鑰密碼革命的一個方法是區分*密鑰強度問題*和*密鑰分發問題*。正如簡單替換密碼的討論所揭示的，密鑰強度問題至少可以通過使加密密鑰更加數學複雜，從而增加密鑰空間。但是，大密鑰空間並不能解決密鑰分發問題，因為如果無法安全地共享加密密鑰，加密提供的安全性就微乎其微。雖然 Carey 可能是對的，即電報將通信與運輸分開，但我們必須注意，電報*並未*將加密密鑰分發與運輸分開。雖然電報可以讓 Alice 和 Bob 放棄手寫信件，轉而發送電報，但他們仍然無法通過電報共享加密密鑰。如果他們這麼做，則他們的秘密密鑰將會被其他人（包括 Eve）獲得，從而輕易地解密他們的消息。因此，電報使得密鑰分發問題更加複雜。電報使通信瞬間完成，但私人通信仍然需要加密密鑰，並且加密密鑰的安全性仍然依賴於物理運輸。為了讓 Alice 和 Bob 能夠利用電子通信革命，他們仍然需要*至少見一次面*來安全地共享他們的密鑰。

在電報發明近 140 年後，Diffie 和 Hellman（1976）觀察到了數字時代的開始，這是一場基於計算機的通信技術革命。如果電報使密鑰分發問題更加複雜，Diffie 和 Hellman 得出結論，計算機網絡將使這一問題更加嚴峻。他們寫道：「計算機控制的通信網絡的發展，承諾了世界各地的人或計算機之間輕鬆且低廉的聯繫，取代了大多數郵件和許多旅行，並以電信形式進行」。不幸的是，輕鬆、低廉的通信承諾被密鑰分發問題所阻礙。當然，Alice 和 Bob 可以立即並持續地相互通信——或與世界各地任何擁有計算機和調製解調器的人通信，但如果他們希望進行私人通信，他們仍然需要某種方式來安全地共享加密密鑰。Diffie 和 Hellman 明白，數字時代對私人通信提出了可能的困境。考慮到當時密碼學的狀況，通信可以是容易的，也可以是私密的，但不能兩者兼得。

為了解決數字時代的密鑰分發問題，Diffie 和 Hellman（1976）構思了一個密碼系統，該系統生成兩個密鑰。一個*公鑰*用來加密消息，一個*私鑰*用來解密消息。舉例來說，Alice 可以將她的公鑰自由地發布在在線目錄中，然後 Bob——或任何其他想要與 Alice 通信的人——可以查找她的公鑰並用它來加密消息。一旦 Alice 收到來自 Bob 或其他人的加密消息，她就可以使用她的私鑰來解密這些消息，並閱讀其中的內容，而她的私鑰無論如何也無法與他人共享。「公鑰」這個術語有點誤導，因為公鑰加密密鑰更像是鎖而不是鑰匙。當 Alice 在目錄中共享她的公鑰時，就像她提供了鎖一樣。Bob 可以使用這把鎖來加密他發送給 Alice 的消息，一旦消息被鎖住，只有 Alice——甚至連 Bob 自己也不行——才能解鎖。只要 Alice 始終保持她的私鑰保密，她就是唯一能解密那些使用她的公鑰加密（鎖住）的消息的人。

要使公鑰加密系統安全，Diffie 和 Hellman得出結論，必須使用「計算安全」的方式來設計，這涉及到一種*單向陷門函數*。正如 Diffie 和 Hellman 解釋的那樣，計算安全的密碼系統是指*可以*被密碼分析解決，但這需要極高的時間和資源成本。換句話說，一個公鑰算法必須能夠被解決，因為接收者必須能夠使用他們的私鑰來解密消息，但這個算法對於沒有私鑰的人來說必須極其難以解決。Diffie 和 Hellman 主張，公鑰加密應該建立在單向函數的基礎上，這是一種易於執行但幾乎不可能逆轉的數學運算。實際上，Alice 的公鑰將是一個方程式，具體來說，是一個單向函數，Bob 將使用這個方程來鎖定他發送給 Alice 的消息。由於幾乎不可能逆轉構成 Alice 公鑰的單向函數，因此 Eve 使用密碼分析方法來破解加密將變得非常困難（但並非不可能）。然而，Alice *可以*輕鬆解密消息，因為她擁有「陷門」，這是一個秘密信息，允許她逆轉單向函數。正如 Diffie 和 Hellman 所說：「陷門密碼是指強烈抵抗任何沒有擁有設計密碼的陷門信息的人進行的密碼分析」。因此，單向陷門函數使得預定的接收者可以解密和閱讀消息，同時防止像 Eve 這樣的未經授權接收者成功地進行密碼分析攻擊。

儘管 Diffie 和 Hellman 提出了幾種數學方法來創建強大的公鑰密碼系統，其中一些方法至今仍在使用，但正是 Ron Rivest、Adi Shamir 和 Leonard Adleman（1978）擴展了 Diffie 和 Hellman 的研究，並開發了大多數現代公鑰密碼的數學基礎。這種密碼算法，我們可以稱之為 RSA，來自於其創始人 Rivest、Shamir 和 Adleman。RSA 算法類似於構成凱薩位移密碼的算法。因此，我們有明文字母（M）、密文字母（C）和模數（N）。與凱薩密碼不同，RSA 密碼使用指數 e 來使方程更加複雜，從而增加計算的難度。凱薩密碼的方程是明文字母加密鑰等於密文模 26，或者 M + k = C 模 26，但 RSA 密碼的方程是明文字母的指數 e 模 N 等於密文，或者 M^e mod N = C。使用這個方程，Alice 為 e 和 N 選擇數值並將其作為公鑰分享。當 Bob 準備向 Alice 發送消息時，他會將明文消息的指數提升為 Alice 選擇的 e，並使用 Alice 選擇的 N 來進行模運算，從而生成密文。

假設 Bob 向 Alice 發送了加密的消息，但 Eve 也攔截了密文的副本。在這種情況下，我們可以理解為什麼 Alice 可以解密消息，而 Eve 不能。當 Bob 加密消息時，他知道 e 和 N（Alice 的公鑰）以及 M（他的消息）的數值。Alice 的加密密鑰是公開的，所以我們可以假設像 Bob 一樣，Eve 也知道 Alice 的 e 和 N。然而，知道 Alice 的 e 和 N 並不幫助 Eve 解密消息，因為 Alice 的私鑰不是 e 和 N，而是 d 和 N。換句話說，構成 Alice 解密密鑰的方程式是密文消息的 d 次方模 N 等於明文消息，或者 C^d mod N = M。Eve 知道 N，但她不知道 d。另一方面，Alice 知道 d 並將其保密，因為它包含了允許她計算方程並獲得明文消息 M 數值的秘密陷門信息。只有 Alice 能夠確定 M，因為只有她擁有這個陷門的密鑰。

雖然 RSA 密碼有幾個複雜的數學特性使其得以運作，但最重要的一個特性是*質因數分解*的難度。質數是一種只能被 1 和它自己整除的數字。例如，4 不是質數，因為它是 4 × 1 和 2 × 2 的積，而 5 是質數，因為它是 1 × 5 並且沒有其他組合。分解是找出哪些數字組合可以相乘得到某個數字的過程。回到我們的例子，1、2 和 4 都是 4 的因數，因為我們可以用 4 × 1 或 2 × 2 得到 4。但是 5 只有 1 和 5 兩個因數。質因數分解是通過分解一個數字來確定它的因數中哪些是質數的過程。取 77 為例：當我們分解 77 時，我們會得到 1 × 77 或 7 × 11。雖然 77 不是質數，但 7 和 11 是。質因數分解是一個單向函數：將兩個質數相乘得到積相對容易，但要將積反向分解得到質數則非常困難。這一過程在數字變大時會變得越來越困難。例如，如果我們選擇兩個 300 位數的質數並將它們相乘得到 X（大約是 600 位數字），計算機可以在瞬間完成這一運算。但如果我們把這個積 X 給計算機，讓它找出我們相乘得到 X 的兩個 300 位數的質數，計算機就會發現這個過程非常困難。

考慮到質因數分解非常大的數字的難度，Rivest 等人（1978）將大質數融入他們的公鑰密碼系統中。為了創建公鑰，RSA 算法 M^e mod N = C 需要一個 N 的數值。要生成 N 的數值，該算法包括一個隨機數生成器（RNG），該生成器隨機生成兩個非常大的質數。這些質數被稱為 p 和 q，並且它們相乘得到一個模數：p × q = N。請注意，Alice 共享 N 作為她的公鑰的一部分，這是安全的，因為 N 非常大，現有的計算機無法將 N 分解來確定 p 和 q。即使 Eve 知道 N，她也無法計算出 p 和 q。此外，p 和 q 還會進行相乘（以及其他運算）來創建 d，這是 Alice 的私密解密密鑰的另一部分。至此，所有的一切都變得清晰：Alice、Bob 和 Eve 都知道加密方程式 M^e mod N = C 和解密方程式 C^d mod N = M。Alice、Bob 和 Eve 也都知道 Alice 為 e 和 N 選擇的數字，這是她的公鑰。因此，他們三個都可以使用加密方程來加密消息。然而，只有 Alice 可以解密消息，因為只有 Alice 知道 d 的數值。任何想要確定 d 的人都必須知道質數 p 和 q，但由於 Alice 不共享 p 和 q，所以 d 對任何其他人來說都難以計算。而且，儘管 N 是通過將 p 和 q 相乘來創建的，但正如 Diffie 和 Hellman 所說，「計算上是不可行的」。Eve 的計算機需要 1270 億年來猜測我們隨機排列的簡單替換密碼的每一個密鑰，而它幾乎需要同樣長的時間來將 N 分解並發現 p 和 q。

雖然公鑰密碼涉及其他技術和數學細節，但我們可以理解 Diffie 和 Hellman（1976）以及 Rivest 等人（1978）研究中的革命性發現。數百年來，密碼學家一直在努力提高他們密碼的強度，而密碼分析師則在努力破解這些密碼。這個過程導致了密碼的強度不斷增強，但密鑰分發問題仍然存在。在電報發明之後，通信可以在從未見過面的人之間瞬間發送，而且在許多情況下，這些人永遠不會親自見面。然而，私人、安全的加密通信仍然依賴於物理運輸，因為密鑰無法通過電報網絡安全地共享。正如 Diffie 和 Hellman 在近 50 年前指出的，現代計算機網絡將繼承電報問題：通信可以是容易的，也可以是私密的，但不能兩者兼得。因此，他們創建了第一個公鑰密碼系統，解決了電子通信時代的密鑰分發問題，使得通信既可以容易又可以私密。一旦 Rivest、Shamir 和 Adleman 證明質因數分解可以用來保護非對稱密碼算法免受簡單的密碼分析攻擊，數位時代隱私和安全的基本構建塊就此誕生。

## 數字密碼作為一種共生工具

根據密碼龐克的範例和 Mitcham 的建議，我們的密碼技術哲學必須綜合工程學和人文關注。前兩個部分滿足了我們對密碼學的哲學理解中的工程部分，而本節則介紹了人文部分，這將是本書其餘部分的重點。雖然 Tim May 的密碼無政府主義哲學和 Julian Assange 的密碼正義哲學將在其他章節中詳細探討，但本節基於 Ivan Illich 的工作，突出密碼龐克在密碼學中發現的倫理和社會價值。Illich（2009）提出了“共生工具”這一概念，這些工具是讓人類在其當地環境中繁榮和創造的技術。*共生*一詞來自拉丁語中的 con-（“與”）和 vivere（“生活”），這暗示著共生工具是幫助我們彼此共處、共生的工具。對 Illich 來說，*vivere* 在共生中的含義不僅僅是生存、生還；它意味著作為自由的、相互依賴的個體共同繁榮。正如 Illich 明確指出的，“共生社會將是社會安排的結果，這些安排為每個成員保證最充分和自由地訪問社區的工具，並且只有在有利於另一成員平等自由的情況下才會限制這種自由” 。使用 Illich 的術語，我們可以說密碼龐克將密碼視為一種共生工具，並且如果強密碼廣泛可用且易於使用，社會就會更加共生。

像許多技術哲學家一樣，Illich（2009）使用“工具”這個詞的範疇遠超過我們日常理解中的含義，他不僅根據工具的功能來分類工具，還根據它們促進的社會價值和權力關係來分類。對於 Illich 來說，工具包括簡單的手工工具（鉛筆、錘子）、複雜的機器（汽車、飛機）、生產性機構（工廠、電廠）、通信網絡（手機塔、光纖電纜），甚至是整個社會機構（公立學校、醫療設施）。

在 Illich 的觀點中，這些工具可以根據其技術性質和促進的權力關係一般理解為操控性工具或共生工具。操控性工具是“本質上限制只有極少數人能夠以自主方式使用的工具”。從這個角度來看，Illich 會說，任何通過其設計將控制權集中於少數人手中的手工工具、機器、網絡或機構，都是操控性的。對於 Illich 來說，公立教育就是一個典型的操控性工具。儘管公立學校是為了提高識字率和使知識獲取民主化而創建的，但他認為它們反而提供了中央集權的政府（以及日益增多的企業）當局，讓他們有權定義教育的目的和目標，並將這些定義強加於全體公眾。類似地，社交媒體平台就是當代操控性工具的例子。儘管像 Facebook 和 Twitter 這樣的公司吸引用戶參與和建立聯繫，但這些平台主要是為了創造收入。正如 Shoshana Zuboff（2019）在她對監視資本主義的分析中有力地指出的那樣，社交媒體對用戶來說*看似*是中立平台，但實際上它們的設計目的是讓用戶保持活躍並生成更多的點擊——尤其是廣告。社交媒體因此可以被理解為操控性工具，不僅因為它們旨在實際上操控用戶點擊廣告，還因為它們由少數沒有民主問責的企業精英控制和運營。

與操控性工具不同，共生工具公平地分配權力，並使個體能夠定義他們自己的創意目的。共生工具抵抗集中化，這使得工具變得操控性。“共生工具排除了某些程度的權力、強制和編程，”Illich解釋道，“這正是使所有政府看起來或多或少相似的特徵”。對 Illich 來說，電話是典型的共生工具。電話允許任何人對任何他們打電話的人說任何他們想說的話，並以任何他們為自己設定的目標來服務。雖然竊聽者可以偷聽電話（特別是如果通話未加密），但電話公司並不會秘密地決定電話用戶的目的。類似地，點對點（P2P）網絡就是當代共生工具的例子。最常見的 P2P 網絡是文件共享平台，如 Napster 和 BitTorrent。P2P 網絡由至少兩個節點（但通常更多）組成，這些節點都由個別用戶運營，並且彼此之間都有連接。因為 P2P 網絡沒有集中式的伺服器來讓所有“客戶端”（用戶）進行通信，所以 P2P 網絡在技術和權力上都是分散的。由於社交媒體上的所有通信必須經過公司的伺服器，而不是從一個用戶的設備直接到另一個用戶的設備，它們就不像 BitTorrent 那樣是“點對點”網絡，而是“點對 Facebook 再到點”。因此，P2P 網絡是共生的，因為每個加入網絡的人都可以對該網絡的結構和目的有一定的發言權，這些決定可以在沒有集中控制權限的情況下做出。

從密碼龐克倫理的角度來看，密碼是典型的共生工具。Illich 提供了明確的標準來判斷一個工具是否是共生工具。正如他解釋的那樣：

> 工具促進共生的程度取決於它們是否可以被任何人輕鬆使用，無論是想使用多長時間還是多久使用一次，用於實現用戶選擇的目的。某個人使用這些工具不會限制另一個人同等使用它們。它們不需要用戶的先前認證。它們的存在不會強加任何使用它們的義務。它們允許用戶在行動中表達自己的意思。

密碼無疑符合這些標準，特別是在其數字和公鑰版本中。沒有義務使用密碼，但密碼軟件的進步使得即使是最非技術性的人也能輕鬆使用。每個人都可以選擇何時使用密碼；每個人都可以決定自己使用密碼的原因。當一個人使用密碼時，他們不會阻止另一個人平等使用密碼。人們不需要從集中式機構獲得許可或授權來使用密碼。最後，當某人使用密碼來保護他們的通信時，他們在行動中表達了自己的意思——即使竊聽者無法讀取密文消息的內容，密碼的使用本身就傳遞了一個想法：*這條消息是私密的*。

為了消除任何對密碼龐克認為密碼在 Illich 意義上是共生的疑問，我們必須轉向 Eric Hughes 所寫的《密碼龐克宣言》，這是該運動的基礎性文本。Hughes（2001）認為隱私的本質與現代電信系統的結構之間存在矛盾。正如 Hughes 定義的那樣，隱私是“選擇性地向世界揭示自己的力量”。然而，現代通信系統在設備相互連接時會自動揭示用戶的身份。從 Illich 的角度來看，這樣的通信系統本身不是共生的，因為它們阻止了個別用戶決定何時以及如何共享或揭示他們的個人身份和個人數據。正如 Hughes 所寫的，“當我的身份被交易的底層機制揭示時，我就沒有隱私。我無法在這裡選擇性地揭示自己；我必須始終揭示自己”。然而，作為密碼龐克，Hughes 最後得出結論：密碼是共生的，因為它使個體能夠捍衛他們的隱私，從而恢復個體選擇性地向世界揭示自己的力量。此外，Hughes 解釋說，密碼龐克不僅創建密碼學軟件，還使這些軟件“免費使用，全球共享”。對於密碼龐克來說，共享密碼軟件並不是終點；相反，這樣的共享會促使創建一個更共生的社會。Hughes 明確表示，“人們必須共同部署這些[密碼]系統，為了共同的利益”，因為“隱私的範圍僅取決於社會中每個人的合作”。如果現代電信系統受到政府和企業的集中控制，它們就會變得越來越操控性。因此，密碼提供了一種去中心化通信控制的技術手段，並將社會推向更共生的方向。

## 結論

本章通過將密碼解釋為一種共生工具來建立密碼龐克的技術哲學。根據 Mitcham 的論點，這種密碼龐克技術哲學同時具有工程學側面和人文學側面。工程學側面要求我們至少對密碼學有基本的技術理解，我們通過研究簡單的替換密碼和公鑰密碼系統來建立這一理解。當然，還有許多其他密碼學方法，但了解密碼學算法是如何通過加法、指數運算、模數數字、階乘、排列、統計和像質因數分解這樣的陷門單向函數的各種組合來構建（和破解），我們可以更好地理解這門科學的技術基礎。更重要的是，理解密碼如何工作使我們能夠更好地理解和欣賞它所促進的倫理價值。這種密碼龐克技術哲學的人文側面要求我們確定密碼所促進的價值，而 Illich 的共生工具概念提供了一種理解密碼龐克視角的有用方式。20世紀的大部分時間，密碼學主要只對那些擁有創建和使用複雜數學系統知識和資源的學者和將軍可用。但隨著計算機技術的發展和 Diffie 和 Hellman 公開密鑰密碼系統的發表，密碼已經實現了普及化。在數字形式中，加密通過賦予個體更大的控制權來促進共生，使人們能夠控制他們何時、如何以及與誰通信。然而，將密碼視為共生工具的討論只是理解密碼龐克倫理的第一步。接下來的兩章將通過探討 Tim May 和 Julian Assange 的倫理和政治哲學來擴展密碼龐克技術哲學的人文側面，而其餘章節將通過探索這些不同密碼龐克倫理觀念的實踐意涵來擴展我們對密碼的技術理解。

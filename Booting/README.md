# Linux 核心開機流程

這個章節將介紹 linux 核心的開機流程，您將會在這裡看到一些文章介紹核心載入流程的完整週期：

* [從開機程式到核心](http://0xax.gitbooks.io/linux-insides/content/Booting/linux-bootstrap-1.html) - 描述從電腦開機到執行第一行核心指令碼的所有階段；
* [核心初始化碼的第一步](http://0xax.gitbooks.io/linux-insides/content/Booting/linux-bootstrap-2.html) - 描述核心初始化碼。 您將會看到堆積(heap)初始化, 不同參數如： EDD, IST等的查詢。
* [影像模式初始化及轉換至保護模式](http://0xax.gitbooks.io/linux-insides/content/Booting/linux-bootstrap-3.html) - 描述核心初始化碼中的影像模式初始化以及保護模式轉換。
* [轉換至64位元模式](http://0xax.gitbooks.io/linux-insides/content/Booting/linux-bootstrap-4.html) - 描述轉換至64位元的準備過程以及轉換的細節。
* [解壓縮核心](http://0xax.gitbooks.io/linux-insides/content/Booting/linux-bootstrap-5.html) - 描述核心解壓縮前的準備以及直接解壓縮的細節。

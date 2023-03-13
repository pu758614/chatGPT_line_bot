## 介紹
基於openai所提供GPT3.5模型，結合LINE BOT成為一個可以在LINE上實現如chatGPT一樣連續對話功能，
因為連續對話需要一個儲存的空間，在此使用google sheet來做為資料儲存的空間。

因openai api並非無限免費使用，所以使得開發者開發出來的LINE平台難以以免費的形式分享給人體驗使用，
因為可能瞬間免費的額度就被使用完了，所以這裡透過google sheet表單儲存方式，建立可多人註冊各自的帳號並且以簡單指令的方式設定自己的openai api key，讓使用者
可以使用自己的openai api key來使用LINE版本的chatGPT。
# Darwin Juan的幣別DB功能維護簡介如下：
![index](https://github.com/darwin0616/DarwinCoindesk/raw/main/index.png)
點擊bpi中的功能按鈕後，可分別進入美金、英鎊、歐元的維護頁面。
以下點擊進入歐元頁面。
![index](https://github.com/darwin0616/DarwinCoindesk/raw/main/eur.png)
點擊json源碼最右端的儲存按鈕會把當下的歐元與比特幣的匯率存入h2 DB。
該儲存按鈕的實作方式是透過restful api處理，因此亦可透過postman的方式直接存入。

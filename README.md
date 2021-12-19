# Darwin Juan的幣別DB功能維護簡介如下：
![index](https://github.com/darwin0616/DarwinCoindesk/raw/main/index.png)
點擊bpi中的功能按鈕後，可分別進入美金、英鎊、歐元的維護頁面。
以下點擊進入歐元頁面。
![index](https://github.com/darwin0616/DarwinCoindesk/raw/main/euro.png)
點擊json源碼最右端的儲存按鈕會把當下的歐元與比特幣的匯率存入h2 DB。
該儲存按鈕的實作方式是透過restful api處理，因此亦可透過postman的方式直接存入。
![index](https://github.com/darwin0616/DarwinCoindesk/raw/main/postman.png)
點擊下方的查詢，會透過restful api自h2 DB中帶出code=EUR的所有資料，使用者可對每筆資料修改/刪除。
h2 DB的範例資訊如下:
![index](https://github.com/darwin0616/DarwinCoindesk/raw/main/h2.png)
上述的功能雖然是依據國泰世華的面試題目所設計，但是實作的程式碼屬於我個人的著作權。
# 『本人聲明不願意在Github上公開程式碼。』
待遠端面試時可以展示其運作結果。
![index](https://github.com/darwin0616/DarwinCoindesk/raw/main/intellij-springboot.png)

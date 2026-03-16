1. 到https://cloud.llamaindex.ai/ 利用免費額度將pdf(在付費牆之後的文獻pdf檔)或docx轉成.md檔
2. 到llamaindex.ai的history看轉檔進度, 逐一打開下載
3. 解說下載按鈕
4. 打開Claude Desktop App, 點選Cowork, 選擇Work in folder(有剛剛下載的references的markdown檔案的資料夾, 還有草稿.docx)
5. 輸入Prompt: You are the best scientific journal editor and orthopedic surgeon to help me polish my manuscripts, aimed for the journal "......" and associated publications. The "20260312.docx" is my manuscript.

- please turn my manuscript into main.md first
- I want to add references in folder "paper.md" to the manuscript. Try to find associated paragraph to support the arguments in my manuscript. You could provide editorial comments paragraph by paragraph
- separate references into .bib, use appropriate citation format.
- output in .md first. don't go into .docx directly.

6. 進行過程, 右邊會列出AI認為資料夾相關的檔案, 或經由AI新產生的檔案
7. 可以點選任何檔案, 如果是.md可以直接在右欄顯示內容, 如果針對想要修改的部分, 可以複製貼到左下角prompt欄, 針對該部分進行修改(如: 這段請縮減50%, 或加入某某文獻)
8. 再針對AI給的Editorial Comments給予回應
9. 再針對AI給的Editorial Comments給予回應
10. 這裡請AI將每個版本另存一份, 方便後續追溯比較
11. 同前頁
12. 加入更多.md格式的文獻, 並請AI將這些文獻加入到manuscript中
13. 再存成另一個版本, 完稿看過沒問題, 請AI轉成.docx格式, 就可以到資料夾拿成果了

如果不指定輸出markdown檔, claude常常會直接產生docx, xlsx, pptx等檔案, 過程緩慢又消耗Tokens(很快就會用完額度, 要等5小時才能再使用), 所以一定要等最後輸出再轉docx.

以上作業涵蓋20篇pdf文獻 + 1篇docx原稿, 耗時30分鐘, 消耗相當於claude pro subscription 5小時的額度, 或每週10%的額度, 以每月20美元計算, 成本約20/4.5/10 = 0.44美元

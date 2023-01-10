# 109503003 陳柏禎 通訊三
# Two Coding Way Comparison
# Arithmetic Coding
1. 進入coding_compare檔案夾之下   
2. 輸入指令：cd arcd-master/examples  
3. 編譯程式碼：gcc arcd_stream.c adaptive_model.c arcd.c -o testarc  
4. 執行壓縮/解壓縮指令：./testarc -e <paper.txt|tee complete  
   解壓縮指令 ./testarc -e <complete|tee paper.txt  
# Huffman Coding
1. 進入coding_compare檔案夾之下    
2. 輸入指令：cd huffman-main  
3. 編譯程式碼：gcc huffcode.c huffman.c -o testhuff  
4. 執行壓縮/解壓縮指令： ./testhuff -i paper.txt -o complete  -c  
   解壓縮指令: ./testhuff -i complete -o paper.txt  -d

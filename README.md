【Virique唯伊】
一個AI虛擬陪伴的軟體
主打最貼近真實的陪伴，不僅可以讓使用者自行創建角色，還提供聊天室、視訊、回憶小舖等多種互動式功能，用來療育日常生活繁忙缺乏社交的每個人
---------------------------------------------------------------------------------

〔系統技術〕
前端：react native
後端：flask
資料庫：SQLite
API：stable diuffsion、edge-tts、retrieval-based voice conversion、openAI、 yolov8、mediapipe、expression editor、ditto talking head

*本檔案不包含大型模型，系統中的模型請至hugging face網頁下載https://huggingface.co/Ann0v0/Virique-Model/tree/main

檔案名稱              存放路徑(專案跟目錄算起) 
------------------------------------------------------------------------------
Coups 10e 60s.pth    backend/assets/Voice/Models/Coups/
˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙
f0D__k & f0G__k      backend/external/Applio/rvc/models/pretraineds/hifi-gan/
˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙
fcpe.pt & rmvpe.pt   backend/external/Applio/rvc/models/predictors/
˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙˙
pytorch_model.bin    backend/external/Applio/rvc/models/embedders/contentvec/
                     backend/contentvec/
                     backend/rvc/models/embedders/contentvec/

安裝步驟：
1. git clone
2. pip install -r requirements.txt
3. 環境變數設定：請準備自己的 OpenAI Key 和 Google Cloud JSON
4. 至hugging face連結https://huggingface.co/Ann0v0/Virique-Model/tree/main下載模型

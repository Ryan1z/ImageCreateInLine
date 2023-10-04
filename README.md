# ImageCreateInLine

SP:建議在Ubuntu或Liunx環境下執行
1.建立.env檔，主要存放OpenAI API KEY。
2.以下兩列為必填，需先申請Line Developers帳號並註冊Message APIs
CHANNEL_SECRET = ""
CHANNEL_ACCESS_TOKEN = ""
3.Ngrok 需持續監聽5000 port
4.使用下列可安裝所需用到的所有套件
``
pip install -r requirements.txt
``
PS:若環境變數無法取得請修改 ~/.bashrc 新增下行並加入token
``
export OPENAI_API_KEY=""
``

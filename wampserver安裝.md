##軟體下載
http://192.168.152.134/

電腦作業系統是64位元的選擇Wampserver2.4-x64.exe

32位元選擇Wampserver2.4-x86.exe

##安裝步驟
1.安裝過程全部都按下一步即可

2.安裝完後，於電腦桌面右下方點擊wampserver icon，將php.ini設定裡的php_curl.dll權限打開，接著再點擊Restart All Services重啟所有服務

示意圖(http://192.168.152.134/wampserver.jpg)

3.試寫測試程式，curl 'http://192.168.152.134/transfer/presenter.php/test?username=phili' ，確認有收到 '{"result":false,"data":{"Code":"4444","Message":"API is not open"}}' 此訊息，若無收到請反映。

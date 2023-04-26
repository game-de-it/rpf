# retroid pocket flip
retroid pocket flipのsleep mode trickを5秒で実行するためのスクリプト。  
通常はスリープモードを15分間維持しなくてはいけませんが、このスクリプトによって5秒に短縮できます。  
Script for retroid pocket flip's sleep mode trick in 5 seconds.  
Normally I have to stay in sleep mode for 15 minutes, but this script cuts it down to 5 seconds.  



## 使い方
1. RPFでset_device_idle_constants.shとunset_device_idle_constants.shをダウンロードしてください   
2. 設定→ハンドヘルドの設定→アドバンスト→Rootとしてスクリプトを実行する　を選択し、先ほどダウンロードしたset_device_idle_constants.shを指定して実行します  
3. 電源ケーブルを接続してバイブレーションが終わったら電源ケーブルを抜きます  
4. RPFの電源ボタンを軽く押してスリープモードに入り、5秒数えたら再度電源ボタンを押してスリープモードから復帰すれば完了です  
  
**Androidを再起動した後は3.と4.の手順を実行してください。**  
**設定を元に戻したい場合はunset_device_idle_constants.shをRootとしてスクリプトを実行してください。**
---  
## Usage
1. Download set_device_idle_constants.sh and unset_device_idle_constants.sh in RPF  
2. Select Settings→Handheld Settings→Advanced→Execute Script as Root, specify the set_device_idle_constants.sh you just downloaded and execute it  
3. Connect the power cable and unplug the power cable after the vibration finishes.  
4. Press the power button on the RPF lightly to enter sleep mode, and after a count of 5 seconds, press the power button again to return from sleep mode, and you are done.  
  
**After rebooting Android, follow steps 3 and 4.**  
**If you want to restore the settings, run the script unset_device_idle_constants.sh as Root.**
---  

# Ansible x SmartCS x ALAXALA Workshop

![ansibleXsmartcsXalaxala.png](ansibleXsmartcsXalaxala.png)


## 本ドキュメントについて

本ドキュメントは、Ansibleハンズオンセミナー  
Ansible × SmartCS × ALAXALAネットワークス  
で使用するコンテンツとなります。  

本ワークショップのトレーニングは以下を目的としています。  
- ネットワーク運用におけるAnsibleの使い方
- コンソールサーバ SmartCSの使い方
- ALAXALAネットワーク製品をAnsibleで制御する方法
- Ansible、SmartCS、ALAXALAネットワークス製品を連携させたネットワーク運用の自動化


## ハンズオン環境

### 構成図
![handson_environment.png](handson_environment.png)

### SWバージョン
- Ansible :  2.8.5
- SmartCS modules for Ansible :  Version 1.1
- AX modules for Ansible :  Version 1.4


## ハンズオン内容

### Section.1 - 演習に向けて

 - [[**演習1.1** 演習環境の確認]](1.1-preparing_for_the_exercise.md)

### Section.2 - SmartCS基礎(without Ansible)演習

 - [[**演習2.1** SmartCSの基本動作]](2.1-basic_operation_of_smartcs.md)

### Section.3 - Ansible × SmartCS × ALAXALA の連携演習基礎

 - [[**演習3.1** ALAXALA装置にSmartCS経由で初期設定を行う]](3.1-Initial_setup_the_ALAXALA_device_via_SmartCS.md)
 - [[**演習3.2** ALAXALA装置にSmartCS経由で追加設定を行う]](3.2-Additional_setup_the_ALAXALA_device_via_SmartCS.md)
 - [[**演習3.3** ALAXALA装置の設定情報を取得する]](3.3-Get_ALAXALA_device_information.md)
 - [[**演習3.4** ALAXALA装置の設定情報をSmartCS経由で取得する1]](3.4-Setting_of_ALAXALA_device_via_SmartCS_1.md)
 - [[**演習3.5** ALAXALA装置の設定情報をSmartCS経由で取得する2]](3.5-Setting_of_ALAXALA_device_via_SmartCS_2.md)

### Section.4 - Ansible × SmartCS × ALAXALA の連携演習応用(ユースケース)

 - [[**演習4.1** オペミスからの復旧自動化]](4.1-Automation_of_operation_error_recovery.md)
 - [[**演習4.2** 通信障害からの復旧自動化]](4.2-Automation_of_recovery_from_network_communication_failures.md)
 - [[**演習4.3** ファームウェアアップデートの自動化]](4.3-Autommation_of_firmware_update.md)
 - [[**演習4.4** ファームウェアアップデートの自動化]](4.4-Automation_of_initialization.md)

### Section.5 - Ansible Tower との連携演習

 - 案1.演習4.2の応用編 監視→情報取得→復旧自動化をTower経由で  
 - 案2.演習4.3をTower経由で行う  

### Section.6 - 最後に

## 参考情報







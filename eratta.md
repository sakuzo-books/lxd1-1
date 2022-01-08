# 正誤情報

* 第2版  
  正誤情報はありません。
  
* 初版
  * ~~P14 : 4.仮想マシンのネットワーク設定を変更します。~~ → 第2版に反映 
    * 誤
    ```
    ＜設定変更前>
    root@ubuntu:~#
    root@ubuntu:~# vi 00-installer-config.yaml
    network:
      ethernets:
    ```

    * 正
    ```
    ＜設定変更前>
    root@ubuntu:~#
    root@ubuntu:~# vi /etc/netplan/00-installer-config.yaml
    network:
      ethernets:
    ```
  
  * ~~P15 : 4.仮想マシンのネットワーク設定を変更します。~~ → 第2版に反映
    * 誤
    ```
    ＜設定変更後＞
    root@ubuntu:~#
    root@ubuntu:~# vi 00-installer-config.yaml
    network:
      ethernets:
    ```

    * 正
    ```
    ＜設定変更後＞
    root@ubuntu:~#
    root@ubuntu:~# vi /etc/netplan/00-installer-config.yaml
    network:
      ethernets:
    ```

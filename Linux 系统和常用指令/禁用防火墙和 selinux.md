__防火墙的操作__
- 关闭防火墙
    ```
    systemctl stop firewalld
    ```
- 禁止防火墙开机自启
    ```
    systemctl disable firewalld.service
    ```

__selinux__
- 查看 selinux 状态
    ```
    getenforce
    ```
- 暂时禁用
    ```
    setenforce 0
    ```
- 关闭 selinux
    ```
    vi /etc/selinux/config
    ```
# 基本工作
在完成辅助igb-driver框架的linkup后，我对igb基本初始化流程和寄存器有了基本的认识。借助ixgbe-driver的代码，我对主要要使用到的寄存器在igb上进行适配，并修改了一些代码以支持igb的启动。之后通过在cargo.toml文件中添加git外部库的方式使用我修改后的代码。
我在arceos/下添加了run.sh文件，通过在根目录下执行下列命令即可运行实例httpclient程序
```
sh run.sh
```
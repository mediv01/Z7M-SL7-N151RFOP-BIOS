# Z7M-SL7-N151RFOP-BIOS
Hasee Z7M-SL7（N151RFOP）BIOS
神舟Z7M-SL7（蓝天N151RFOP） BIOS超频及降压教程（附修改器以及BIOS文件）
声明：刷BIOS以及修改BIOS具有一定的风险，请谨慎刷机。

步骤1：提取原厂BIOS，我这里使用的是BIOS_Backup_TooKit.EXE
 
点击读取，等读取完成后再点击备份，保存BIOS文件为AmericanMegatrendsInc.-1.05.08ROP4.rom

步骤2：用BIOS修改器AMIBCP64修改提取出来的原厂BIOS，并另存为UNSIGN.ROM
 

步骤3：将UNSIGN.ROM拷贝入SIGN_BIOS这个文件夹，用管理员模式运行make_sign_capsule.bat，然后程序会自动生成蓝天签名，生成的文件为BIOSSIGNROM文件夹内的SIGW9XLU.ROM。
 
步骤4：将SIGW9XLU.ROM重命名为机型名称，如Z7M-SL7就命名为N151RFOP.ROM，拷贝入FAT格式的U盘里，然后关闭计算机。

步骤5：计算机在关闭的状态下按住FN+B键不放，然后按电源键，等待10秒左右BIOS系统会进入RECOVERY模式，选择刷入BIOS，重启后BIOS就更新了，可以在高级选项中超频和降压了。

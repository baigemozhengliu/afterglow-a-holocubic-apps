# Afterglow 余辉 1.0.0



<img width="128" height="128" alt="main" src="https://github.com/user-attachments/assets/9da01d57-6450-4628-abba-9b52d2877512" />



适用于 HoloCubic 320×240 屏幕的复古仪表时钟，提供 IBM 3270 等宽时间码、日期与实时麦克风波形。
具备三种色彩模式，通过倾斜切换
<img width="320" height="240" alt="screenshot-el" src="https://github.com/user-attachments/assets/82c404e2-ba4a-4db8-ac7a-c38d939676b7" />
<img width="320" height="240" alt="screenshot-vfd" src="https://github.com/user-attachments/assets/e87a6898-1c45-44ce-9269-cabf19584004" />
<img width="320" height="240" alt="screenshot-crt" src="https://github.com/user-attachments/assets/5322dd0f-3012-4da7-9eed-efb5135b3db3" />


## 安装

下载 [afterglow-1.0.0.zip](afterglow-1.0.0.zip)，解压后将 `afterglow` 文件夹复制到 SD 卡的 `apps` 目录。确认入口路径为 `/sd/apps/afterglow/main.lua`，重新扫描应用或重启设备，在启动器中打开 Afterglow。

或将 package/ 内所有文件复制到 /sd/apps/afterglow/。

## 使用

- 左右倾斜设备切换 EL 琥珀、VFD 青蓝、CRT 绿色主题，需要 IMU 支持。
- 短按 HOME 返回启动器。
- 麦克风波形支持自动显示增益压缩；缺少麦克风接口时显示内部示意波形。
- `COMP` 和右下角 dB 表示显示增益压缩状态，不是声压测量值；波形区量程文字为装饰，时间码末尾两位为视觉时间细分。


使用IBM 3270 字体![Uploading screenshot-el.png…]()

应用不发起网络请求，不录制或保存音频。应用采用 MIT 许可；随包保留应用及字体许可证。


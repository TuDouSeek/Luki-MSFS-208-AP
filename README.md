# 爱折腾的Luki 外设教程

---

### **材料**

3D打印件，开源地址：

| 名称       | 数量 | 尺寸        |
| ---------- | ---- | ----------- |
| nano开发板 | 1    |             |
| 自锁按钮   | 10   | （5.8*5.8） |
| 非自锁按钮 | 10   | （5.8*5.8） |
| 线束       | 若干 |             |
| ec11编码器 | 4    | 15mm梅花轴  |
| 自攻螺丝   | 10   | （M3*12）   |
| 自攻螺丝   | 4    | （M1.2*4）  |

### **接线图**

| 元件       | 开发板接口 |
| ---------- | ---------- |
| BUT_HDG    | D2         |
| BUT_APR    | D3         |
| BUT_DC     | D4         |
| BUT_NAV    | D5         |
| BUT_FD     | D6         |
| BUT_RANK   | D7         |
| BUT_XFR    | D8         |
| BUT_AP     | D9         |
| BUT_YD     | D10        |
| BUT_ALT    | D11        |
| BUT_VB     | D12        |
| BUT_VNY    | D13        |
| BUT_FLC    | RX         |
| BUT_SPD    | TX         |
| EC11_HDG   | A1         |
| EC11_CRS1  | A2         |
| EC11_SEL   | A3         |
| EC11_DN-UP | A4         |
| EC11_CRS2  | A5         |

 <img src="/img/image.png" width="400">



当前接线图只是推荐，具体可以根据自己的实际情况进行修改。 

---

### **固件导入**

软件我们使用**MobiFlight**开源地址：https://github.com/MobiFlight/MobiFlight-Connector

下载地址：[https://www.mobiflight.com/en/download/thank-you.html](https://www.mobiflight.com/en/download/thank-you.html)

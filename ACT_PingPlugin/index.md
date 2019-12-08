# ACT_PingPlugin

## Ping Overlays

### 标准布局

- [ping.html](ping.html)

### 单行布局

- [ping_oneline.html](ping_oneline.html)

对于单行布局，我们建议使用以下avg变量以仅显示一条信息。  
例如: `https://ShadyWhite.github.io/ACT_PingPlugin/ping_oneline.html?avg=30`

## 关于avg变量

- 如果在URL后面添加`?avg=30`，将显示30项的平均时间。
- 如果在URL后面添加`?avg=5,10,30`，将显示5项，10项和30项的平均时间。
- 如果不添加任何内容，则假定指定了`?avg=5,30,60`。

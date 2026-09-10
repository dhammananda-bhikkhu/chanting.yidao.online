# 如何烤钵——给钵烤出近似钢琴漆的效果

<div class="mermaid">
graph TD
A("物料与设备")
click A "./pattakala_tool.html" _blank
B("预处理")
click B "./pattakala_pre.html" _blank
C("上漆前准备")
click C "./pattakala_pre_paint.html" _blank
D("上漆")
click D "./pattakala_paint.html" _blank
E("上漆后清理")
click E "./pattakala_after_paint.html" _blank
F("烘烤")
click F "./pattakala_bake.html" _blank
G("打磨")
click G "./pattakala_polish.html" _blank
H("补漆")
click H "./pattakala_fixing.html" _blank
I("抛光")
click I "./pattakala_polish_A.html" _blank
J1{"检查<br>漆膜<br>穿孔"}
J2{"判定烤钵<br>次数和颜色"}
A-->B-->C
C-->D
D-->F-->G
G-->J2
J2--"次数未满5次<br>颜色不够深"-->D
J2--"次数满5次<br>颜色够深"-->J1
J1--"无"-->I
J1--"有"-->H-->F
I-->E
</div>



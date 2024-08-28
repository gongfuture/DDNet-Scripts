# 旁观缩放

## 说明
参考了 [Index](../../Zoom_out_&_spectating/ScrollWheel_Zooms_in_spec_{by_Index}/) 和 [Deen](../../Zoom_out_&_spectating/Zoom_out_on_spec_{By_Deen}) 两位大佬的设计

尝试将两个`cfg`脚本合并成一个,个人习惯`Q`使用`/pause`指令，`P`使用`/spec`指令

按下`Q`/`P`时，执行`/pause`/`/spec`，并且缩小五次、此时可以使用鼠标滚轮进行缩放。
再次按下`Q`/`P`时，执行`/pause`/`/spec`，恢复默认缩放，并且滚轮恢复切换武器功能。
有时`Q`/`P`触发过快导致缩放/武器状态错误，可以使用`W`切换缩放/武器状态

## 使用方法

如何使用：`exec Zoom_off.cfg`

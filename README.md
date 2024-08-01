# pyJianYingDraft
### 轻量化、易用的Python剪映脚本文件生成工具
> **关于6+版本**：尽管剪映对`draft_content.json`文件进行了加密，但仍能读取本程序生成的脚本文件

# 特性清单
> 目前仅在5.9版本上进行测试
> 标注☑️的特性**已实现**，标注⬜的特性**待实现**，标注❔的特性**优先级较低**

### 视频/图片
- ☑️ 添加本地视频/图片素材
- ❔ 添加**剪映提供的**视频/图片素材
- 将视频/图片素材添加至轨道
  - ☑️ 自定义放置在轨道上的**时间、持续时长或播放速度**
  - ☑️ 自定义**截取**其中某个片段
  - ☑️ 视频**整体调节**（裁剪、旋转、翻转、缩放、透明度、亮度等）
  - ☑️ 除裁剪外上述属性的**关键帧**生成
  - ☑️ 视频片段的**入场/出场/组合动画**（剪映右上角菜单）添加及其时长修改
  - ☑️ 吸附在视频片段上的**特效**
    - ☑️ 特效的参数设置
    - ❔ 特效参数的关键帧
  - ⬜ 吸附在视频片段上的**滤镜**
    - ⬜ 滤镜参数设置
    - ❔ 滤镜参数的关键帧
### 音频
- ☑️ 添加本地音频素材
- ❔ 添加**剪映提供的**音频素材
- 将音频素材添加至轨道
  - ☑️ 自定义放置在轨道上的**时间、持续时长或播放速度**
  - ☑️ 自定义**截取**其中某个片段
  - ☑️ 调整**音量、淡入淡出**时长
  - ☑️ 音量的**关键帧**生成
  - ☑️ 音频片段的**音色、场景音**效果（剪映右上角菜单）添加
    - ☑️ 效果的参数设置
    - ❔ 效果参数的关键帧
  - ❔ 自动触发**声音成曲**效果的文件生成
### 轨道
- ☑️ 添加轨道
- ☑️ 将片段添加到指定轨道
  - 附带片段重叠检查
### 特效类
- ⬜ 位于独立轨道的特效
- ⬜ 位于独立轨道的滤镜
- ☑️ 添加转场
  - ☑️ 转场时长设置
### 文字
- ❔ 添加文字
- ❔ 文字特效

# 视觉风格参考

仅在任务使用老吴角色、3D 怪兽、统一纸张背景或 AI 标题时读取本文件。

## 老吴角色锁定

以 `../assets/laowu-character-reference.png` 为身份参考，生成提示必须明确：

- youthful cute Q-version Lao Wu, oversized round head and small body
- perfectly bald, absolutely no side hair
- round black glasses
- white MUJI-style narrow stand-collar shirt
- top button visibly fastened at the throat
- no bow tie, no necktie, no folded collar, no lapels
- not elderly, not photorealistic

当动作或表情变化时，以上身份特征仍不可变化。

## 3D 卡通材质

以 `../assets/3d-monster-material-reference.png` 为材质参考。重点是：

- 明显的雕塑体积和圆润结构
- 皮肤颗粒、毛孔、细小凹凸和柔和次表面散射
- 眼睛湿润高光、牙齿珐琅质、角与爪的硬质感
- 布料织纹、皮质拳套或道具的真实高光
- 柔和接触阴影、轮廓光和景深

避免平面水彩角色、赛璐璐阴影、纸片感和只靠粗描边制造层次。

## 纸张与构图

以 `../assets/paper-watercolor-layout-reference.png` 为背景气质参考：暖白纸张、轻微旧纸纹理、水彩向白底自然消散、克制米色边框。参考图是竖版示例，新图必须服从用户选择的比例。

以 `../assets/selected-cover-no-text-reference.png` 为成熟构图参考：主体大、动作关系一眼可懂、前后层次清楚、缩小后仍能识别表情与关键道具。

业务背景必须与主题对应。具体选择规则见 [background-selection.md](background-selection.md)。不要用无意义的烟雾或观众席替代能解释主题的平台后台、产品页或实体场景。

## AI 标题

以 `../assets/ai-title-treatment-reference.png` 为默认质量参考，不复制其具体文字。当前偏好的方向是漫画重拳标题：红蓝阵营分色，重点词使用亮金色并放大，重点词背后允许克制的红色爆裂冲击形。标题应由 AI 根据主题设计：

- 文字逐字准确
- 字形不是默认系统字体效果
- 配色与画面阵营或品牌形成逻辑
- 有克制的立体材质、边缘高光和投影
- 重点词可以放大并成为冲击中心；除非用户要求，不使用冠军腰带、月桂或黑色铭牌
- 不遮挡人物眼睛和关键动作

如果 AI 文字拼写错误，保持底图不变，仅重新生成标题区域，直到准确。

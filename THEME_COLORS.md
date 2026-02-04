# 金色主题色列表 (Gold/Sand Theme Colors)

本文档列出了页面中使用的所有金色/沙金色相关的主题色。

## 金色系基础颜色

| 变量名 | 颜色值 | 说明 | 用途 |
|--------|--------|------|------|
| `--primary-color` | `#e8c99b` | 浅沙金色 (Light sand gold) | 主要强调色、链接颜色、按钮hover状态 |
| `--primary-hover` | `#d4a574` | 中等沙金色 (Medium sand gold) | 链接hover、按钮hover背景 |
| `--primary-dark` | `#b8864a` | 深沙金色 (Dark sand gold) | 渐变终点、边框深色 |
| `--accent-color` | `#d4a574` | 强调色（与primary-hover相同） | 强调元素 |

## 金色系边框颜色

| 变量名 | 颜色值 | 说明 | 用途 |
|--------|--------|------|------|
| `--border-sand` | `#e8c99b` | 沙金色边框（与primary-color相同） | 沙色边框 |
| `--border-sand-dark` | `#b8864a` | 深沙金色边框（与primary-dark相同） | 深沙色边框 |

## 金色系渐变

| 变量名 | 渐变定义 | 说明 | 用途 |
|--------|----------|------|------|
| `--gradient-primary` | `linear-gradient(135deg, #e8c99b 0%, #b8864a 100%)` | 主要渐变（浅沙金→深沙金） | 标题渐变文字、卡片背景 |
| `--gradient-primary-light` | `linear-gradient(135deg, rgba(232, 201, 155, 0.1) 0%, rgba(184, 134, 74, 0.1) 100%)` | 浅色主要渐变（10%透明度） | 浅色背景渐变 |
| `--gradient-primary-medium` | `linear-gradient(135deg, rgba(232, 201, 155, 0.2) 0%, rgba(184, 134, 74, 0.2) 100%)` | 中等主要渐变（20%透明度） | 中等背景渐变 |
| `--gradient-box-light` | `linear-gradient(135deg, #f5f7fa 0%, #e8d5b7 100%)` | 浅色盒子渐变（浅灰→浅沙） | 浅色卡片背景 |

## 金色颜色值详情

### 主要金色
- **浅沙金色**: `#e8c99b` (RGB: 232, 201, 155)
- **中等沙金色**: `#d4a574` (RGB: 212, 165, 116)
- **深沙金色**: `#b8864a` (RGB: 184, 134, 74)

### 渐变中包含的金色
- `rgba(232, 201, 155, 0.1)` - 浅沙金色10%透明度
- `rgba(232, 201, 155, 0.2)` - 浅沙金色20%透明度
- `rgba(184, 134, 74, 0.1)` - 深沙金色10%透明度
- `rgba(184, 134, 74, 0.2)` - 深沙金色20%透明度
- `#e8d5b7` - 浅沙色（渐变中使用）

## 金色使用场景总结

1. **链接颜色**: `--primary-color` (#e8c99b)
2. **链接hover**: `--primary-hover` (#d4a574)
3. **按钮hover背景**: `--primary-color` (#e8c99b)
4. **图标hover**: `--primary-color` (#e8c99b)
5. **分页器**: `--primary-color` (#e8c99b)
6. **滚动到顶部按钮**: `--primary-color` (#e8c99b)
7. **标题渐变文字**: `--gradient-primary` (浅沙金→深沙金)
8. **卡片背景**: `--gradient-primary` (浅沙金→深沙金)
9. **边框强调**: `--border-sand` (#e8c99b)

所有金色相关颜色定义位于 `static/css/index.css` 文件的 `:root` 选择器中。

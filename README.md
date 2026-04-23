# lunar-lander-sim
Code with Google Gemini 3

# Lunar Lander Simulator

基於物理動力學模擬的登月遊戲。

## 技術架構 (Technical Stack)
- **物理模型**: 基於齊奧爾科夫斯基火箭方程式與動態質量 ($m(t)$) 積分。
- **技術棧**: HTML5 Canvas, Vanilla JavaScript, Tailwind CSS。
- **渲染機制**: 歐拉積分法 (Euler Integration) 與程序化地形生成。

## 控制說明
- **[↑]**: 主引擎推力 (線性類比)
- **[←/→]**: 姿態調整 (RCS)
- **[R]**: 重置模擬

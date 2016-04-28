# Fourier series -> 频域中离散
1. 为了组合成特殊的曲线: 正弦波按照频率,从低到高排列起来,每个波的振幅都是不同的,有些频率的正弦波时不需要的.
2. 不同频率的正弦波称为频率分量,构成构建频域的基本单元,称作基.
3. 时域的基本单元是"1 秒",频率的基本单元是角频率w_0.
4. 0频率称为直流分量,影响全部波形相对数轴整体向上或向下移动,不改变波的形状.
5. 时间轴上的曲线是规律的正弦波在时域上的投影.
6. 很多在时域看似不可能做到的数学操作，在频域相反很容易。尤其是从某条曲线中去除一些特定的频率成分，这在工程上称为滤波，是信号处理最重要的概念之一，只有在频域才能轻松的做到。
7. 从侧面看的频谱, 代表每一个对应频率的正弦波的振幅.
8. 相位谱是同一个时间点下,离该点最近的正弦波的波峰的时间差,除以2*pi则为在一个周期中的相位差.相位谱的值域取值为(-pi,pi]

# Fourier Transform -> 频域中连续
1. 从求和符号变成了积分符号
2. 乘以虚数i:从实数轴逆时针旋转90度到虚数轴.
3. 欧拉公式描绘随时间变化,在复平面上做圆周运动的点,形成螺旋线,一个轴是时间轴.
4. 螺旋线的叠加在实数空间(由实数轴和时间轴组成)的投影是正弦波的叠加.
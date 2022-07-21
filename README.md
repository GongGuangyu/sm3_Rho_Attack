# 简介
其中ConstParameters.py存储sm3常量 main.py实现sm3以及Rho攻击
# sm3_Rho_Attack
首先是成环的过程，这里的f函数用的并不复杂为2*x+1
# 实验结果
最多可以尝试到前20bit的碰撞，从24bit计算过程过大，猜测瓶颈在于判断sm3（a）是否在列表中，改进方法或许可以用散列表
# 8bit时
![T0AE4S~5(CK1D V~{~~U({A](https://user-images.githubusercontent.com/105531474/179993963-8d4d4d13-2f07-4b8f-8a4b-a424a6a83b1f.png)
# 16bit时
![9DCCW`@T(EZBOF`3DWRXTCA](https://user-images.githubusercontent.com/105531474/179993989-b0357e66-663f-4a77-829b-13990c0b5c7b.png)
# 20bit时
![0$5NAGUG OS~V(0ON @GH H](https://user-images.githubusercontent.com/105531474/179994015-b32906ef-0937-41a2-b1b8-9fc5cd07f152.png)

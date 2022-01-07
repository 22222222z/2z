# 2z
## h2
#### h4
[link to 22z](./22z.md)
****
[a link to apple.com](https://www.apple.com/)
****
## local image
![image](./2.jpg)
****
## web image 
![image](https://gss0.baidu.com/-vo3dSag_xI4khGko9WTAnF6hhy/zhidao/pic/item/63d0f703918fa0ec0d994ef72d9759ee3c6ddbe9.jpg)
****
```cpp
    using namespace std;
    for(int i = 0;i < 100 ;i ++)
    cout<<i<<endl;
```
```py
    import torch
    import numpy as np
    import matplotlib.pyplot as plt

    x_data = [1.0, 2.0, 3.0]
    y_data = [2.0, 4.0, 6.0]

    def forward(x):
        return x * w

    def loss(x, y):
        y_pred = forward(x);
        return (y_pred - y) * (y_pred - y)

    w_list = []
    mse_list = []

    for w in np.arange(0.0, 4.1, 0.1):
        print('w = ',w)
        l_sum = 0
        for x_val,y_val in zip(x_data, y_data):
            y_pred_val = forward(x_val)
            loss_val = loss(x_val, y_val)
            l_sum += loss_val
            print('\t',x_val, y_val, y_pred_val, loss_val)
        print('MSE = ',l_sum / 3)
        w_list.append(w)
        mse_list.append(l_sum / 3)

        #绘图
        plt.plot(w_list, mse_list)
        plt.ylabel('Loss')
        plt.xlabel('w')
        plt.show()
```
****
> a block quote
****
1. 123
2. 456
3. 789
4. 987
- first
- second
- third
****
| head1 | head2 | head3
| :-----:|:-----:|:-----:|
| content1 | content2 | content3 |
| content | content | content |
****
**bold text**
****
*italicized text*
****
***cu xie ti***
****
~~delete~~
****

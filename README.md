# AISpringButton
实现弹簧效果按钮
使用方法
<p>cocoapod</p>
    pod 'AISpringButton'
</p>
```
    AISpringButton *btn = [[AISpringButton alloc]initWithFrame:CGRectMake(0, 0, 100, 182)];
    btn.center = self.view.center;
    //标题的方向
    btn.titleDirection = TitleDirection_bottom;
    [btn setTitle:@"我是标题"];
    [btn setNormalImageName:@"deng" andSelectedImageName:@"deng"];
    [btn addTarget:self action:@selector(onClickBtn:) forControlEvents:(UIControlEventTouchUpInside)];
    [self.view addSubview:btn];
```
![image](https://github.com/aizexin/AISpringButton/blob/master/弹簧按钮.gif)
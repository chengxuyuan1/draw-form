# draw-form
UIView *v1 = [[UIView alloc] initWithFrame:(CGRect){1, 50, WZBWidth - 2, 80}];<br>
    [self.view addSubview:v1];<br>
    // 在v1上画一个4列3行的表格<br>
    /**
     * 创建一个表格<br>
     * line：列数<br>
     * columns：行数<br>
     * data：数据<br>
     */
    [v1 wzb_drawListWithRect:v1.bounds line:4 columns:3 datas:@[@"", @"语文", @"数学", @"英语", @"王晓明", @"100.5", @"128", @"95", @"李小华", @"100.5", @"128", @"95", @"张爱奇", @"100.5", @"128", @"95"]];<br>

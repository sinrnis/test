# test
homework
BEGIN
    start_date = 1990-01-01
    target_date = 用户输入的日期
    
    // 计算两个日期相差多少天
    total_days = 计算两个日期之间的天数差(start_date, target_date)
    
    // 5 天一个周期
    remainder = total_days MOD 5
    
    IF remainder == 0 OR remainder == 1 OR remainder == 2 THEN
        输出 "打渔"
    ELSE
        输出 "晒网"
    END IF
END

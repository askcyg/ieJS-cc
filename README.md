# ieJS-cc
js封装的cocos creator扩展工具包


-----------------
日志库 ie.log
-----------------
ie.log.debug(text);
ie.log.info(text);
ie.log.error(text);
ie.log.setLevel(level);
ie.log.setTimeType(type);
ie.log.setDisplay(is);

    Level: {
        DEBUG: 1,
        INFO: 2,
        ERROR: 3
    },

    TimeType: {
        TIMESTAMP: 0,
        STRING: 1,
        SERVER: 2,
    },
    
-----------------
工具库 ie.util
-----------------
ie.util.timer 定时器类
ie.util.httpHelper http交互类

-----------------
ui扩展库 ie.uienca
-----------------
ie.uienca.loadingAnim 加载动画(遮罩层)类
ie.uienca.click 点击限制类


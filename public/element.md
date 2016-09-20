# 开始定义零件了

    // 通用零部件
    public class generalElement
    {
        string elementName;      // 名称
        string elementNumber;    // 图号
        int sepp;                // 单台用量
    }
    
    // 螺栓
    public class bolt
    {
        string boltNmae;        // 名称
        string boltNumber;      // 图号
        int sepp;               // 单台用量
        float boltD;            // 公称直径Mxx
        float boltL;            // 螺纹长度
    }
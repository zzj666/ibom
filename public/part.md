#部件的定义#

    public ckass part
    {
        string partName;  //部件名称
        string partNumber;  //部件图号
        int samePartOfOneProduct;  //单台用量
        bool isLeft; //是否分左右，1左，0右
        float partWeight;  //部件重量
        bool isSubParts;  //是否为子部件
        int haveSubParts;  //含有子部件数量，0 为不含子部件
        int havaSubProducts;  // 含有零件数量，0为独立部件
    }
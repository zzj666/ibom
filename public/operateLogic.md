# 这里都是业务逻辑所需要的函数或者说明


// 定义工艺路线，
// 1 "购->装"
// 2 "焊->装"
// 3 "机->装"
// 4 "焊->机->装"
private string ProcessRoute(int routeCode;)
{
    if(routeCode == 1)
        return "购->装";
    else if(routeCode == 2)
        return "焊->装";
    else if(routeCode == 3)
        return "机->装";
    else if(routeCode == 4)
        return "焊->机->装";
    else
        return "Error,wrong code";
}
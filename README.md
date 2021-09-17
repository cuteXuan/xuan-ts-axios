# xuan-ts-axios
cutexuan 使用ts实现axios


## 1、基础功能实现
### 1.1 处理url参数


##2、

## 扩展接口

## 拦截器
axios 拥有interceptors对象属性，该属性有request和
response两个属性，对外提供use方法。

拦截器的执行顺序是链式依次执行的方式，对于request拦截器，
后添加的拦截器会在请求的过程中先执行。
对于response拦截器，先添加的拦截器会在响应后先执行

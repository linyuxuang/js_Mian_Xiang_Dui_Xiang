# js_Mian_Xiang_Dui_Xiang
js_面向对象(基础)



	数据属性  
			      数据属性有四个描述其行为的特性
			      
            configurable   true可以删除   false 不能删除 (默认true)
            enumerable   true可以 for-in 循环属性   false 不能  (默认true)
            writable        true可以修改属性   false不能修改属性  (默认true)
            value    读取属性值时,从这个位置读, 写入属性值时 ,保存新值在这个位置  (默认undefined)



                Object.defineProperty() 要修改属性默认属性 ,必须用这个方法
                
                      参数 :
                           第一个参数 属性所在对象 
                           第二个参数  属性名字
                           第三个参数  一个描述符对象
                           
                           
                           
                    var obj={};
                    Object.defineProperty(obj,"name",{
                      writable:false,
                      value:"ooop",
                    });

                    obj.name="kkk";
                    console.log(obj.name);    输出 ooop










关于Promise的一些理解和小例子
===
* 含义  
  Promise对象用于一个异步操作的最终完成或失败及其结果值的表示。简单点说，它就是用于处理异步操作的，异步处理成功了就执行成功的操作，失败了就捕获错误或则停止后续操作。  
  它的一般表示形式为：    
new Promise(  
    function(resolve,reject){  
        if(success){  
            resolve();  
        }else{  
            reject();  
        }  
    }  
)

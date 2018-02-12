## jstat 
命令格式 `jstat -<option> [-t] [-h<lines>] <java进程id> [<interval> [<count>]]`
> jstat [ generalOption | outputOptions vmid [ interval[s|ms] [ count ] ]

其中的 vmid 格式为
    [protocol:][//]lvmid[@hostname[:port]/servername]
    protocol  如果省略了这个参数,也没有指定hostname 默认的协议是 platform-specific optimized 如果
          指定了hostname 但是省略了protocol 默认就是rmi



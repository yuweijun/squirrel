## 五笔输入法鼠须管 0.9.26.2 版本配置

```bash
$ cd ~/Library/Rime
$ vi default.custom.yaml

# default.custom.yaml
# encoding: utf-8
patch:
  schema_list:
    - schema: wubi86
```

```bash
$ vi wubi86.custom.yaml

# wubi86.custom.yaml
# encoding: utf-8
#
patch:
  translator/enable_user_dict: false
```  

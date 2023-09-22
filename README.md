# config

公用配置库


示例：

```
go get -u git.beeps.cn/jiazujiang/config

import "git.beeps.cn/jiazujiang/config"

if err := config.Viper.UnmarshalKey("postgresql", &PostgreSQL); err != nil {
		panic(err)
	}
```


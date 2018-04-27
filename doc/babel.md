# 配置文件 .babelrc #
Babel 的配置文件是.babelrc，存放在项目的根目录下, 作用：设置转码规则和插件

1.presets字段设置转码规则，官方提供以下的规则集，你可以根据需要安装
	# 最新转码规则
	$ npm install --save-dev babel-preset-latest
	# react 转码规则
	$ npm install --save-dev babel-preset-react
	# 不同阶段语法提案的转码规则（共有4个阶段），选装一个
	$ npm install --save-dev babel-preset-stage-0
	$ npm install --save-dev babel-preset-stage-1
	$ npm install --save-dev babel-preset-stage-2
	$ npm install --save-dev babel-preset-stage-3
加入到.Babelrc中
 {
    "presets": [
      "latest",
      "react",
      "stage-2"
    ],
    "plugins": []
  }

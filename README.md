## Install

```
npm i jk-react-selector
```

## Usage

```
import Selector from 'jk-react-selector';
//function:
  showConsole=()=>{
    
  }
//render:
    const allData = [
      { key: 1, name: '事假' },
      ...
      ]
      //'key' and 'name' are neccessary properties
    const title = "请选择xxx"
//return:
    <Selector
      title = {title} //选择器标题,title message
      titleShow = {true/false}  //是否显示标题,if title show
      data = {allData}   //选择器要显示的列表数据,data items you want to show
      onSelect = {this.showConsole.bind()}  //点击item的回调函数,callback function
    />
  )
}

```

## Tips

```
1、you can not have the same name items in data

wrong examples:

    const allData = [
      { key: 1, name: '事假' },
      { key: 2, name: '年假' },
      { key: 3, name: '事假' },
      ...
      ]

2、onSelect() must be a function

you can code as  "this.xxx.bind()" or "()=>this.xxx()" but not "this.xxx()"

```

## keyword
```

react   selector  mobile

```

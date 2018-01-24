# jojo

如果用v-if时结构一样的情况下 如果不加key默认只会更改文本不会更改样式 初始目的是为了更好的渲染

v-for比v-if优先级高  小技巧<div v-for='item in items' v-if="item.news"></div>使用场景为如果这个item里面有新闻才显现出来

配置子路由时默认直接跳转地址为 ''的

行内加上v-cload有效阻止闪屏与显示变量 或者在style标签里面加上[v-cloak]{style:none}但要注意 如果是外部引入样式注意是用 import还是link 因为import是dom加载完毕后才执行的


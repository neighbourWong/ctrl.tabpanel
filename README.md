# ctrl.tabpanel

## 最新版本

**1.0rc1**

## 依赖

- [lib.motion](https://github.com/AlibabaMobileFrontEnd/lib.motion)
- [lib.gesture](https://github.com/AlibabaMobileFrontEnd/lib.gesture)
- [lib.scroll](https://github.com/AlibabaMobileFrontEnd/lib.scroll)
- [ctrl.tabheader](https://github.com/AlibabaMobileFrontEnd/ctrl.tabheader)

## 如何使用

### 初始化

    var Tabpanel = ctrl.tabpanel;
    var instance = new Tabpanel();
    document.body.appendChild(instance.root);
    instance.viewModel = [
        {text: 'tab1', html: 'panel1'},
        {text: 'tab2', html: 'panel2'}
    ];

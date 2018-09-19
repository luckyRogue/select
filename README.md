# 可以自定义样式的下拉框 <br>
html结构为
> <div class="select-box">
        <div class="sb-ac">
            <span>请选择国家 V</span>
        </div>
        <ul class="slide">
            <li class="item">中国</li>
            <li class="item">美国</li>
            <li class="item">韩国</li>
            <li class="item">日本</li>
            <li class="item">火之国</li>
        </ul>
    </div>
>
调用方法
> $('.select-box').select({
            slideBox: '.slide', //下拉框
            option: '.item',  //下拉框里的子元素
            showBox: 'span' //显示内容的地方
        });
>
需传递三个参数

colspan 属性规定单元格可横跨的列数。
type='radio' checked默认选中，name必须相同，不然不能单选
type='checkbox' checked默认选中，name不同，因为name会提交到服务器中，如果name相同，就会出现覆盖（但是checkbox是多选），
可以在name值后面加[]，这样获取的就是name数组了
 border-collapse:collapse可以消除table中td的间隙，合并td边，但是要放在table样式中
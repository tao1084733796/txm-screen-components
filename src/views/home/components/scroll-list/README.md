# scroll-list
  * 自动滚动组件，可以根据父组件高度自适应展示内容，父组件需要设置高度
  * 组件默认列表数据左对齐，字号16px，行高32px，列表不自动滚动，超出td范围横向滚动，单元格宽度根据数据平均等分
### scroll-list Attributes
| 参数  | 说明   | 类型  | 可选值  | 默认值  |
|-------|-------|------|--------|--------|
| scrollId | 滚动组件的id | string | -- |

### 其他
  * @param scrollId {string, (必填)} - 滚动组件id，
  * @param scrolltime {number, (可填)} - 滚动的时间，默认3000
  * @param stayTime {number, (可填)} - 滚动结束后 每屏停留时间，默认10000
  * @param auto {boolean, (可填)} - 是否开启滚动，默认不滚动
  * @param scrollListNum {number, (可填)} - 每次滚动的数据条数，默认全屏滚动
  * @param visible {number, (可填)} - 指定范围内可见条数，默认适应的最优条数
  * @param rowStyle {Object, (可填)} - 表格内容每行样式
  * @param theadStyle {Object, (可填)} - 表头样式
  * color {string, (可填)} - 每行数据中加color属性，可以设置列表column内容样式  { field: '', color: '#fff37e' }
  * data-- 表头数据及表头配置项
  * 每行数据中加color属性，可以设置该列表格数据颜色
  * 每行数据中加roll: false，可以关闭文字的横向滚动，超出部分省略号并title提示



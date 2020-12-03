
2020/11/20

# 舊版: https://960.gs/demo.html
# BS: https://www.layoutit.com/build

# BS排版原理
  1. 起手式規則: row
  2. BS=> 手機優先，所以一開始就是在做手機板型　col-3
  3. 口決：col上一層只能是row，row裡面只能是col，row外面至少補container
  4. 不要在col-6裡面在做padding -> 鐵則
  5. 口決：先看權重，再看先後
  6. 順序：col-6 col-sm-6 col-md-6 col-lg-6 col-xl-6 有權重才能蓋過去
     => 例如：col-12 col-md-3，手機1欄，平板以上3欄
  7. 格線系統-容器
     元件
  8. 依照習慣去做開發
 
# SCSS 整合 BS
  1. 載入bootstrap,做引用，修改BS _variables.scss 做修正
  2. function/mixin/variables 一定要載入
  3. utilities => import 通用類別,各種工具類class，約18種可使用
  4. root =>
  5. reboot => reset/normalize
  6. grid.tables.forms.buttons => 元件
  7. 順序　=> 環境，reset，元件(表單、格線)，util
  8. 自訂>元件>容器>元件>util
  9. tinypng => 壓縮圖片
  10. - ul>li => 群組，seo會比較好，後端看有條有理，列表使用
      - Div=>不是群組
　11. 設計式設計出稿通常會有一定倍數: 4倍數/8倍數，通常都抓偶數倍
　　　- web UI是有規則，不是平面設計思維
　12. layout,page,要變少=> 元件化
     
https://www.museum-kawakyu.jp/
https://bm.s5-style.com/

下禮拜：
  想詢問如果是遇到多語系的話，要怎做修改


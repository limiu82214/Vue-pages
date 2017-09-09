# Vue-pages
簡單的分頁套件

### Demo
![Alt demo](/../usage_source/resource/demo.png "Demo")

使用範例：見 example.html

### 參數

| 參數                  | 資料型別 | 是否必填 | 功能                     | 預設值 |
| -------------------- | ------ | ---| ---|---| 
| `show_head`           | Boolean  | N        | 顯示"首頁"字樣           | false  |
| `show_tail`           | Boolean  | N        | 顯示"尾頁"字樣           | false  |
| `total_pages`         | Number   | Y        | 總頁數                   | none   |
| `counts_page`         | Number   | Y        | 一次顯示幾頁             | none   |
| `current_page`        | Number   | N        | 當前頁數                 | 1      |
| `v-on:set_page_event` | Event    | N        | 當頁數改變時會呼叫的事件 | none   |

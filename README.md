# SarbeerFrontEnd
公司學習筆記（每日更新）<br />
### gitbook install<br />
https://wcc723.github.io/design/2014/09/04/gitbook-install/<br />

## 公司額外的學習（在專案上遇到的問題）
<strong>1.控台即時注單在玩家端下注的時候，safari沒有即時更新的問題</strong><br />
★changeDetection<br />
https://blog.kevinyang.net/2017/01/23/angular2-change-detection/<br />

★Default和 OnPush 細節部份<br />
https://blog.kevinyang.net/2016/06/05/angular2-ChangeDetectionStrategy/<br />
https://segmentfault.com/a/1190000008754052<br />
https://blog.kevinyang.net/2017/08/09/angular-changedetector-markforcheck/<br />

https://www.youtube.com/watch?v=bst0w7-EklY<br />

```
ERROR Error: ViewDestroyedError: Attempt to use a destroyed view: detectChanges

 // 使用 takeUntil 中斷 subscription
  public ngOnDestroy() {
    this.unsubscribe.next();
    this.unsubscribe.complete();
  }
```

使subscription中斷處理，不然會報錯上面error<br />

★測試prod或營運的環境方法<br />
環境變數要測prod 寫入w2<br />
若要側betlink有一個網址 在headers那邊可以看到<br />

★queryString<br />
queryString 出現％20 為空格字串<br />
https://msdn.microsoft.com/zh-tw/library/system.web.httprequest.querystring(v=vs.110).aspx<br />
詳細％20 其他輸入對應encode表<br />
http://www.w3school.com.cn/tags/html_ref_urlencode.html<br />

## 問題區
ＳＰＡ的請教 與ts 語法(res=>res.json()).subscribe(查看<br/>
interface class 差異


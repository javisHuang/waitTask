介紹
============

在android中實現如javascript的setTimeout

使用
=====
setTimeout(OnTimeoutListener onTimeoutListener, int sec)

onTimeoutListener 參數是new waitTask.OnTimeoutListener()

sec 參數是設定幾毫秒後執行onTimeout裡的程式

```java
	waitTask waittask = new waitTask();
	waittask.setTimeout(new waitTask.OnTimeoutListener() {
		public void onTimeout() {
			\\輸入要執行的程式碼，也可對view下執令
		}
	}, 1);
```

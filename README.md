# runaway-of-focus-event
input要素にfloatがかかっていると、要素外をクリックしても`focus`イベントが発火する（Chrome64.0.3282.186とSafari9.0.2で再現）。

![focusイベント](focus.gif)

"# SlotMachines"

[拉霸範例](https://github.com/matthewlein/jQuery-jSlots)

## Option

    $.jSlots.defaultOptions = {
        number : 3,          // 數量：插槽數量
        winnerNumber : 1,    // 數字或陣列：觸發獲勝的清單項目編號，從 1 開始的索引，而不是從零開始
        spinner : '',        // CSS 選擇器：將開始事件綁定到的元素
        spinEvent : 'click', // 字串：在此事件上啟動插槽的事件
        onStart : $.noop,    // 功能：自旋啟動時運行，
        onEnd : $.noop,      // 功能：在旋轉端運作。它被傳遞（finalNumbers:Array）。 FinalNumbers 給出每個槽依序停止的 li 的索引。
        onWin : $.noop,      // 功能：按中獎號碼運行。已通過 (winCount:Number, Winners:Array, FinalNumbers:Array)
        easing : 'swing',    // 字串：最終旋轉的緩動類型。我推薦 easing 插件和 easeOutSine，或者您選擇的 easeOut。
        time : 7000,         // Number：旋轉動畫的總時間
        loops : 6            // Number：動畫期間旋轉的次數
    };
